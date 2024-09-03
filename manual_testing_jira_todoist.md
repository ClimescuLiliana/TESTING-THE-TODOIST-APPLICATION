<h1>Testing Project for **TODOSIT**</h1>

Application under test: TODOIST
Tools used: Jira, Zephyr Squad.

<h2>Functional specifications:</h2>
  
The below story:
<ol>
<li>Create a new task to organize my activities</li>
<li>As a user, I want to be able to edit an existing task so that I can update its information was created in Jira and describes the functional specifications of the "TODOIST" module, for which the final project is performed upon.</li>
</ol>

![story 1 1](https://github.com/user-attachments/assets/f58f2fc4-4943-461f-b08c-a9ce99918ca6)
![story 2 2](https://github.com/user-attachments/assets/ecb0f76b-5900-4bd7-87ff-ea3706c302c7)


Here you can find the release that was created for this project:

![REALEASE VS1 1](https://github.com/user-attachments/assets/b5900f56-13d1-4bce-a1f7-cab3924bb075)

<h2>Testing process</h2>
The test process was performed based on the standard test process as described below.

<h3> 1.1 Test planning</h3> 
The Test Plan is designed to describe all details of testing for all the modules from the Todoist application. 

The plan identifies the items to be tested, the features to be tested, the types of testing to be performed, the personnel responsible for testing, the resources and schedule required to complete testing, and the risks associated with the plan. The test plan that was created for this project can be found here (https://docs.google.com/document/d/17Ox1PG5PV_fWRuPUjeSOXzqVOWOpf37qDepUGUjP_tE/edit)

<h4>1.1.1. Roles asigned to the project and persons allocated:</h4>

<ul>
<li>Project manager:NASTASE DOINA</li>
<li>Product owner:ONOFREI ALEX</li>
<li>Software developer:PAUN ALIN</li>
<li>QA Engineer:CLIMESCU LILIANA</li>
</ul>
  
<h4>1.1.2 Entry criteria defined</h4>

<ul>
<li>All functional requirements are documented and approved.</li>
<li>The test environment is configured and accessible.</li>
<li>Testing resources (testers, tools) are available.</li>
</ul>

<h4>1.1.3 Exit criteria defined</h4>
  
<ul>
<li>All test cases have been executed.</li>
<li>All critical and major bugs have been fixed or documented.</li>
<li>The final test report is complete and approved.</li>
</ul>

<h4>1.1.4 Test scope</h4>

<h5> Tests in scope: </h5>
<Ol>
<li>Testing the creation of a task with a valid title.</li>
<li>Testing the creation of a task with a missing title (negative test).</li>
<li>Testing editing an existing task.</li>
<li>Testing the change in the term of a task.</li>
<li>Testing the deletion of a task.</li>
<li>Testing the reactivation of an archived task.</li>
<li>Testing setting a priority for a task.</li>
<li>Testing adding a comment to a task.</li>
<li>Testing the completion of a task.</li>
<li>Testing reminder notifications for near-term tasks.</li>
</ol>

<h5>Types of Testing:</h5>
<ul>
<li>Functional Testing: Testing the aforementioned functionalities to verify the correctness of the implementation.</li>
<li>Interface Testing (UI): Checking the appearance and functionality of the interface.</li>
<li>Performance Testing: Checking the response time of the application under different loads.</li>
<li>Compatibility Testing: Checking the operation of the application on different devices and browsers.</li>
</ul>
  
<h5>Test Environment:</h5>
<ul>
<li>Devices: Desktop, mobile (Android, iOS).</li>
<li>Browsers: Chrome, Firefox, Safari.</li>
<li>Operating Systems: Windows, macOS, iOS, Android.</li>
</ul>
  
<h5>Testing Tools:</h5>
<ul>
<li>JIRA: For requirements and bug management.</li>
<li>Zephyr: For managing and running test cases.</li>
<li>BrowserStack: For cross-browser and cross-platform testing.</li>
</ul>

<h5>Tests not in scope: </h5>

<ul>
<li>Testing Premium Features</li>
<li>Testing the performance of the application when handling an extremely large number of tasks (ex: 10,000 concurrently active tasks).</li>
<li>Advanced security testing</li>
<li>Testing the application on very old versions of operating systems, such as iOS 10 or Android 5.</li>
<li>Testing translations for all languages ​​available in the app.</li>
<li>Checking date, time and numbering formats specific to each region.</li>
<li>Testing integrations with other applications such as Google Calendar</li>
</ul>

<h4>1.1.5 Risks detected</h4>

<h5>Project risks:</h5>
<ul>
<li>Unrealistic delivery times.</li>
<li>Frequent changes in requirements.</li>
<li>Limited testing resources.</li>
</ul>

<h5>Product risks:</h5>
<ul>
<li>Missing archive button.</li>
<li>Task priority visibility issues.</li>
<li>Notifications not working properly.</li>
</ul>
  
<h4>1.1.6 Evaluating entry criteria</h4>
<ul>
<li>All functional requirements are documented and approved.</li>
<li>The test environment is configured and accessible.</li>
<li>Testing resources (testers, tools) are available.</li>
</ul>

<h3>1.2 Test Monitoring and Control</h3>
The reason why the monitoring and control stage was done for:
<ul>
<li>Identifies deviations from the original test plan, such as delays, unanticipated problems, or requirements changes.</li>
<li>Maintains the quality of the testing process by continuously monitoring progress and adjusting testing activities as necessary.</li>
<li>Ensure effective communication between team members and other stakeholders so that everyone is aware of the current status of the project.</li>
<li>Manage previously identified risks through corrective or preventive actions to minimize their impact on final deliverables.</li>
</ul>
How the monitoring and control stage was carried out:
<ul>
<li>Tracking the progress of testing activities</li>
<li>Bug management and reporting</li>
<li>Test metric review</li>
<li>Status and synchronization sessions</li>
</ul>

![matricicea trasabilitatii - proiect Climescu Rodica liliana](https://github.com/user-attachments/assets/05af4952-313f-4ea7-b39d-494ea2be588d)


<h3>1.3 Test Analysis</h3>
The testing process will be executed based on the application requirements. 

The following test conditions were found:
<ul>
<li>Testing the creation of a task with a valid title.</li>
<li>Testing the creation of a task with a missing title (negative test).</li>
<li>Testing editing an existing task.</li> 
<li>Testing the change in the term of a task.</li>
<li>Testing the deletion of a task.</li>
<li>Testing the reactivation of an archived task.</li> 
<li>Testing setting a priority for a task.</li> 
<li>Testing adding a comment to a task.</li> 
<li>Testing the completion of a task.</li> 
<li>Testing reminder notifications for near-term tasks.</li>
</ul>

<h3>1.4 Test Design</h3>
Functional test cases were created in Zephyr Squad based on the analysis of the specifications. The test cases can be accessed here: (https://docs.google.com/document/d/1xcOqpuw53SxTWgddkMyx7wggK_uOqahdYtrQ3AeTU1I/edit)

<h3>1.5 Test Implementation</h3>
The following elements are needed to be ready before the test execution phase begins:
<ul>
<li>Execution of test cases</li>
<li>Respecting the timeline</li>
<li>Test accuracy</li>
<li>The quality of test scripts</li>
<li>Identifying and Reporting Bugs</li>
<li>Communication and Collaboration Efficiency</li>
<li>Traceability matrix</li>
<li>Risk assessment</li>
</ul>

<h3>1.6 Test Execution </h3>
Test cases are executed on the created test Cycle summary: Vs.1.1. - My project Todoist

Bugs have been created based on the failed tests. The complete bug reports can be found here: (https://docs.google.com/document/d/151tWpwVUqX5iBPK3xMwHeBSrEWv_-q5oxp1fqu3S4os/edit)

The following is a summary of the bugs that have been found 
(https://docs.google.com/document/d/1ztJMtTghRhhMiN1_vs-cMJonZl1CdSjLTTSbLY5XhJM/edit)

Full regression testing is needed on the impacted areas after the bugs are fixed and retesting will be done for every functionality that was previously failed.

<h3>1.7 Test Completion</h3>
As the Exit criteria were met and satisfied as mentioned in the appropriate section, this feature is suggested to ‘Go Live’ by the Testing team
The traceability matrix was generated and can be found here: ![matricicea trasabilitatii - proiect Climescu Rodica liliana](https://github.com/user-attachments/assets/b41698e7-ac66-42b4-80ae-50c745955d0f)


Test execution chart was generated and can be found below.

![raport de executie-proiect jira](https://github.com/user-attachments/assets/7bd48e00-8d16-4f81-a3eb-6e4f68a18d79)

The final report shows that a number 5 tests have failed of a total of 10. They covered the main functionalities of the app such as creating, editing, archiving and deleting tasks, setting priorities, reminder notifications and adding comments.

Requirements coverage: Approximately 90% of the requirements defined in the scope were covered by the tests performed.

A number of 5 total bugs were found, from which the priority is: 2 are high and 3 are medium. Major bugs, such as the lack of archiving functionality for tasks and the inability to set reminders for short-term tasks, have a significant impact on the user experience. Therefore, we recommend fixing these bugs before release to production.

Identified risks: We have identified several product risks, including the risk that major bugs may affect users' perception of the app's quality. These risks must be managed by prioritizing fixing issues before release.

Release Recommendations: We recommend that the production release be delayed until major bugs are resolved.

Lessons Learned: An important lesson learned from this project is the need to allocate more time and resources to testing integrations and extreme performance scenarios. It is also essential to include a testing process for premium features, even if they are less accessible, to ensure full coverage of requirements.

In conclusion, the testing revealed that the Todoist app is almost ready for release, but some critical issues need to be addressed to ensure a smooth user experience. After fixing the identified bugs, applying the mentioned recommendations and managing the risks, the application should be ready to be delivered to production successfully.
