>   **SENG 438 - Software Testing, Reliability, and Quality**

**Lab. Report \#1 – Introduction to Testing and Defect Tracking**

| Group: Group Number 17     |
|-----------------|
| Qazi Ali              |   
| Shayyan Asim            |   
| Rohan Kapila              |   
| Fayzan Toor             |   


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

1: In this lab we were asked to perform the task of familiarization, exploratory testing, manual scripted testing, and regression testing on an ATM system. This allowed our group to understand and implement the key concepts of software testing. Exploratory testing is often referred to as a dynamic approach. This is done by understanding the requirements of the code and coming up with a brief plan on how you will approach the tests. Exploratory testing is often done in an active approach consisting of testing components of the program on the go. Manual testing on the other hand, consists of a more defined approach. The order of tests are known beforehand and often have one member known as the driver testing cases, while the others note which tests have been completed. In conclusion the difference between exploratory and mandatory testing is the use of a plan. Exploratory is an “on the fly” approach, while manual testing is a predetermined order of tests. 

# High-level description of the exploratory testing plan

2: The primary focus of the exploratory testing plan was to simulate real-world user interactions with ATM, and identify possible usability issues. Test cases for exploratory testing were planned as if a user is about to use an ATM in real life. Test plans included.
    Entering a negative number for the number of 20$ bills
    Entering an incorrect PIN
    Entering an incorrect Card Number
The test cases mentioned above were for checking login authenticity.
    Testing out the Withdrawal functionality with all the different account types.
    Testing out the Deposit functionality with all the different account types.
    Testing out the Transfer functionality with all the different account types.
    Testing out the Balance Inquiry with all the different account types.
The test cases mentioned above were used to check that if the ATM does what its supposed to do, that is testing its overall functionality by entering incorrect information like (Characters, Negative Numbers etc) and checking if an error message shows up when entering incorrect info. Also making sure that if an amount that needs to be withdrawn is correct or an amount that transfer is transferred correctly, and checking that the ATM shows the correct balance that is available


# Comparison of exploratory and manual functional testing

3: The benefits of exploratory testing compared to manual functional testing is the ability to determine bugs along the way. For instance, if one bug is found it can open doors to a whole different set of potential bugs that may be related. Manual functional testing does not consider this due to a set order of tests. This can be seen during the provided test suite, as many bugs were found based on the fact that an incorrect amount was being deposited during the exploratory testing phase. The tradeoff between exploratory and manual testing also becomes present with respect to efficiency. Exploratory testing may result in some basic functional errors being overlooked, while manual scripting tests allow the tester to cover all basic functionalities. There are tradeoffs between the two approaches. For instance, Exploratory testing allows users to gain a better understanding of the system and examine aspects further that may have related errors, however some basic functionalities can mistakenly be avoided. Manual testing on the other hand, does not allow testers to dive into relative bugs, however ensures all aspects are covered through a well developed plan. Based on the comparison, exploratory testing can be defined as more adaptable, flexible, and dynamic, while manual testing is more structured, predictable, and scripted.

# Notes and discussion of the peer reviews of defect reports

4: The testing was divided into 2 groups. 1 Group tested the Withdrawal and Deposit functionality. 2nd Group was responsible for Transfers and Balance Inquiry. The login authenticity tests were done together. The primary goal of dividing the group was to ensure that each group mastered the functionality that they were assigned to since the ATM had a lot of options. After getting to know the system more through tests were conducted with multiple inputs and were first reported on a google doc where everyone was collaborating. Afterwards 2 groups reviewed each other’s work and started to report the bugs found on Azure.

# How the pair testing was managed and team work/effort was divided

5: We decided to divide the pair testing with regard to the different actions a user can take. One group's responsibilities were to test the deposit and withdrawal functionalities and all dependent components. The other group was responsible for testing balance inquiry and transfer and all dependent components. Furthermore we divided the CSV component and the lab report. 

# Difficulties encountered, challenges overcome, and lessons learned

6: Difficulties encountered were making the test cases during the exploratory testing part. Since it was the first time we were doing something like this, coming up with different ideas on how to proceed with the testing was a bit difficult. But then all of us first agreed that before starting the testing we should first get comfortable with the ATM and see how it works and do effective communication with each other if something is not clear. When everyone was comfortable with the system we started to design the test cases and divided the testing into 2 groups to ensure that each group focused especially on the component they were assigned to test to get the maximum benefit. Lessons learned were that rushing the testing part can cause huge problems especially when working in the industry so taking things slow and learning about the system that is being tested is essential.

# Comments/feedback on the lab and lab document itself

7: Overall, the lab was a good introduction into the aspects of testing. It gave us a starting point to apply the concepts we learned in class in an interactive and comprehensive way. We had to come up with our own methods of testing for the first part of exploratory testing, but got to follow instructions for the scripted and regression test which felt like a good balance between following instructions and having to use our knowledge. A possible criticism for the lab would be the way the instructions were formatted. They were not very user friendly and difficult to read through in one sitting.
