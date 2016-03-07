# Basics

### Link to the Github Repository for the Project
[Your Repo](https://github.com/jillmd501/stevetime)

### Link to the Deployed Application
[Your Application](https://realstevetime.herokuapp.com/)

### Link to Your Commits in the Github Repository for the Project
[Your Commits](https://github.com/jillmd501/stevetime/commits/master)

### Provide a Screenshot of your Application
![spacejam](http://i.imgur.com/oypEwbp.png)

## Completion

### Were you able to complete what you feel is the base functionality?
#### If not, list what functionality you think may be missing missing.

I was not able to close the poll.

### What features did you complete which you feel 'exceeded expectations'?


# Code Quality

### Link to a specific block of your code on Github that you are proud of
[client.js](https://github.com/jillmd501/new-steve-time/blob/master/public/client.js#L11-L19)

#### Why were you proud of this piece of code?
I used to be pretty bad about having FAT views. In this piece of code, I was able to pull in my voteCount method and even have the styling/formatting done so I could just plop it on the page. 

### Link to a specific block of your code on Github that you feel not great about
#### Why do you feel not awesome about the code? What challenges did you face trying to write/refactor it?

### Attach a screenshot or paste the output from your terminal of the result of your test-suite running.

### Provide a link to an example, if you have one, of a test that covers an 'edge case' or 'unhappy path'

it('will not tally multiple votes', function(){
  var expectedResult = {'jill': 2, 'joe': 2}
  expect(countVotes(poll)).to.deep.equal(expectedResult)
});

-----

### Please feel free to ask any other questions or make any other statements below!
