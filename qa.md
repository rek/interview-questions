# Quality Testing

## What is the difference between Quality Assurance, Quality Control and testing?

- Quality Assurance is the process of planning and defining the way of monitoring and implementing the quality (test) processes within a team and organization. This method basically defines and sets the quality standards of the projects.

- Quality Control is the process of finding defects and providing suggestions to improve the quality of the software. The methods used by Quality Control are usually established by the quality assurance.

It is the primarily responsibility of the testing team to implement quality control.

- Testing is the process of finding defects / bug. It validates whether the software built by the development team meets the requirements set by the user and the standards set by the organization.

Here the main focus is on finding bugs and testing team acts as quality gatekeeper.

## In your own words, explain a bug life cycle.

Bug Life Cycle is also referred to as Defect life cycle. It is a software testing cycle where a bug or defect goes through its lifetime. It consists of several stages:

1. A tester finds a bug. He or she assigns it with either Open or New status.
1. The found bug is then assigned to a particular development project coordinator. He or she analyzes the nature of the bug. The manager will determine whether the bug is valid or not. If the defect is not valid, then the project coordinator will reject the bug with the status “Rejected.”
1. When it is not, the next step is to check whether the scope of the defect is checked. In the case the defect is not part of the current release, then that defect is postponed.
1. In this stage, the tester evaluates whether a defect similar to the current one had earlier been discovered. If yes, the bug is assigned with a “Duplicate” status.
1. The bug is now assigned to a developer. It is assigned with a status “In Progress.”
1. After fixing the code, the bug is assigned with a status “Fixed.”
1. Last but not least, the tester re-tests the code. If the code passes to what we refer to as test case, the bug is “Closed.” If the test case fails, the defect is re-opened. Once again, it is assigned to the developer until it passes test case.

## What is the difference between Test Plan and Test Strategy

- Test Strategy is at a higher level, mostly created by the Project Manager which demonstrates the overall approach of the testing for the entire project.

- Test plan basically depicts the how the testing should be performed for a particular application, falling under a project.

## How do you define a format of writing a good test case?

A test case has the below format:

- Test case ID,
- Test case description
- Severity
- Priority
- Environment
- Build version
- Steps to execute
- Expected results
- Actual results

## Suppose you find a bug in production, how would you make sure that the same bug is not introduced again?

Best way is to immediately write a test case for the production defect.
This way we ensure that the bug does not get introduced again.

Also it is good to think of alternate test cases or similar kinds of test cases and include them in our planned execution.

## Mention the different types of software testing?

- Unit testing
- Integration testing and regression testing
- Negative testing
- Functional testing
- Performance testing
- Load testing and stress testing

## What is the difference between functional and nonfunctional testing?

- Functional testing: deals with the functional aspect of the application. This technique tests that the system is behaving as per the requirement and specification.

- Nonfunctional testing: it tests NOT the requirement, but the environmental factors like performance, load and stress.

## What is negative testing? How is it different from positive testing?

- Negative testing is a technique which validates that the system behaves gracefully in case of any invalid inputs.
For example, in case user enters any invalid data in a text box, system should display a proper message instead of technical message which the user does not understands.
Negative testing is different from positive testing in a way that positive testing validates that our system works as expected and compares the test results with the expected results.

## What are the tools used by a tester while testing?

- Selenium
- Firebug
- OpenSTA
- WinSCP
- YSlow for FireBug
- Web Developer toolbar for firebox

## What is Ad Hoc testing?

It is a testing phase where the tester tries to break the system by randomly trying the system’s functionality.  It can include negative testing as well.

