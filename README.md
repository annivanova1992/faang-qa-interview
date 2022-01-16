# FAANG QAE Interview preparation materials

## Introduction

This repository was created for collecting information about the interviews for QAE/SDET/Test Automation positions. Don't hesistate to create a pull request for adding new materials.

## References

- Main document for FAANG preparation: [faang-interview](https://github.com/faang-interview/faang-interview.github.io). There you can find info about coding interviews, job offer negotiation, behavioral interviews and so on.

## Amazon

**Interview Process**

Looks like that interview process varies, but seemingly most common flow has the following structure

- Round 1
  - LP questions
  - Coding question: 1 [LC](https://leetcode.com/) easy/medium problem
  - Test data and test cases for problem from previous point
  - Questions to the interviewer
- Round 2
  - Testing theory or Coding question: 1 [LC](https://leetcode.com/) easy/medium problem
  - 4 LP questions
  - Questions for the interviewer
- Round 3
  - Troubleshooting
  - Questions for the interviewer
- Round 4
  - LP questions or Coding question: 1 [LC](https://leetcode.com/) easy/medium problem
  - Questions for the interviewer
- Round 5
  - LP questions
  - Coding question: 1 [LC](https://leetcode.com/) easy/medium problem
  - Test data and test cases for problem from previous point
  - Questions for the interviewer

## Apple

**Interview Process**

Interview questions depend on team.

- Phone screening, Leet code easy, Behavioural questions, QA Basics, Work Experience
- Phone screening, Test task, Behavioural questions, QA Basics, Work Experience

## Meta (SDET position)

**Interview Process**

- Round 0: Call with a hiring manager
  - No coding questions
  - Sys design question: How would you design a test infrastructure for a end to end testing of a product? No white boarding, just talking through the high level overview.
  - Questions to the interviewer

If the call went well you're invited to the next round.

- Round 1: System design interview (45 min)
  - How would you design a test infrastructure for a end to end testing of a product?
  - More detailed overview of a system design than for the first round
  - Drawing a system diagram
  - Detailed design of a system
  - Questions to the interviewer
- Round 2: Technical interview (45 min)
  - 2 medium level LeetCode questions
  - Tests for the problem from previous point
  - Questions to the interviewer
- Round 3: Problem troubleshooting (45 min)
  - Troubleshoot the given problem using
    - Logs from a production environment
    - Code snippets
    - Problem description from an alert
  - Detect if the alert is a bug or a false positive
  - Define potential code/system fixes
  - Questions to the interviewer
- Round 5: Behavior interview (45 min)
  - Standard behavior interview questions

## Netflix (SDET Position)

**Interview Process**

- Round 0: Call with a hiring manager
  - No coding questions
  - General questions about your experience and why you want to join the team
  - Questions to the interviewer

If the call went well you're invited to the next round. Netflix practices interviewing with potential team members, so you get to see your future colleagues. Plan specific questions.

- Round 1: Hiring Manager Interview (more behavioral questions then technical questions)
  - Detailed questions about your experience and why you want to join the team
  - Expectations from the hiring manager
  - Questions to the interviewer
- Round 2: Technical Interview
  - Job specific coding question, I got one to write input function for an onscreen keyboard
  - Test data and test cases for problem from previous point
  - Questions to the interviewer
- Round 3: Technical Interview
  - Technical experience questions about tools and frameworks I've used in the past and how were they chosen and used
  - Specific examples for my experience
  - Questions to the interviewer

If you passed the technical interview (no detailed feedback, more yay/nay count from 3 rounds), you're invited to the next round. There is a possibility that next two rounds will be on the other day and not scheduled initially due to the fact you might fail the first round. Netflix does behavioral interviews with director level folks, so all questions would be very open ended and high level.

- Round 4: Behavior Interview
  - Standard behavior interview questions about my experience with team members
  - Detailed questions about communication patterns and how you would handle a defect
  - Questions to the interviewer
- Round 5: Behavior Interview
  - Standard behavior interview questions about my experience with team members
  - Detailed questions about what excites me in my job and how do I see myself in 5 years
  - Questions to the interviewer



**Behavior questions**

- How will you handle a defect found on the day before a major public release where Jeff Bezos is going to demostrate to public. How will you fix this ?
- How to handle a hot fix? Do you take ownership in debugging issue or deligate the task to developers?
- How will you handle the stress at work, more work less time?
- Have you taken any initiative or leadership task in the past, if so what?
- Any challenges with team member as well as technical challenge? How did u handle?
- How wil you handle defect found during hot fix which needs immediate fix?
- How will you test devices like bluetooth keyboard?

**Coding questions**

For QAE: Easy level leetcode questions including math operations, strings, arrays, loops, hashmap, etc
For SDET: Easy/medium level leetcode questions including math operations, strings, arrays, loops, hashmap, tree, sorting, linked list etc
- How to design simple HashMap ([HashMap Implementation for Java](https://medium.com/swlh/hashmap-implementation-for-java-90a5f58d4a5b)) [LC reference](https://leetcode.com/problems/design-hashmap/)
- What is difference List and LinkedList?
- Questions regarding trees,linked list , Bst ,Heap were asked
- Write program for bubblesort and how to identify a palindrome?
- Find all palindromic substrings of a given string
-- Find all palindromic substrings of a given string (Input : abba Output: bb, abba)
- Given sides of a triangle write a function which could say it is equilateral , isosceles or scalene. Give Test data for the solution you give
- Write a program to find Max Depth of a BST. Give test data for the same.
- Write a function that solves [insert CS101 problem here] and calculate the complexity.
- trees, graphs and optimising algorithms
- Simple programs related to number reversal without using Array
- Finding the pairs forming a particular sum from a given array
- Write a function to reverse a linked List
- Implement a linked List
- Design and Implement a music player that has the songs and band Names stored internally in this class using appropriate data structure . with the methods to play a song and find the top played song. The songs themselves are write once, read rest of the song's lifetime. So, I would not change the way the song is stored...a sequentially written file. The directory that maintains the list of songs could and will be randomly accessed. So, this directory data structure needs to support random directory reads. In addition, it seems that a consecutive play should not repeat a song i.e. this calls for sequential directory reads. One good data structure that supports both efficient random reads (lg n) and supports sequential reads is a btree. Other structures like a skip list provides both random and sequential access with its own trade offs.


**How to test questions**
- How would you test Youtube?
- If you have a service that sends SMS to given phone numbers. How would you test if SMS actually got delivered or not
- how I will test and troubleshoot the online web applications


**Other common questions**
- How to reach Inbox in Gmail in Eclipse?
- Questions about subnet masks ,routers,TCP/UDP.etc"
- Testing frameworks, strategy
- How many time does hour and minute hand overlap
- What type of tools do you use testing? What types of environments do you use for testing?

**
**References** with interview details for QAE

- Amazon QA Engineer Interview Questions https://www.interviewkickstart.com/interview-questions/amazon-qa-engineer-interview-questions
- Has anyone taken the Amazon QA Engineer code test? https://www.reddit.com/r/QualityAssurance/comments/gfnw8e/has_anyone_taken_the_amazon_qa_engineer_code_test/
- How to Prepare for Amazon Quality Assurance Engineer Interview https://www.techbeamers.com/amazon-quality-assurance-engineer-interview-guide/
- How to be Successful in Amazon QAE Interview https://www.linkedin.com/pulse/how-successful-amazon-qae-interview-chandrasekhar-muttineni-cham-/
- Amazon Interview Experience | Set 420 (For QAE) https://www.geeksforgeeks.org/amazon-interview-experience-set-420-qae/
- Amazon | Quality Assurance Engineer (QAE) | Intern/FTE | India | Bangalore, Chennai https://leetcode.com/discuss/interview-question/1450892/Amazon-or-Quality-Assurance-Engineer-(QAE)-or-InternFTE-or-India-or-Bangalore-Chennai
- Amazon QAE II - Bay Area - OFFERED!! https://leetcode.com/discuss/interview-experience/1521822/Amazon-QAE-II-Bay-Area-OFFERED!!
