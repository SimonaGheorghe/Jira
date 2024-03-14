# OpenCart
<br> 
Revision History 

| Date	    |Description	          |Author	          |Comments     |
|-----------|-----------------------|-----------------|-------------|
|06.02.2024	|Test plan for OpenCart	|Simona Gheorghe 	| Version 1.0 | 

<br>

## 1. Introdution 
<p>OpenCart, a free open-source e-commerce platform, caters to online merchants by offering a robust and dependable framework for establishing thriving digital stores. This framework is embraced by diverse users, including experienced web developers seeking a user-friendly interface and newcomers venturing into online business for the first time. <br>
OpenCart boasts an array of features that empower you to customize your store extensively, enabling you to unlock its full potential with the aid of its tools.</p>

### 1.1.	Project Objective
Before releasing the project to customers, it's crucial to elevate trust in its quality to the highest level achievable. <br>
Application being tested: https://demo.opencart.com/admin/<br>
Documentation: https://docs.opencart.com/en-gb/administration/

### 1.2.	Functionalities in scope
All features, functionalities, and capabilities outlined in the OpenCart business requirements for the Admin Module will be subject testing across various types, including functional testing, system testing, acceptance testing, component testing, and compatibility testing. <br>
The OpenCart application will be tested on latest versions of Microsoft Edge, Chrome and IE browsers. 

### 1.3 Functionalities and tests out of scope<ul>
<li>Non-functional testing such as stress, performance, security and maintenance falls outside the scope of this project.
<li>No QA support for mobile applications developed. Only web applications will be tested.</li>
<li>Automation testing is beyond scope.</li>
<li>All features that are not under Admin Module.</li> </ul>

<br> 

## 2. Test process
### 2.1. Test planning
### 2.1.1. Roles and responsibilities
|Name                |              Testing Scope                               |
|--------------------|----------------------------------------------------------|
|Simona - QA Junior  | 	will test: User Management, Dashboard, Catalog          |
|QA Senior           |	will test: Design, Sales, Customers, Marketing          |

### 2.1.2. Entry criteria <ul>
<li>Smoke test passed (being the most basic type of test, this is a very important entry criteria in the process of testing);</li>
<li>Testing environment is up and running;</li>
<li>Roles and responsibilities for the project are allocated;</li>
<li>Functional business specifications are defined; </li></ul>

### 2.1.3. Exit criteria<ul>
<li>  100% of tests are executed;</li>
<li>90% of tests are passed;</li>
<li>No Critical defects have Open status;</li>
<li>User Add functionality tests are 100% passed;</li>
<li>Exploratory testing was performed on Admin module; </li></ul>

### 2.1.4. Risks<ul>
<li>Stability risks (crashes, disconnects, etc.);</li>
<li>IE browser might have performance issues;</li>
<li>The web page pagination could be impacted when opened on mobile devices;</li>
<li>Stress conditions might impact the web application;</li>
<li>New browser might not be supported;</li></uL>

### 2.2 Test Analysis  <ul>
<li>Examine the business requirements thoroughly to ensure that all necessary details are gathered for formulating the test conditions; </li>
<li>Write test conditions (What?);</li>
<Li>We intend to complete a full regression test on the current version; </Li></ul>

### 2.3 Test design <ul> 
<li>	All the test cases (How?) are written and reviewed; </li>
<li>	All test cases are generated within Jira, serving as our Test Management Tool; </li>

### 2.4 Test implementation <ul> 
<li> All the test data is available and reviewed (Test data=email examples, password examples, employee, user with admin role);</li>
<li>This test run exclusively focuses on regression testing, wherein we will prioritize tests of the highest importance as our primary objective;</li>
<li>Create the test suites (Cycle Summary) (Grouped by release version or testing type);</li>

### 2.5 Test execution <ul>
<li>The tests will be executed on the latest versions of browsers: Chrome, Microsoft Edge, IE. If time permits, we will expand the testing scope to include other browsers; </li>
<li>Bugs (Defects) will be created based on the failed test cases;</li>
<li>The full regression testing will be done after new application changes; </li>
<li>Retesting will occur following the resolution of any identified bugs; </li> </ul>

### 2.6. Test closure <ul>
<li>At least 90% of tests are passed;</li>
<li>There are no critical issues in an open status; </li> </ul>

### 2.7 Test monitoring and control <ul> 
<li>Status reports will be generated to indicate the current status of the testing process;</li>
<li> If significant issues arise, appropriate control measures will be implemented; </li><br>

## 3.Test deliveries 
### 3.1. Test plan

Link to Test Plan: [link](https://github.com/SimonaGheorghe/Jira/blob/main/Test%20Plan%20-%20OpenCart.docx)

### 3.2. Test conditions 
The test conditions will be created based on the business requirements validated in the test analysis phase and will represent the features to be tested and transformed into test cases.

###  3.3. Test cases
Link to test cases: [link](


