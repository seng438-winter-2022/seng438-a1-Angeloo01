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

[1 Introduction	1](#_Toc439194677)

[2 High-level description of the exploratory testing plan	1](#_Toc439194678)

[3 Comparison of exploratory and manual functional testing	1](#_Toc439194679)

[4 Notes and discussion of the peer reviews of defect reports	1](#_Toc439194680)

[5 How the pair testing was managed and team work/effort was
divided	1](#_Toc439194681)

[6 Difficulties encountered, challenges overcome, and lessons
learned	1](#_Toc439194682)

[7 Comments/feedback on the lab and lab document itself	1](#_Toc439194683)

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

Text…

# How the pair testing was managed and team work/effort was divided 

Text…

# Difficulties encountered, challenges overcome, and lessons learned

Text…

# Comments/feedback on the lab and lab document itself

Text…
