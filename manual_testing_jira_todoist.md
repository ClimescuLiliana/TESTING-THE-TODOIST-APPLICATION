<h1>Testing Project for **TODOSIT**</h1>

Application under test: TODOIST
Tools used: Jira, Zephyr Squad.

Functional specifications:
The below story: Create a new task to organize my activities AND As a user, I want to be able to edit an existing task so that I can update its information was created in Jira and describes the functional specifications of the "TODOIST" module, for which the final project is performed upon.

![story 1 1](https://github.com/user-attachments/assets/f58f2fc4-4943-461f-b08c-a9ce99918ca6)
![story 2 2](https://github.com/user-attachments/assets/ecb0f76b-5900-4bd7-87ff-ea3706c302c7)


Here you can find the release that was created for this project:

![REALEASE VS1 1](https://github.com/user-attachments/assets/b5900f56-13d1-4bce-a1f7-cab3924bb075)

Testing process
The test process was performed based on the standard test process as described below.

1.1 Test planning
The Test Plan is designed to describe all details of testing for all the modules from the Todoist application.

The plan identifies the items to be tested, the features to be tested, the types of testing to be performed, the personnel responsible for testing, the resources and schedule required to complete testing, and the risks associated with the plan. The test plan that was created for this project can be found here (https://docs.google.com/document/d/17Ox1PG5PV_fWRuPUjeSOXzqVOWOpf37qDepUGUjP_tE/edit)

1.1.1. Roles asigned to the project and persons allocated
(CLIMESCU LILIANA, NASTASE DOINA, PAUN ALIN)

*Project manager
*Product owner
*Software developer
QA Engineer
1.1.2 Entry criteria defined
*All functional requirements are documented and approved.
*The test environment is configured and accessible.
*Testing resources (testers, tools) are available.

1.1.3 Exit criteria defined
*All test cases have been executed.
*All critical and major bugs have been fixed or documented.
*The final test report is complete and approved.

1.1.4 Test scope

1.Testing the creation of a task with a valid title.
2.Testing the creation of a task with a missing title (negative test).
3.Testing editing an existing task.
4.Testing the change in the term of a task.
5.Testing the deletion of a task.
6.Testing the reactivation of an archived task.
7.Testing setting a priority for a task.
8.Testing adding a comment to a task.
9.Testing the completion of a task.
10.Testing reminder notifications for near-term tasks.

Types of Testing:
Functional Testing: Testing the aforementioned functionalities to verify the correctness of the implementation.
Interface Testing (UI): Checking the appearance and functionality of the interface.
Performance Testing: Checking the response time of the application under different loads.
Compatibility Testing: Checking the operation of the application on different devices and browsers.
Test Environment:
Devices: Desktop, mobile (Android, iOS).
Browsers: Chrome, Firefox, Safari.
Operating Systems: Windows, macOS, iOS, Android.
Testing Tools:
JIRA: For requirements and bug management.
Zephyr: For managing and running test cases.
BrowserStack: For cross-browser and cross-platform testing.

Tests not in scope:
Testing Premium Features
Testing the performance of the application when handling an extremely large number of tasks (ex: 10,000 concurrently active tasks).
Advanced security testing
Testing the application on very old versions of operating systems, such as iOS 10 or Android 5.
Testing translations for all languages ​​available in the app.
Checking date, time and numbering formats specific to each region.
Testing integrations with other applications such as Google Calendar

1.1.5 Risks detected
Project risks:
Unrealistic delivery times.
Frequent changes in requirements.
Limited testing resources.

Product risks:
Missing archive button.
Task priority visibility issues.
Notifications not working properly.

1.1.6 Evaluating entry criteria
All functional requirements are documented and approved.
The test environment is configured and accessible.
Testing resources (testers, tools) are available.

1.2 Test Monitoring and Control
The reason why the monitoring and control stage was done for:
Identifies deviations from the original test plan, such as delays, unanticipated problems, or requirements changes.
Maintains the quality of the testing process by continuously monitoring progress and adjusting testing activities as necessary.
Ensure effective communication between team members and other stakeholders so that everyone is aware of the current status of the project.
Manage previously identified risks through corrective or preventive actions to minimize their impact on final deliverables.

How the monitoring and control stage was carried out:

Tracking the progress of testing activities
Bug management and reporting
Test metric review
Status and synchronization sessions

![matricicea trasabilitatii - proiect Climescu Rodica liliana](https://github.com/user-attachments/assets/05af4952-313f-4ea7-b39d-494ea2be588d)


1.3 Test Analysis
The testing process will be executed based on the application requirements. 

The following test conditions were found:

Testing the creation of a task with a valid title.
Testing the creation of a task with a missing title (negative test). 
Testing editing an existing task. 
Testing the change in the term of a task. 
Testing the deletion of a task. 
Testing the reactivation of an archived task. 
Testing setting a priority for a task. 
Testing adding a comment to a task. 
Testing the completion of a task. 
Testing reminder notifications for near-term tasks.

1.4 Test Design
Functional test cases were created in Zephyr Squad based on the analysis of the specifications. The test cases can be accessed here: (https://docs.google.com/document/d/1xcOqpuw53SxTWgddkMyx7wggK_uOqahdYtrQ3AeTU1I/edit)

1.5 Test Implementation
The following elements are needed to be ready before the test execution phase begins:

Execution of test cases
Respecting the timeline
Test accuracy
The quality of test scripts
Identifying and Reporting Bugs
Communication and Collaboration Efficiency
Traceability matrix
Risk assessment

1.6. Test Execution
Test cases are executed on the created test Cycle summary: Vs.1.1. - My project Todoist

Bugs have been created based on the failed tests. The complete bug reports can be found here: (https://docs.google.com/document/d/151tWpwVUqX5iBPK3xMwHeBSrEWv_-q5oxp1fqu3S4os/edit)

The following is a summary of the bugs that have been found 
(https://docs.google.com/document/d/1ztJMtTghRhhMiN1_vs-cMJonZl1CdSjLTTSbLY5XhJM/edit)

Full regression testing is needed on the impacted areas after the bugs are fixed and retesting will be done for every functionality that was previously failed.

1.7 Test Completion
As the Exit criteria were met and satisfied as mentioned in the appropriate section, this feature is suggested to ‘Go Live’ by the Testing team
The traceability matrix was generated and can be found here: ![matricicea trasabilitatii - proiect Climescu Rodica liliana](https://github.com/user-attachments/assets/b41698e7-ac66-42b4-80ae-50c745955d0f)


Test execution chart was generated and can be found below.

![raport de executie-proiect jira](https://github.com/user-attachments/assets/7bd48e00-8d16-4f81-a3eb-6e4f68a18d79)

The final report shows that a number 5 tests have failed of a total of 10.

A number of 5 total bugs were found, from which the priority is: 2 are high and 3 are medium.
