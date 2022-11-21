# ECE444-F2022-Lab6

## Reference 
Hi this is Nathan Coelho and this repo is a clone of the docker-prep branch of https://github.com/ECE444-2022Fall/Assignment_1_starter_template

## Test Cases
I added some simple Jest testing for React code we added.
https://github.com/Group12-TripleFour/Project1/blob/main/Education_Pathways/frontend/src/App.test.js
https://github.com/Group12-TripleFour/Project1/blob/main/Education_Pathways/frontend/src/components/FeedbackSubmitPage.test.js
https://github.com/Group12-TripleFour/Project1/blob/main/Education_Pathways/frontend/src/components/feedbacks/NewFeedbackForm.test.js

## TDD Pros and Cons
### Pros
- only necessary code is written since you always need a test for the code, you should not end up writing useless code
- it results in a more modular design as you separate functions to test them individually and avoid having one function do multiple things
- due to the modularity that comes with TDD, the code is more extensible as you have individual parts you can change and tests to show if your change breaks that individual part
- eases the debugging process by singling out issues to specific functions
- helps to document the functions and helps developers better understand their own code

### Cons
- requires a lot more time and effort to continuously create tests for every function
- tests need to be maintained along with the code and may need understanding from external libraries not relevant to the main code (this adds to the extra time and effort required with TDD)
- every team member must participate because you need the whole code to be tested for it to be worth doing (can also be a pro to force everyone to commit to TDD)
- can be hard to learn after having never done it
- may need to mock certain functions and make entire classes just to test simple functionalities with things like databases
