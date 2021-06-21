# types-of-software-testing

TYPES OF SOFTWARE TESTING
ADHOC TESTING
Adhoc testing is an informal testing type with an aim to break the system. This testing is usually an unplanned activity. It does not follow any test design techniques to create test cases. In fact is does not create test cases. This testing is primarily performed if the knowledge of testers in the system under test is very high. Testers randomly test the application without any test cases or any business requirement document. Main aim of this testing is to find defects by random checking.
Adhoc testing is performed when there is limited time to do elaborative testing. Usually adhoc testing is performed after the formal test execution.

Best practices of Adhoc testing
 Following best pratices can ensure effective Adhoc Testing.
1.	Good business knowledge
Testers should have good knowledge of the business and clear understanding of the requirements- Detailed knowledge of the end to end business process will help find defects easily. Experienced testers find more defects as they are better at error guessing.
2.	Test Key Modules
Key business modules should be identified and targeted for adhoc testing. Business critical modules should be tested first to gain confidence on the quality of the system.
3.	Record Defects
All defects need to be recorded or written in a notepad . Defects must be assigned to developers for fixing. For each valid defect ,corresponding test cases must be written & must be added to planned test cases.
These defect findings should be made as lesson learnt and these should be reflected in our next system while we are planning for test cases.



FUNCTIONAL TESTING
Functional testing verifies that each function of the software application operates in conformance with the requirement specification. This testing mainly involves black box testing and it is not concerned about the source code of the application. Each and every functionality of the system is tested by providing appropriate input, verifying the output and comparing the actual results with the expected results.
The prime objective of Functional testing is   checking the functionalities of the software system. It mainly concentrates on -
Mainline functions:  Testing the main functions of an application
Basic Usability: It involves basic usability testing of the system. It checks whether an user can freely navigate through the screens without any difficulties.
Accessibility:  Checks the accessibility of the system for the user
Error Conditions: Usage of testing techniques to check for error conditions.  It checks whether suitable error messages are displayed.
Types of Functional testing are
•	Smoke Testing
•	Sanity Testing
•	Black Box testing
•	User Acceptance testing
•	Regression Testing

SMOKE TESTING
 
Smoke Testing is performed after software build to ascertain that the critical functionalities of the program is working fine. It is executed "before" any detailed functional or regression tests are executed on the software build. The purpose is to reject a badly broken application, so that the QA team does not waste time installing and testing the software application.

In Smoke Testing, the test cases are chosen that cover the most important functionality or component of the system. The objective is not to perform exhaustive testing, but to verify that the critical functionalities of the system is working fine.
For Example a typical smoke test would be – Verify that the application launches successfully, Check that the GUI is responsive ... etc.
SANITY TESTING

After receiving a software build, with minor changes in code, or functionality, Sanity testing is performed to ascertain that the bugs have been fixed and no further issues are introduced due to these changes. The goal is to determine that the proposed functionality works roughly as expected. If sanity test fails, the build is rejected to save the time and costs involved in a more rigorous testing.

The objective is "not" to verify thoroughly the new functionality, but to determine that the developer has applied some rationality (sanity) while producing the software. For instance, if your scientific calculator gives the result of 2 + 2 =5! Then, there is no point testing the advanced functionalities like sin 30 + cos 50.

REGRESSION TESTING
The purpose of regression testing is to confirm that a recent program or code change has not adversely affected existing features.
Regression testing is nothing but full or partial selection of already executed test cases which are re-executed to ensure existing functionalities work fine.
This testing is done to make sure that new code changes should not have side effects on the existing functionalities. It ensures that old code still works once the new code changes are done.
Regression Testing is required when there is a
•	Change in requirements and modifying the code according to the requirement
•	New feature is added to the software
•	Defect fixing
•	Performance issue fix 
 




PERFORMANCE TESTING
Performance testing is a means of quality assurance (QA). It involves testing software applications to ensure they will perform well under their expected workload.
Features and Functionality supported by a software system is not the only concern. A software application’s performance like its response time do matter. The goal of performance testing is not to find bugs but to eliminate performance bottlenecks
The focus of Performance testing is checking a software program’s
•	Speed – Determines whether the application responds quickly
•	Scalability – Determines maximum user load the software application can handle.
•	Stability – Determines if the application is stable under varying loads
 Types of performance testing
 Load testing – checks the application’s ability to perform under anticipated user loads. The objective is to identify performance bottlenecks before the software application goes live.
Stress testing – involves testing an application under extreme workloads to see how it handles high traffic or data processing .The objective is to identify breaking point of an application.
Volume testing – Under Volume Testing large no. of. Data is populated in database and the overall software system’s behavior is monitored. The objective is to check software application’s performance under varying database volumes.
Common Performance Problems
Long Load time – Load time is normally the initial time it takes an application to start. This should generally be kept to a minimum. While some applications are impossible to make load in under a minute, Load time should be kept under a few seconds if possible. 
Poor response time – Response time is the time it takes from when a user inputs data into the application until the application outputs a response to that input. Generally this should be very quick. Again if a user has to wait too long, they lose interest. 
Poor scalability – A software product suffers from poor scalability when it cannot handle the expected number of users or when it does not accommodate a wide enough range of users. Load testing should be done to be certain the application can handle the anticipated number of users.






