# Design tests for Jira

## Story

Let’s get deeper into working with Jira and discovering Zephyr Scale a little further.
This week your mission as a team will be to:

- Get familiar with a Test Management tool for Jira
- Design tests consciously, based on ISTQB suggestions
- Use folders in Zephyr Scale to organize the test-cases
- Make sure your manual test cases can be executed by other testers, even without the knowledge of the specific software

### Expectations:

- Every test should be built around the following ideology

    - Preconditions set
    - Action implemented
    - Verification implemented
    - Reset test data

- Tests should be independent of each other (run order should not affect the result)
- You don’t have to execute the tests in this project, just work on designing the best tests possible

The list of tasks below contains the functions to be tested.

## What are you going to learn?

- Design and Implement Manual Test cases in Zephyr Scale (Test Design)
- Building your testing mindset :)
- Teamwork

## Tasks

1. As a registered user, I want to log in to Jira, so that I can use most functionalities. Example tests - Empty credentials, Wrong password, Captcha after 3rd try, Successful Login
    - Validate that login functionalities work correctly

2. As a registered user, I want to log out from Jira, so that I can protect my private data
    - Validate that logout functionalities work correctly

3. As a logged in user, I want to Browse existing Projects, so that I can access the details of tasks
    - Validate the Browse Project functionalities
    - In Projects / View all projects the available projects should contain COALA, JETI, and TOUCAN projects

4. As a logged in user, I want to create a new issue, so that I can track my tasks in any project
    - Validate the Create Issue functionalities
    - Using the Create button to create an issue, projects COALA, JETI and TOUCAN should be available to choose from
    - Using the Create button, for projects COALA, JETI, or TOUCAN, the available issue types to create should be Story, Task, Bug, and Sub-task

5. As a logged in user, I want to browse existing issues, so that I can access the details of tasks
    - Validate the Browse Issue functionalities
    - TOUCAN project has at least 3 issues that can be browsed individually (with ID 1, 2, 3)
    - JETI project has at least 3 issues that can be browsed individually (with ID 1, 2, 3)
    - COALA project has at least 4 issues that can be browsed individually (with ID 1, 2, 3, 4)

6. Every issue is editable by your user
    - Validate the Edit Issue functionalities
    - TOUCAN project’s issue with ID 1, 2 and 3 can be edited by your user
    - JETI project’s issue with ID 1, 2 and 3 can be edited by your user
    - COALA project’s issue with ID 1, 2, 3 and 4 can be edited by your user

7. Write a test plan
    - Determining the scope and objectives of testing
    - Defining the overall approach of testing, the test strategy and test schelude
    - Defining the preconditions and definition of done
    - Identify the risk assumptions

8. Write the purposes and contents for test reports
    - The test report should be included summary of all test activites and test results, such as number of test cases and bugs, duration etc. You can use Jira dashboard.

9. Determining defect management process
    - You can use traceability matrix for the test results are shown on different environments

## General requirements

- Make sure you only work your team’s newly created Zephyr Scale folder. Do not add or delete test cases from other Zephyr Scale folders!
- In case you find a bug, discuss it with your team-mates and try to collect as many details about the bug as possible before reporting it into Jira
- Make sure the test cases for the features are added to Zephyr Scale
- Make sure there are preconditions added to the test cases
- Make sure the steps are added into the test cases
- Make sure the test data column is fulfilled when needed

## Hints

- Explore the system’s behaviour before designing the test cases
- We never said that everything is configured correctly…
- Use your browser in incognito mode when executing the tests
- Don’t forget to ask (the internet, your peers, and then your mentors) in case you have any questions!

## Background materials

- <i class="far fa-exclamation"></i> [Zephyr Scale Documentation - Test Cases](https://support.smartbear.com/zephyr-scale-server/docs/test-cases/index.html)
- <i class="far fa-exclamation"></i> [How to Write Test Cases for Software - with a sample](https://blog.testlodge.com/how-to-write-test-cases-for-software-with-sample/)
- <i class="far fa-exclamation"></i> [Writing Test Cases from User Stories & Acceptance Criteria](https://blog.testlodge.com/how-to-write-test-cases-for-software-with-sample/)
- <i class="far fa-exclamation"></i> [Positive vs Negative vs Destructive Test Cases](https://blog.testlodge.com/how-to-write-test-cases-for-software-with-sample/)
