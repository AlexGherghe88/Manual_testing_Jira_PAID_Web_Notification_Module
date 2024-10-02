<h1>Testing Project for PAID Online Claims Notification Module.</h1>

The scope of the final project for ITF Manual Testing Course is to use all gained knowledge throught the course and apply them in practice, using a live application

Application under test: **PAID Online Claims Notification Module**

Tools used: Jira, Zephyr Squad.

<h2>Functional specifications:</h2>

The below stories were created in Jira and describes the functional specifications of the **PAID Online Claims Notification Module**, for which the final project is performed upon.

![Gas 2](https://github.com/user-attachments/assets/ad5a7332-4c2d-44f4-8d41-e5b9ed8946e0)

![Gas 3](https://github.com/user-attachments/assets/0ecb9f4d-9158-498c-8638-f3377e88a3a9)

![Gas 4](https://github.com/user-attachments/assets/cf2089dd-166a-4e08-ac89-8f259f6186fc)

Here you can find the release that was created for this project:

![Release](https://github.com/user-attachments/assets/e7dbe729-5604-48ba-96bc-e9e076138eeb)

<h2>Testing process</h2>

The test process was performed based on the standard test process as described below.

<h3>1.1 Test planning</h3>

The Test Plan is designed to describe all details of testing for **PAID Online Claims Notification Module**

The plan identifies the items to be tested, the features to be tested, the types of testing to be performed, the personnel responsible for testing, the resources and schedule required to complete testing, and the risks associated with the plan. The test plan that was created for this project can be found here:
[Test plan](https://github.com/AlexGherghe88/Manual_testing_Jira_PAID_Web_Notification_Module/blob/main/Test%20Plan%20-%20ST6_Gherghe%20Alexandru.pdf)

<h3>1.1.1. Roles asigned to the project and persons allocated</h3>

<ul>
  <li>Project manager: Popescu Ioana</li> 
  <li>Product owner: Dinu Cosmin</li>
  <li>Software developer: Barbu Stefania</li>
  <li>QA Engineer: Gherghe Alexandru</li>
</ul>

<h3> 1.1.2 Entry criteria defined </h3>

<ul>
  <li>We should have test environment available and be able to be accessed by all testing members</li> 
  <li>We should have business requirements defined </li> 
  <li>We should have the roles and responsibilities set and allocated</li> 
  <li>We should have the Test Plan described</li> 
  <li>Potential project risks are defined, analyzed and a mitigation plan is set</li> 
</ul>

<h3> 1.1.3 Exit criteria defined </h3>

<ul>
  <li>We should have all test cases executed</li> 
  <li>We should have all major bugs closed</li> 
  <li>All discovered defects were reported</li> 
  <li>All business requirements were covered by test cases</li> 
  <li>Potential products risks have been identified and a mitigation plan is set</li> 
</ul>

<h3> 1.1.4 Test scope</h3>

<ul>
  <li> Increasing the quality of the web application</li>
  <li> Identifying bugs and reporting them to the developing team</li>
  <li> Verifying that the web application is working as per the request of the client</li>
  <li> Identifying  and mitigating the product risks</li>
</ul>

<h4> Tests in scope: </h4>

For the current testing team, the functionalities that are in scope of testing are:
<ul>
 <li> Welcome screen from the PAID Online Claims Notification module (cap. 2.1 - from the business requirements)</li>
 <li> PAD Policy Validation screen, (cap. 2.2 - from the business requirements) </li>
 <li> Damage Details screen (cap. 2.3 - from the business requirements)</li>
</ul> 
Throughout the testing process the testing team will perform functional testing, positive testing, negative testing, black-box testing and GUI testing.


<h4>Tests not in scope: </h4>
<ul>
<li>All the other functionality of the web application except the ones mentioned above are out of scope.</li>
<li>Non-functional testing is out of scope.</li>
<li>Automation testing is out of scope.</li>
</ul> 

<h3>1.1.5 Risks detected</h3>

<h4>Project risks:</h4>

<ul>
<li> The risk of missing a large number of defects given that the tester assigned to the project has limited experience in testing web applications;</li>
<li> Difficulties in the production launch of the web application, considering that it will be implemented on the client's web page that is developed by another company, a collaboration on its part being necessary;</li>
<li> The risk that the business requirements are frequently changed, the client not having a clear vision of how the web application works.</li>
</ul>

<h4> Product risks: </h4>
<ul>
<li>The web application presents the user with summary information about the data they must provide in the process (lack of info buttons detailing the data to be provided).</li>
<li>Situations have been identified where if the user enters data that the application cannot process, it displays a generic error message from which the user does not understand what the problem is. The business requirements have no data on the error messages that should be displayed for these situations.</li>
<li>The risk of inappropriate behavior in terms of the performance of the application, as it is not tested from a non-functional point of view.</li>
</ul>

<h3>1.1.6 Evaluating entry criteria</h3>

The entry criteria defined in the Test Planning phase have been achieved and the test process can continue.

<h3>1.2 Test Monitoring and Control</h3>

<p>During the testing periodchecks were made periodically to ensure that the testing activity is performed according to the planed schedule</p>
<p>Also reports ware generated and sent to management to inform about quality level of the application.<br>
You can see bellow the report for the Daily Test Execution Progress for this project. </p>

![image](https://github.com/user-attachments/assets/78ea4259-b693-491b-bb6f-ac81b9fb1cbf)

<h3> 1.3 Test Analysis </h3>
<ul>
  <li>In this phase we analyzed the business requirements to make sure we understand them, that there are no mistakes, ambiguities, inconsistencies or contradictions.</li>
  <li>We also made suggestions for improvement on the business requirements for the decision of the customer
  <li>Based on the business requirements, test conditions were created.</li>
</ul>

<p>The following test conditions were found:</p>

![image](https://github.com/user-attachments/assets/90cae9e2-e5dd-4388-a0c5-28cc543f4fa8)
![image](https://github.com/user-attachments/assets/81bf5997-2b1f-4201-a2e7-00d8dafbd425)


<h3>1.4 Test Design</h3>

Functional test cases were created in Zephyr Squad based on the analysis of the specifications. The test cases can be accessed [here.](https://github.com/AlexGherghe88/Manual_testing_Jira_PAID_Web_Notification_Module/blob/main/Test%20cases%20-%20PAID%20Online%20Damage%20Notification%20Module.csv) 

<h3>1.5 Test Implementation</h3>

The following steps are performed before the test execution phase can begin:
<ul>
  <li>The test environment is validated through smoke testing</li>
  <li>We also make sure that test environment is updated with the latest changes</li>
  <li>The test data identified in the previous step is created</li>
  <li>We prioritize test cases written in the previous phase (based on business importance and risks)</li>
</ul>

<h3>1.6. Test Execution </h3>

Test cases are executed on the created test Cycle summary: 
![image](https://github.com/user-attachments/assets/d8a86af0-40c9-4c6b-a0f2-3da4ec35b057)

<p>Following the execution of the 16 test cases created defects were identified in the functionality of the web application for 8 test cases.</p>

The following is a summary of the bugs that have been found and reported to the development team:

![image](https://github.com/user-attachments/assets/efeca908-e08e-460b-b6d3-71bce9d5b0d5)

Full regression testing is needed on the impacted areas after the bugs are fixed and retesting will be done for every functionality that was previously failed.

<h3> 1.7 Test Completion</h3>
As the Exit criteria were met and satisfied as mentioned in the appropriate section, this feature is suggested to ‘Go Live’ by the Testing team.

The traceability matrix was generated and can be found here:

![image](https://github.com/user-attachments/assets/c0eac9b1-6e1e-4187-942e-706622e6b30d)


Test execution chart was generated and can be found below. 

![image](https://github.com/user-attachments/assets/2a7988be-3efe-4ca4-8b9f-fd03bf8ec5a4)


The final report shows that a number **8** tests have failed of a total of **16**.

A number of **10** total bugs were found.

<p>The identified bugs do not block the user from using the web application, but affect their experience with the application, the links in the application are not set to redirect the user to the appropriate web pages and the displayed error messages are generic ones that do not explain to the user where he went wrong and what can do to fix the error.</p>

<p>At the same time, there are fields where the user must enter data where the info buttons are missing to provide the user with more details about the data he must provide, and thus his experience with the application can be difficult.</p>

<p>We recommend completing the business requirements with individually defined error messages for each type of error resulting from the use of the application and filling the fields with info buttons that give additional details to the user in relation to the data they must provide in the notification process of the claim within the PAID Online Claims Notice web application.</p>

