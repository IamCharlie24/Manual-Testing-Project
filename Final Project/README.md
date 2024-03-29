# Proiect-Practic-Testare-Manuala
The scope of the final project for ITF Manual Testing Course is to use all gained knowledge throught the course and aplly them in practice, using a live application

Application under test: [JPetStore](https://petstore.octoperf.com/actions/Catalog.action)




Tools used: JIRA, Zephyr Squad

# **Functional specifications**
____

**The below stories were made in JIRA and describes the functional specifications of the "Account System" and "Product" module , for which the final project is performed upon.**

![story v1](https://github.com/IamCharlie24/Manual-Testing-Project/assets/133395092/d486d208-c74c-44a7-9e52-68314ed02816)




# **1 Testing section**

**1.1 Test Planning**

The Test Plan is designed to describe all details of testing for the "Account System" and "Product" module from the ***JPetStore***.

The plan identifies the items to be tested, the features to be tested, the types of testing to be performed, the personnel responsible for testing, the resources and schedule required to complete testing, and the risks associated with the plan

**1.1.1 Roles assigned to the project and persons allocated**

- Project manager - Andrei Laurentiu
- Product owner - Mark Smith
- Software developer - Mihai Ion
- QA Engineer - Andrei Grigore

**1.1.2 Entry criteria defined**

- Project risks to be identified and mitigated.

- Test plan to be created.

- Entry requirements to be met

- Roles to be assigned.

**1.1.3 Exit criteria defined**

 - 90% of tests are passed.

 - No Critical issues have Open status.
 
 - Update tests are 100% passed (update tests will not generate other new issues that impact the application).
 
 - The testing should cover all the functionalities, features identified in the test plan.
 
 - The website meets the expected performace standards.
 
 - The website meets the expected security standards, including secure payment processing, user data privacy, and protection against hacking and cyber attacks.
 
 - All required documentation, including test plans, test cases, and test results, has been completed and reviewed.


**1.1.4 Test scope**

  **Tests in scope:**
  
  
-	To design a user-friendly interface that allows customers to browse and search for products easily.
-	To provide customers with a user account system that allows them to track their orders and cancel them if its needed and manage their information.
-	To implement a shopping cart and checkout process that is secure and easy to use.
-	To provide photos for each product so the customers know what they are gonna buy.
-	To add a variety of pets so you can have from where to choose.
-	Compatible with all most used browsers.
-	From the many reviews we got on social media we understand that the customers want a performant website, and we create one with fast loading time,fast responsive design and efficient navigation.

  **Tests not in scope:**

-	Non-functional testing like stress, performance is beyond scope of this project.
-	No QA support for mobile applications developed. Only web applications will be tested.
-	Automation testing is beyond scope.


**1.1.5 Risks detected:**
 - Projects risks: 
 
  - Technology Dependencies: Dependencies on third-party technologies, frameworks, or APIs may introduce risks related to compatibility issues, version conflicts, or lack of support, which can hinder the development process.
  - Inadequate Testing: Insufficient time or resources allocated for testing activities may result in inadequate test coverage, leading to undetected defects and potential quality issues in the final product.
  - Communication Breakdown: Poor communication and collaboration among team members, stakeholders, or external vendors can result in misunderstandings, delays, and rework.
  - Budget Constraints: Insufficient budget allocation for the project may limit access to necessary resources, tools, or technologies, impacting the overall quality or timely completion of the website.

 
 - Poduct risks:

- IE browser might have performance issues.
- Versions of IE older than Version 112.0.1722.68 have security vulnerabilities (cross-site scripting( user data can be stolen after injecting malicious code in  the website), exploits on buying system).
- The web page pagination could be impacted when opened on mobile devices with different versions of systems or rooted.
 	stability risks (crashes, disconnects, etc).
- Data breaches, payment frauds and regulatory compliance issues may appear after launching the website to the customers. 
- Stability risks (crashes, disconnects, etc).


**1.1.6 Evaluating entry criteria**

The entry criteria defined in the Test Planning phase have been achieved and the test process can continue.




**1.2 Test Monitoring and Control**

It will be done by generating periodic reports that reflect the current status of the test.

![Screenshot 2023-11-14 200117](https://github.com/IamCharlie24/Manual-Testing-Project/assets/133395092/c52188c5-cebf-4b37-9b97-efc53becde84)

**1.3 Test Analysis**

The testing process will be executed based on the above requirements for the ***Account System***. The following test conditions were found:

-Verify if a user can login in with a valid username and incorrect password.

-Verify if the user can successfully receive an Email Verification after resetting password.

-Verify if a user can login without filing the username and passwords fields.

-Verify Successful Security Question Verification for Account Recovery.

-Verify if a user can login with an incorrect CAPTCHA verification.

-Verify Invalid Email Adress for Account Recovery.

-Verify Incorrect Security Question Answers for Account Recovery.

-Verify if a user can login with a successful CAPTCHA verification.

-Verify if a user can login after reloading/refreshing the CAPTCHA.

-Verify if a user can login in with a incorrect username and valid password.

**1.4 Test Design**

Functional test cases were created in Zephyr Squad. Based on the analysis of the specifications, the test design techniques used for generating test cases are: 

![test](https://github.com/IamCharlie24/Manual-Testing-Project/assets/133395092/2f0c5e31-70ca-43a4-ab6c-614b2261a396)




The test cases with steps can be viewed here: [test_cases.pdf](https://github.com/IamCharlie24/Manual-Testing-Project/blob/main/Final%20Project/Test_Cases_JPetStore.csv)

**1.5 Test Implementation**

The following elements are needed to be ready before the test execution phase begins:

+Testing environment is up and running: https://jpetstore.aspectran.com/catalog/

+Access to the testing environment is given: Username : j2ee | Password : j2ee

+Cycle summary was created.

+Test cases were added to the cycle summary.
 
**1.6 Test Execution**

 - Test cases are executed on the created test Cycle summary(or Test Run): [cycle_summary_execution.pdf](https://github.com/IamCharlie24/Manual-Testing-Project/blob/main/Final%20Project/Cycle_Summary_report..pdf)
 - Bugs have been created based on the failed tests. The complete bug reports can be found here: [created_bugs.pdf](https://github.com/IamCharlie24/Manual-Testing-Project/blob/main/Final%20Project/Bug_report.pdf)

* The user can use "Easy Registration" method with a invalid username and a valid password.

* The user can use "Easy Registration" method with a invalid username and a valid password.

* Unable to Edit Profile Picture in "Account Management"

* The prices of products are displayed incorrectly.

* The prices of products are wrongly calculated when products are loaded on the platform

**1.7 Test Completion**
 - Exit criteria was evaluated and passed.
 - The traceability matrix was generated and can be found here: [Traceability_matrix.csv](https://github.com/IamCharlie24/Manual-Testing-Project/blob/main/Final%20Project/Traceability_Matrix_JPetStore.xlsx)
 - Test execution chart was generated, the final report shows that a number of 5 tests fail of a total of 23.
 - A number of 23 test cases were planned for execution and all of them were executed.
 - A number of 5 total bugs were found, from which the priority is: 1 highest, 1 high and 3 medium

![Picture1](https://github.com/IamCharlie24/Manual-Testing-Project/assets/133395092/15ba93be-a6ec-43ae-bd9d-37f9b1ac2f4b)





