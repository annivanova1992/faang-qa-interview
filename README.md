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

## Questions (which were asked on interview)

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
- Write a function to reverse a linked List [206. Reverse Linked List](https://leetcode.com/problems/reverse-linked-list/)
- Implement a linked List
- Design and Implement a music player that has the songs and band Names stored internally in this class using appropriate data structure . with the methods to play a song and find the top played song. The songs themselves are write once, read rest of the song's lifetime. So, I would not change the way the song is stored...a sequentially written file. The directory that maintains the list of songs could and will be randomly accessed. So, this directory data structure needs to support random directory reads. In addition, it seems that a consecutive play should not repeat a song i.e. this calls for sequential directory reads. One good data structure that supports both efficient random reads (lg n) and supports sequential reads is a btree. Other structures like a skip list provides both random and sequential access with its own trade offs.
- to find the sum of all nodes in a binary tree which was divided vertically 
Find from a list of numbers where each number is repeating even number of times except one. Find that number
Write a function to find a substring in a string. Test your code, write the test cases.
- Convert a sorted binary array of int to balanced BST.
- Implement an insert method for a sorted circular linked list
- Merging of two sorted arrays [88. Merge Sorted Array](https://leetcode.com/problems/merge-sorted-array/)
- Parenthesis matching [20. Valid Parentheses](https://leetcode.com/problems/valid-parentheses/)
- Sort the digits of a number in efficient manner
- Given a linked list with N nodes, Reverse the list in a group of 'k' nodes
- Convert a binary tree into a doubly linked list
- delete elements which had value equal to given value in a doubly linked circular list
- In a tree node, there is an extra pointer called random. Point random of each node to the next node in that level, NULL if it is the right most node.
- Given a tree, make the left and right pointers such that it acts as a doubly linked list in spiral level order.
- Given a number of closing and opening brackets, produce the number of sets of brackets that have been closed/opened.
- Given a string and a letter, How many times does the letter appear. Followed by how would you test it. 
- Print the list of numbers in an array fall beyond the average of the total numbers of the same array. And generate the test cases assuming it is a black box. (Intention here is to generate the exhaustive test cases)
- Rotate a string in clockwise direction [796. Rotate String](https://leetcode.com/problems/rotate-string/)
- Given an array of integers and k, print all the pairs of numbers (a,b), both of them inside the array, such that a+b=k [1. Two Sum](https://leetcode.com/problems/two-sum/) [167. Two Sum II - Input Array Is Sorted](https://leetcode.com/problems/two-sum-ii-input-array-is-sorted/)
- there are a bunch of distinctive numbers with only one pair of duplicates. find the odd ones
- Write code to reverse a linked list from its mid point. So 1->2->3->4->5->6->7 becomes 1->2->3->7->6->5->4 
- Given two texts, x and y, where x < y, check if all the characters of x are in y.
- Given a string, find the longest repeating substring. [1062. Longest Repeating Substring](https://leetcode.com/problems/longest-repeating-substring/)
- Write a function that takes two lists of strings and return a list of Strings with all of the intersections of the strings ex: List1 = {"a","a","a", "b", "d"} List2 = {"a", "a", "c", "d"} expectedReturn={"a","a","d"} Also he asked what tests cases I would use to validate the function also he wanted to know the run time analysis of the function
- Question 1: Setup: Assume primitive Facebook. FB has Members. class Member { String name; String email; List<Member> friends; } Question A: Code printSocialGraph(Member m). Direct friends of m are Level 1 friends. Friends of friends are level 2 friends.....and so on Print level 1 friends first. Then print level 2 friends....and so on Enumerate test cases to verify the implementation is correct.
- Write a function that converts an int into its alpha-numeric equivalent represented as a null terminated string. The function should accept an int as input and return a string as output. For instance, calling the function with an int value of 324 would return a null terminated string containing "324". Ensure that your function checks for appropriate boundary conditions and edge cases. Assume you cannot use any standard libraries (for example, no itoa or sprintf). Write out test cases to verify your code is working correctly.
- Let's say we're developing a vector graphics application. It will allow the user to create lines, rectangles, circles, text, etc. and manipulate them independently - move them, re-size them, etc. Design an object model for this application.
- array where indexes correspond to the tree node number of a parent node, and values correspond to current tree node number., root having number -1 Write code to recreate a tree (binary tree, bnon-BST)
- Given an array of numbers including negative, print the highest sum of the continuous sequence you can find.
- Find the second largest element in an array of integers.
- Using an already implemented method Rand5() that generates a random integer between the ranges 1-5 uniformly. Using this method, implement a a new method that returns a random integer in the range 1-7 uniformly, i.e. Rand7(). Basically this is Rejection Sampling Algorithm. See http://leetcode.com/2010/11/rejection-sampling.html
- Finding out if a linkedlist has a loop or not. [141. Linked List Cycle](https://leetcode.com/problems/linked-list-cycle/) 
- Mergin two sorted linkedlists.
- Implement a reverse hash table
- Given a binary tree. Find if there exists a path from root to leaf which sums up to a given number.
- Given a BST with following property find the LCA of two given nodes. Property : All children has information about their parents but the parents do not have information about their children nodes. Constraint - no additional space can be used
- Find top 100 maximum number from a continuous input stream.
- Given your family tree, find all the you cousins in the tree, given your position.
- Given a number, find out how many times each digit is repeated in it.
- Given a number, sum its digits till the sum becomes a single digit. eg. 12345-15-6. Optimize it to O(n) complexity.
- Given two roman numbers, sum them and print the sum in roman. eg. X+IV=XIV
- sudoku solver [37. Sudoku Solver](https://leetcode.com/problems/sudoku-solver/)
- How would you model a deck of cards? Write a reshuffling function for the deck of cards.
- Write a function which takes two strings as parameters and returns a string of common characters between the two strings but no duplicates. Use hash table to implement the algorithm.
- Write a code to swap left and right node of a tree.

**How to test questions**
- How would you test Youtube?
- If you have a service that sends SMS to given phone numbers. How would you test if SMS actually got delivered or not
- how I will test and troubleshoot the online web applications
- You are given an app on a mobile device which can take pictures of different objects, how would you go about testing this - What test cases would you create. Write code to create an automation test script which would go to a website, click into some different links, store all references to a certain word and output these.
- How would you test a subway system?
- How would you test Gmail app?
- How do you test the functionality of weather.com which takes a coordinates anywhere on earth and gives you accurate current weather information. After I given my plan which is to use automation tool collecting weather information from public weather station and compare results. I was asked what if there's no web service, no phone service, not even radio and you can't load weather forecast information from the public weather stations. Nor you can use historical value to test since the results need to be very accurate.
- There were also testing questions, of "how would you test" kind, say how would you test a high availability system with backend on the cloud
- list test cases for phone alarm system.
- How do you check a Sudoku game to make sure all the rules have been respected?

**Other common questions**
- How to reach Inbox in Gmail in Eclipse?
- Questions about subnet masks ,routers,TCP/UDP.etc"
- Testing frameworks, strategy
- How many time does hour and minute hand overlap
- What type of tools do you use testing? What types of environments do you use for testing?
- Design and code An API takes following parameters as input and inserts them into a relational database table. Of these parameters, few of them are mandatory fields. How would you implement your API?TestcaseId, TestCaseName, TestCase Description, TestCaseExecutionId, TestCaseExecutionStatus, TestSteps, TestLabels, IsActive, IsAutomated, TestPriority TestcaseId, TestCaseExecutionId and TestCaseExecutionStatus are mandatory fields. How do you handle this?
- what are private/public/package, who can access variable and methods given one of these?
- What is a hashtable, how would you implement one?
- Binary trees/AVL trees, what can you tell me about them.
- Equivalence Class Testing Pair Wise Combinatorial Testing Failure Mode Analysis
- difference between hashtable and hashmap, etc. 
- Detailed performance test questions: load, stress, etc tests.
- How to troubleshoot when you fail to sign in your online chat/messenger program.
- how would you get to the 1st chapter of an ebook through ur code.
- explain the steps that happen after a url is entered on the address bar of a browser and enter is pressed.
- Given that you are working for amazon, you want to know the response time of amazon web page for each customer or user who opens it. By response time i mean the moment the user enters the website url and presses enter and till the web page opens, time interval between pressing enter and received web page. How will you calculate the time interval for each user or customer ?
- As a test engineer, what would you want built into the design of an LRU cache to help you test it.
- Debug a chat program from user point of view when it is failing to sign in the user means user is entering user name and password but it is not signing him in.
- What is the time required to search a tree , what is the advantage of AVL tree over ordinary tree? How would you merge 2 sorted arrays?
- What is difference List and LinkedList?

**
**References** with interview details for QAE

- Amazon QA Engineer Interview Questions https://www.interviewkickstart.com/interview-questions/amazon-qa-engineer-interview-questions
- Has anyone taken the Amazon QA Engineer code test? https://www.reddit.com/r/QualityAssurance/comments/gfnw8e/has_anyone_taken_the_amazon_qa_engineer_code_test/
- How to Prepare for Amazon Quality Assurance Engineer Interview https://www.techbeamers.com/amazon-quality-assurance-engineer-interview-guide/
- How to be Successful in Amazon QAE Interview https://www.linkedin.com/pulse/how-successful-amazon-qae-interview-chandrasekhar-muttineni-cham-/
- Amazon Interview Experience | Set 420 (For QAE) https://www.geeksforgeeks.org/amazon-interview-experience-set-420-qae/
- Amazon | Quality Assurance Engineer (QAE) | Intern/FTE | India | Bangalore, Chennai https://leetcode.com/discuss/interview-question/1450892/Amazon-or-Quality-Assurance-Engineer-(QAE)-or-InternFTE-or-India-or-Bangalore-Chennai
- Amazon QAE II - Bay Area - OFFERED!! https://leetcode.com/discuss/interview-experience/1521822/Amazon-QAE-II-Bay-Area-OFFERED!!
