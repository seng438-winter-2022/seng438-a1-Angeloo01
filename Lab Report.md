>   **SENG 438 - Software Testing, Reliability, and Quality**

**Lab. Report \#1 – Introduction to Testing and Defect Tracking**

| Group \#:       |   |
|-----------------|---|
| Student Names:  |  Angelo Gonzales |
|                 |  Dave Sharma |
|                 |  Jaron Baldazo |
|                 |  Manjot Singh |

**Table of Contents**

(When you finish writing, update the following list using right click, then
“Update Field”)

[1 Introduction	1](#Introduction)

[2 High-level description of the exploratory testing plan	1](#high-level-description-of-the-exploratory-testing-plan)

[3 Comparison of exploratory and manual functional testing	1](#comparison-of-exploratory-and-manual-functional-testing)

[4 Notes and discussion of the peer reviews of defect reports	1](#Notes_and_discussion_of_the_peer_reviews_of_defect_reports)

[5 How the pair testing was managed and team work/effort was
divided	1](#How_the_pair_testing_was_managed_and_team_work/effort_was_divided)

[6 Difficulties encountered, challenges overcome, and lessons
learned	1](#Difficulties_encountered,_challenges_overcome,_and_lessons_learned)

[7 Comments/feedback on the lab and lab document itself	1](#Comments/feedback_on_the_lab_and_lab_document_itself)

# Introduction

This purpose of this lab is to introduce us to the concepts of software testing. The objectives of this lab includes hands-on experience in testing, the differences between exploratory testing, manual scripted testing, and regression testing, and using tools to track defects and common practices.

What we knew about exploratory testing includes that in exploratory testing, tests are designed and executed together at the same time. Exploratory testing is done with no strict plan, however, the testing is done with some plan or goal in mind. For example, the testing can be focused on specific simple functionalities to easily localize faults or it can be focused on a large set of functionalities to test the system as a whole. Additionaly, exploratory testing uses a human tester to create realistic scenarios for the system that will cause it to fail or succeed. The tester varies the system input in order to find faults with the system.

Manual functional testing or manual scripted testing varies from exploratory testing such that the former is heavily scripted and planned. In scripted testing, tests are first designed and recorded, then they are executed at a later time. This allows tests to be run by different testers. Scripted testing strictly follows the path that was designed prior to the execution of the tests. No deviation from the planned tests recorded in the script.

Exploratory testing enables choice and increases the net of different scenarios that are tested, while scripted testing limits the scenarios that are tested and it's possible to miss a fault every time. However, exploratory testing is less scalable, trackable, and repeatable than scripted testing

# High-level description of the exploratory testing plan

Our goal for the exploratory test is to test all the high level requirements as stated in Appendix B. These include:
-   Start or stop the machine.
-   Enter ATM card and Personal Identifcation Number (PIN)
-   Withdrawal, limited to multiples of $20
-   Deposit
-   Transfer
-   Balance Inquiry
-   Invalid PIN and 3 invalid attempts.
-   failed transactions
-   Proper printed receipt
-   Proper logging of transactions

In addition to these tests, we plan to enter invalid inputs when it queries the user. For example, a negative or large number for ATM card number. Finally, we will check to see if the system's behaviour and output matches that expected behaviour and output as stated in Appendix B.

# Comparison of exploratory and manual functional testing

We found almost similar defects during the exploratory and manual functional testing. Unique defects found while exploratory testing were misspelled user prompts. Unique testing defects found while manual functional testing were re-entry of pin was considered incorrect and incorrect behaviour during transfer between accounts. 

Manual functional testing is preffered as it is heavily planned thus, it is more repeatable, scalable and easier to document. Additionaly, Manual functional testing allowed for an easier regression testing because it allowed us to repeat procedures that were already documented and planned. Exploratory is also planned, but it offers more freedom to the tester. This freedom allowed us to find defects that would have not been discovered with MFT alone. However, this freedom makes it more difficult to document the testing procedures thus, the process is less repeatable and scalable especially if functionalities are added to the system.

# Notes and discussion of the peer reviews of defect reports

For the exploratory testing, each pair of group members looked at the bug defect report via searching issues in the backlog bug reporting system. The groups looked at each others’ bugs, while trying to reproduce the steps to ensure that they were able to achieve the same end goal. The searching was done by looking at first the priority level for the search, either High Priority or Low Priority given in the categories. Some of the notes that were taken while reviewing the defects report was that some bugs were not necessarily as important as others such as a misspelling of a word like “wood” which was demoted to a lower priority compared to a logical problem such as printing money for any option clicked (Bug ATM1-4). In addition, some notes pointed out by one of the groups was that a bug such as a large integer fail (Bug ATM1-1) was not necessarily due to an in-system bug, however due to not being able to properly display an error message, it was kept as a bug. For the manual-scripting and manual regression for version 1.0, Tests 6 and 14 were the same as some of the exploratory tests that were already caught. For version 1.1 Tests 13, 14, and 34 were the same as some of the exploratory tests that were already caught. 

# How the pair testing was managed and team work/effort was divided 

During pair testing pair work was split equally, with 1 member utilizing the app and sharing their screen, while the other member noted and defects and fixes to the backlog. This way both members of the pair were able to witness proper execution of the program, and are able to discuss specific bugs that were found. Also since pair testing was done on exploratory tests, dividing work this way made it easier to determine a way to find defects between the two members. Once these tests were finished we combined our results with the other pair in the group, seeing that we both had very similar bugs to be found due to using the same method of pair testing.

# Difficulties encountered, challenges overcome, and lessons learned

Text…

# Comments/feedback on the lab and lab document itself

Text…
