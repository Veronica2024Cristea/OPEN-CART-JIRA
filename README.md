<h1>Testing Project for **OpenCart**</h1>


Application under test: **OpenCart**

Tools used: Jira, Zephyr Squad.

<h2>Functional specifications:</h2>

The below story **(Categories, Products, Orders,Returns,Gift Vouchers,Adding multiple languages,Creating a multi store, Filters, Marketing**) was created in Jira and describes the functional specifications of the "**Catalog,Sales,Admin interface**" module, for which the final project is performed upon.

*https://github.com/Veronica2024Cristea/OPEN-CART-JIRA/blob/main/Screenshot%202024-10-19%20182152.png***

Here you can find the release that was created for this project:

**(https://github.com/Veronica2024Cristea/OPEN-CART-JIRA/blob/main/Raport%20de%20executie%2COPEN%20CART%2C%20Veronica%20Cristea.pdf)**

<h2>Testing process</h2>

The test process was performed based on the standard test process as described below.

<h3>1.1 Test planning</h3>

The Test Plan is designed to describe all details of testing for all the modules from the JPetStore Demo application.

The plan identifies the items to be tested, the features to be tested, the types of testing to be performed, the personnel responsible for testing, the resources and schedule required to complete testing, and the risks associated with the plan. The test plan that was created for this project can be found here **(https://github.com/Veronica2024Cristea/OPEN-CART-JIRA/blob/main/Test_Plan%20OPEN%20CART%20.docx)**

<h4>1.1.1. Roles asigned to the project and persons allocated</h4>

<ul>
  <li>Project manager: Papa Maria</li> 
  <li>Product owner:Razvan Toader</li>
  <li>Software developer:Alex Dan</li>
  <li>QA Engineer:Cristea Veronica</li>
</ul>

<h4> 1.1.2 Entry criteria defined </h4>
<ul>
  <li>Functional business specifications are defined
  <li>Roles and responsabilities have been allocated 
  <li>The test environment is up and running 
  <li>Initial risks were identified 
  <li>The test plan was created and test process is detailed for the functionalities in scope
</ul>    
<h4> 1.1.3 Exit criteria defined </h4>

<li>All the test cases were executed 
<li>90% of test cases are passed 
<li>The remaining defects/bugs have low severity and low priority 
<li>The project deadline was reached 
<li>The project budget was reached 

<h4> 1.1.4 Test scope</h4>

<h5> Tests in scope: </h5>

link pt toate testele https://itfclasses.atlassian.net/jira/software/c/projects/SVC/list?filter=type+%3D+%22Test%22&atlOrigin=eyJpIjoiZTYxMWUyNDNhMmQ5NDQxNGEwNTgzNjBkNzA0OGI4ZjIiLCJwIjoiaiJ9

<h5>Tests not in scope: </h5>

<li>Non-functional testing like performance, stress, volume testing are out of scope
<li>Test process for mobile application is out of scope
<li>Other browsers except Chrome and Mozilla are out of scope
<li>Automation testing is beyond scope 

<h4>1.1.5 Risks detected</h4>

<h5>Project risks:</h5>

<li>The team does not have the proper knowledge and experience for web testing 
<li>Test environment not working 
<li>Short/tight deadlines 
<li>Due to the company changes we might have levers 

<h5> Product risks: </h5>

<li>Taking into account that Admin is  the only module in scope of testing, the rest of them will be at risk of not fulfilling the user needs
<li>Validation constraints on some of the fields might be too restrictive

<h4>1.1.6 Evaluating entry criteria</h4>

The entry criteria defined in the Test Planning phase have been achieved and the test process can continue.

<h3>1.2 Test Monitoring and Control<h3>

In this phase various periodic reports will be generated to reflect the current status of the testing process. In case of major problems, control measures could be taken.
https://github.com/Veronica2024Cristea/OPEN-CART-JIRA/blob/main/Screenshot%202024-10-19%20182152.png

<h3> 1.3 Test Analysis </h3>
The testing process will be executed based on the application requirements. <b>(The requirements analysis has been done in order to implement the <i>early testing</i> test principle and the results can be found here - inserati linkul catre documentul de review. Parte asta specificata intre paranteze o puneti doar daca aveti cerinte si daca ati facut review)</b>. <br><br>

The following test conditions were found: <br>

**( https://itfclasses.atlassian.net/jira/software/c/projects/SVC/list?filter=type+%3D+%22Test%22&atlOrigin=eyJpIjoiZTYxMWUyNDNhMmQ5NDQxNGEwNTgzNjBkNzA0OGI4ZjIiLCJwIjoiaiJ9)**


<h3>1.4 Test Design</h3>

Functional test cases were created in Zephyr Squad based on the analysis of the specifications. The test cases can be accessed here **(https://github.com/Veronica2024Cristea/OPEN-CART-JIRA/blob/main/TESTE%20OPEN%20CART.7z)**

<h3>1.5 Test Implementation</h3>

The following elements are needed to be ready before the test execution phase begins:

<li>Verify if the test environment is up and running 
<li>Access to the test environment is given: valid username and valid password 
<li>Create test suites (Test cycles)
<li>We prioritize the test cases based on risks and business priority 


<h3>1.6. Test Execution </h3>

Test cases are executed on the created test Cycle summary: **(https://github.com/Veronica2024Cristea/OPEN-CART-JIRA/blob/main/Screenshot%202024-10-22%20200834.png)**

Bugs have been created based on the failed tests. The complete bug reports can be found here: **(https://github.com/Veronica2024Cristea/OPEN-CART-JIRA/blob/main/BUGS%20OPEN%20CART.7z)**

The following is a summary of the bugs that have been found
**(https://github.com/Veronica2024Cristea/OPEN-CART-JIRA/blob/main/BUGS%20OPEN%20CART.7z)**

Full regression testing is needed on the impacted areas after the bugs are fixed and retesting will be done for every functionality that was previously failed.

<h3> 1.7 Test Completion</h3>
As the Exit criteria were met and satisfied as mentioned in the appropriate section, this feature is suggested to ‘Go Live’ by the Testing team

The traceability matrix was generated and can be found here: **(inserati aici fie o poza cu matricea de trasabilitate din jira, fie linkul catre fiserul excel exportat din jira cu matricea de trasabilitate. Nu uitati sa faceti filtrare dupa type = story)**

Test execution chart was generated and can be found below. 

**(https://github.com/Veronica2024Cristea/OPEN-CART-JIRA/blob/main/Raport%20de%20executie%2COPEN%20CART%2C%20Veronica%20Cristea.pdf)**

The final report shows that a number 30 tests have failed of a total of 3.

A number of **3** total bugs were found, from which the priority is: 3 are high .
General Testing Conclusion for OpenCart

Tests Created and Executed:
Based on information from the tested documentation, multiple tests were created and executed for the main functionalities of the OpenCart platform, including product management, categories, vouchers, and orders. Most of these tests were successfully executed. Examples of completed tests include:

Adding a new product,
Applying and removing discounts,
Modifying orders.
Ref.: (SVC-65), (SVC-86), (Zephyr Test Steps + Exe…).
Scope Requirements Coverage:
Approximately 80-90% of the initial requirements were covered, particularly in OpenCart's main workflows, such as product catalog management, marketing campaigns, and voucher system.

Untested Functionalities:
Although no specific untested functionalities were reported, some complex features or integration scenarios (e.g., APIs) might need additional testing in the future.

Impact of Bugs on Release:
The identified bugs, though of medium importance, do not block the immediate production release. For example, the issue of multiple uses of a gift voucher requires a prompt fix to prevent financial loss but can be managed post-launch (SVC-65). Other issues, such as creating campaigns without mandatory data, do not have an immediate impact (SVC-86).

Identified Risks:
There are moderate risks to revenue and operations, mainly due to bugs related to vouchers and order management, which require quick post-release fixes (SVC-65), (SVC-86).

Release Recommendations:
The release is recommended with continuous monitoring of functionalities related to vouchers and discounts, along with the urgent implementation of necessary patches. Additional tests are also recommended for complex scenarios or third-party interfaces that were not fully covered.

Lessons Learned:
For future projects, an early focus on testing specific usage scenarios, such as the reuse of promo codes and alternative back-end workflows, could prevent financial losses and operational disruptions. Increasing test automation could help identify issues faster before release.
