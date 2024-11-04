# CS520 Theory of Programming Languages, Fall 2024, KAIST 

This is a webpage of the course "CS520 Theory of Programming Languages", which is offered at the KAIST CS department in the fall of 2024. The webpage will contain links to course-related materials and announcements.

CS520 is an advanced graduate-level course on the theories of programming languages. Its goal is to expose students to rigorous mathematical foundations for programming languages and systems, and mathematical techniques for formally reasoning about  programs written in those languages. The course will largely follow Reynolds's textbook "Theories of Programming Languages", which provides good mathematical treatment of a wide range of programming constructs through axiomatic, denotational, and operational semantics. 

The prerequisite of the course is CS320, the undergraduate-level programming-language course offered at KAIST, or a similar course. The course will be heavy in math, and we expect students to be comfortable with doing and reading rigorous mathematical proofs. 

## 1. Important Announcements

#### [29 October] [Homework2](https://github.com/hongseok-yang/graduatePL24/blob/main/Homework/homework2-questions.pdf) is out.

The second homework assignment is out. Submit your solutions in KLMS by 6:00pm on 8 November 2024 (Friday).

We remind the students that we adopt a very strict policy for handling dishonest behaviours. If a student is found to copy answers from peers or other sources in her or his submission for this homework assignment, he or she will get F.


#### [1 October] [Homework1](https://github.com/hongseok-yang/graduatePL24/blob/main/Homework/homework1-questions.pdf) is out.

The homework assignment 1 is out. Submit your solutions in KLMS by 6:00pm on 18 October 2024 (Friday).

We remind the students that we adopt a very strict policy for handling dishonest behaviours. If a student is found to copy answers from peers or other sources in her or his submission for this homework assignment, he or she will get F.

#### [24 September] No lecture on 1 October.

The first of October is a national holiday. We won't have a class on that day.

#### [27 August] Q&A and use of a LLM.

We strongly recommend students to ask questions in KLMS, instead of in github, if they have any. This would help fellow students to access those questions and corresponding answers more easily. It would also help TAs and the lecturer not to miss those questions.

We do not permit students to ask homework questions directly to ChatGPT, Gemini, or other LLMs. Doing so would be regarded as the violation of the honour code. However, students can use LLMs to get help for their study, for instance, using CoPilot to solve LaTeX typesetting issues and asking ChatGPT to get an overview of a concept or a technique covered in the course or encountered in your group project. If a student or a project group gets help from LLMs for an assignment, such as a project report, the student or the group should do the following two things:

1. In a submission, the student or the project group should explain how and where LLMs are used.
2. LLMs are well-known to give false information. Ensuring correctness is the responsibility of the student or the project group.

#### [August 27] Policy for handling late submissions.

We will adopt the following scheme for handling late submissions for all types of assignments, including homework assignments. The scheme assumes that the total marks are 100.

1. <= One day late (by the midnight of the next day): -10
2. <= Two days late: -20
3. <= Three days late: -30
4. <= Four days late: -40
5. More than four days late: -100.

#### [August 27] Honour code.

We adopt a very strict policy for handling dishonest behaviours. If a student is found to copy answers from peers or other sources in her or his submission for any assignment, he or she will get F.

We also handle the case of plagiarism strictly. Plagiarism means that students copy texts from other sources in their reports. They shouldn't do it. If students have to use texts from other sources, they have to rephrase the texts in their own words and state the source of the texts explicitly. Ideally, students' write-ups should mostly consist of their own phrases and expressions, and use such borrowed and rephrased sentences only when doing so is absolutely needed; if a large part of the report is just a series of rephrases of existing texts, the report won't get good marks. Copying texts from other sources is an instance of plagiarism, and if it happens to an academic, it can destroy his or her research career. If a report of a student or a project group is found to plagiarise, the student or everyone in the group will get F. 

## 2. Logistics

#### Evaluation

* Final exam (40%). Group project (40%). Homework (20%). 

#### Teaching Staffs

* Lecturer: [Prof Hongseok Yang](https://cs.kaist.ac.kr/people/view?idx=552&kind=faculty&menu=160) (email: hongseok00@gmail.com, office hour: 6:00pm - 7:00pm on Monday, office: 3403 in E3-1.)
* TAs: Gyeongwon Jung (email: jgyw0910@kaist.ac.kr) and Sangho Lim (email: lim.sang@kaist.ac.kr), office hour: 4:00pm - 5:00pm on Tuesday, office: 3419 in E3-1.

#### Time and Place

* Time: 14:30 - 16:00 on Tuesday and Thursday.
* Place: 1101 in E3.

## 3. Final Exam

The final exam for this course will happen in our usual classroom on the 19th of December (Thursday) during the final-exam period. Note that the exam starts at 1:00pm.

* Date: 19 December 2024 (Thursday).
* Time: 13:00 - 14:30.
* Place: 1101 in E3.
* Closed-book exam. The scope of the exam is all the topics covered in the classes.

## 4. Group Project

One important part of this course is to form a group of 2-4 students, study an advanced research topic on programming languages with fellow students in the group, and present what the group studied if the group is selected for presentation. Here are the detailed instructions on this group project.

1. Form a group.
  * Deadline - 11:59PM on 26 September 2024 (Thursday).
  * Form a group with 2-4 students.
2. Select a topic and write a proposal (5 marks out of 40 marks).
  * Deadline - 11:59PM on 17 October 2024 (Thursday).
  * Pick a paper or papers on the theories of programming languages that will be studied by your group.
    The paper or papers should be chosen among papers published in POPL'20, POPL'21,
    POPL'22, POPL'23, POPL'24, PLDI'20, PLDI'21, PLDI'22, PLDI'23, and PLDI'24.
  * Submit a 1-page proposal in KLMS that contains the title(s) of the selected paper(s), the reasoning for choosing it or them, and the plan to study the paper in depth.
  * The proposal can be submitted by only one member of each team.
3. Write a report (15 marks out of 40 marks).
  * Deadline - 11:59PM on 21 November 2024 (Thursday).
  * Submit a report with at most 4 pages excluding bibliography and figures in KLMS.
  * The report can be submitted by only one member of each team.
  * The report should explain not just the topic studied by your group but also how the group studied the topic. The latter can be about how the group members studied the topic together, which questions they asked in order to understand the topic in depth, which other papers they studied, which existing implementations or mechanised proofs they looked at if there are any such, and how each member of the group contributed to the study, etc.
  * We encourage the students to go beyond a simple summary of the topic, and to have their own thoughts on the topic in the form of mathematical or experimental analyses. For instance, if the existing results on a chosen topic mostly use the call-by-value setting, the students may try to find out which parts of the results survive in the call-by-name setting.
4. Submit the slides of a presentation on the studied topic (15 marks out of 40 marks).
  * Deadline - 11:59PM on 28 November 2024 (Thursday).
  * Prepare the slides for a 35-minute talk on the studied topic, and submit them in KLMS.
  * The slides can be submitted by only one member of each team.
  * The slides should be in the pdf format.
5. Present your study if your group project is chosen (5 marks out of 40 marks).
  * Four projects will be selected based on the votes by the students, TAs, and the lecturer.
  * Two projects will be presented on 10 December 2024 (Tuesday), and the other two will be presented on 12 December 2024 (Thursday).
6. Warning on plagiarism.
  * Students should not copy texts from other sources in their reports. If students have to use such texts, they have to rephrase the texts in their own words and state the source of the texts explicitly. Ideally, students' write-ups should mostly consist of the students' own phrases and expressions, and use such borrowed and rephrased sentences only when doing so is absolutely needed. Copying texts from other sources is an instance of plagiarism, and if it happens to an academic, it can destroy his or her research career. If any of the reports of a group is found to plagiarise, everyone in the group will get F.

## 5. Homework

Submit your solutions in KLMS. We will create submission folders for all the homework assignments in KLMS.

* [Homework1](https://github.com/hongseok-yang/graduatePL24/blob/main/Homework/homework1-questions.pdf) - Deadline: 6:00pm on 18 October 2024 (Friday).
* [Homework2](https://github.com/hongseok-yang/graduatePL24/blob/main/Homework/homework2-questions.pdf) - Deadline: 6:00pm on 8 November 2024 (Friday).

## 6. Tentative Plan

* 09/03(Tue) - Introduction.
* 09/05(Thu) - Predicate Logic (Ch1).
* 09/10(Tue) - Predicate Logic (Ch1).
* 09/12(Thu) - Predicate Logic (Ch1).
* 09/17(Tue) - __NO LECTURE. Chuseok.__
* 09/19(Thu) - Predicate Logic (Ch1).
* 09/24(Tue) - The Simple Imperative Language (Ch2).
* 09/26(Thu) - The Simple Imperative Language (Ch2).
* 10/01(Tue) - __NO LECTURE. National Foundation Day.__
* 10/03(Thu) - __NO LECTURE. National Foundation Day.__
* 10/08(Tue) - The Simple Imperative Language (Ch2).
* 10/10(Thu) - The Simple Imperative Language (Ch2).
* 10/15(Tue) - Program Specification and Their Proofs (Ch3).
* 10/17(Thu) - Program Specification and Their Proofs (Ch3).
* 10/22(Tue) - __NO LECTURES. Week for Mid-term Exams.__
* 10/24(Thu) - __NO LECTURES. Week for Mid-term Exams.__
* 10/29(Tue) - Failure, Input-Output and Continuation (Ch5).
* 10/31(Thu) - Failure, Input-Output and Continuation (Ch5).
* 11/05(Tue) - Failure, Input-Output and Continuation (Ch5).
* 11/07(Thu) - Transition Semantics (Ch6)
* 11/12(Tue) - Transition Semantics (Ch6) 
* 11/14(Thu) - The Lambda Calculus (Ch10).  
* 11/19(Tue) - The Lambda Calculus (Ch10).
* 11/21(Thu) - The Lambda Calculus (Ch10).
* 11/26(Tue) - The Lambda Calculus (Ch10).
* 11/28(Thu) - __NO LECTURES. Interview for Undergraduate Admission.__
* 12/03(Tue) - An Eager Functional Language (Ch11).
* 12/05(Thu) - An Eager Functional Language (Ch11)
* 12/10(Tue) - Project Presentations.
* 12/12(Thu) - Project Presentations.
* 12/17(Tue) - __NO LECTURES. Week for Final Exams.__
* 12/19(Thu) - __FINAL EXAM (1:00pm - 2:30pm, 1101 E3).__

## 7. Lecture Notes

The lectures will be based on the following hand-written notes, which summarise the contents of the two main textbooks. Reading these notes and solving exercises in the notes is a recommended way to study the topics covered by the course.

* Predicate Logic (Ch1) ([note1](https://github.com/hongseok-yang/graduatePL24/blob/master/Lectures/Lecture2/note1.jpg), [note2](https://github.com/hongseok-yang/graduatePL24/blob/master/Lectures/Lecture2/note2.jpg), [note3](https://github.com/hongseok-yang/graduatePL24/blob/master/Lectures/Lecture2/note3.jpg), [note4](https://github.com/hongseok-yang/graduatePL24/blob/master/Lectures/Lecture2/note4.jpg), [note5](https://github.com/hongseok-yang/graduatePL24/blob/master/Lectures/Lecture2/note5.jpg), [note6](https://github.com/hongseok-yang/graduatePL24/blob/master/Lectures/Lecture2/note6.jpg), [note7](https://github.com/hongseok-yang/graduatePL24/blob/master/Lectures/Lecture2/note7.jpg), [note8](https://github.com/hongseok-yang/graduatePL24/blob/master/Lectures/Lecture2/note8.jpg)).
* The Simple Imperative Language (Ch2) ([note1](https://github.com/hongseok-yang/graduatePL24/blob/master/Lectures/Lecture3/note1.jpg), [note2](https://github.com/hongseok-yang/graduatePL24/blob/master/Lectures/Lecture3/note2.jpg), [note3](https://github.com/hongseok-yang/graduatePL24/blob/master/Lectures/Lecture3/note3.jpg), [note4](https://github.com/hongseok-yang/graduatePL24/blob/master/Lectures/Lecture3/note4.jpg), [note5](https://github.com/hongseok-yang/graduatePL24/blob/master/Lectures/Lecture3/note5.jpg), [note6](https://github.com/hongseok-yang/graduatePL24/blob/master/Lectures/Lecture3/note6.jpg)).
* Program Specification and Their Proofs (Ch3) ([note1](https://github.com/hongseok-yang/graduatePL24/blob/master/Lectures/Lecture4/note1.jpg), [note2](https://github.com/hongseok-yang/graduatePL24/blob/master/Lectures/Lecture4/note2.jpg), [note3](https://github.com/hongseok-yang/graduatePL24/blob/master/Lectures/Lecture4/note3.jpg), [note4](https://github.com/hongseok-yang/graduatePL24/blob/master/Lectures/Lecture4/note4.jpg)).
* Failure, Input-Output, and Continuation (Ch5) ([note1](https://github.com/hongseok-yang/graduatePL24/blob/master/Lectures/Lecture5/note1.jpg), [note2](https://github.com/hongseok-yang/graduatePL24/blob/master/Lectures/Lecture5/note2.jpg), [note3](https://github.com/hongseok-yang/graduatePL24/blob/master/Lectures/Lecture5/note3.jpg), [note4](https://github.com/hongseok-yang/graduatePL24/blob/master/Lectures/Lecture5/note4.jpg), [note5](https://github.com/hongseok-yang/graduatePL24/blob/master/Lectures/Lecture5/note5.jpg), [note6](https://github.com/hongseok-yang/graduatePL24/blob/master/Lectures/Lecture5/note6.jpg), [note7](https://github.com/hongseok-yang/graduatePL24/blob/master/Lectures/Lecture5/note7.jpg)).
* Transition Semantics (Ch6) ([note1](https://github.com/hongseok-yang/graduatePL24/blob/master/Lectures/Lecture6/note1.jpeg), [note2](https://github.com/hongseok-yang/graduatePL24/blob/master/Lectures/Lecture6/note2.jpeg), [note3](https://github.com/hongseok-yang/graduatePL24/blob/master/Lectures/Lecture6/note3.jpeg), [note4](https://github.com/hongseok-yang/graduatePL24/blob/master/Lectures/Lecture6/note4.jpeg), [note5](https://github.com/hongseok-yang/graduatePL24/blob/master/Lectures/Lecture6/note5.jpeg)).
* An Introduction to Category Theory (Tennent Ch8) ([note1](https://github.com/hongseok-yang/graduatePL24/blob/master/Lectures/Lecture7/note1.jpeg), [note2](https://github.com/hongseok-yang/graduatePL24/blob/master/Lectures/Lecture7/note2.jpeg), [note3](https://github.com/hongseok-yang/graduatePL24/blob/master/Lectures/Lecture7/note3.jpeg), [note4](https://github.com/hongseok-yang/graduatePL24/blob/master/Lectures/Lecture7/note4.jpeg), [note5](https://github.com/hongseok-yang/graduatePL24/blob/master/Lectures/Lecture7/note5.jpeg)).
* Recursively-Defined Domains (Tennent Ch10) ([note1](https://github.com/hongseok-yang/graduatePL24/blob/master/Lectures/Lecture8/note1.jpeg), [note2](https://github.com/hongseok-yang/graduatePL24/blob/master/Lectures/Lecture8/note2.jpeg), [note3](https://github.com/hongseok-yang/graduatePL24/blob/master/Lectures/Lecture8/note3.jpeg), [note4](https://github.com/hongseok-yang/graduatePL24/blob/master/Lectures/Lecture8/note4.jpeg), [note5](https://github.com/hongseok-yang/graduatePL24/blob/master/Lectures/Lecture8/note5.jpeg), [note6](https://github.com/hongseok-yang/graduatePL24/blob/master/Lectures/Lecture8/note6.jpeg), [note7](https://github.com/hongseok-yang/graduatePL24/blob/master/Lectures/Lecture8/note7.jpeg), [note8](https://github.com/hongseok-yang/graduatePL24/blob/master/Lectures/Lecture8/note8.jpeg), [note9](https://github.com/hongseok-yang/graduatePL24/blob/master/Lectures/Lecture8/note9.jpeg)).
* The Lambda Calculus (Ch10) ([note1](https://github.com/hongseok-yang/graduatePL24/blob/master/Lectures/Lecture9/note1.jpeg), [note2](https://github.com/hongseok-yang/graduatePL24/blob/master/Lectures/Lecture9/note2.jpeg), [note3](https://github.com/hongseok-yang/graduatePL24/blob/master/Lectures/Lecture9/note3.jpeg), [note4](https://github.com/hongseok-yang/graduatePL24/blob/master/Lectures/Lecture9/note4.jpeg), [note5](https://github.com/hongseok-yang/graduatePL24/blob/master/Lectures/Lecture9/note5.jpeg), [note6](https://github.com/hongseok-yang/graduatePL24/blob/master/Lectures/Lecture9/note6.jpeg), [note7](https://github.com/hongseok-yang/graduatePL24/blob/master/Lectures/Lecture9/note7.jpeg), [note8](https://github.com/hongseok-yang/graduatePL24/blob/master/Lectures/Lecture9/note8.jpeg)).
* An Eager Functional Language (Ch11) ([note1](https://github.com/hongseok-yang/graduatePL24/blob/master/Lectures/Lecture10/note1.jpeg), [note2](https://github.com/hongseok-yang/graduatePL24/blob/master/Lectures/Lecture10/note2.jpeg), [note3](https://github.com/hongseok-yang/graduatePL24/blob/master/Lectures/Lecture10/note3.jpeg), [note4](https://github.com/hongseok-yang/graduatePL24/blob/master/Lectures/Lecture10/note4.jpeg), [note5](https://github.com/hongseok-yang/graduatePL24/blob/master/Lectures/Lecture10/note5.jpeg), [note6](https://github.com/hongseok-yang/graduatePL24/blob/master/Lectures/Lecture10/note6.jpeg), [note7](https://github.com/hongseok-yang/graduatePL24/blob/master/Lectures/Lecture10/note7.jpeg)).
* Continuation in a Functional Language (Ch12) ([note1](https://github.com/hongseok-yang/graduatePL24/blob/master/Lectures/Lecture11/note1.jpeg), [note2](https://github.com/hongseok-yang/graduatePL24/blob/master/Lectures/Lecture11/note2.jpeg), [note3](https://github.com/hongseok-yang/graduatePL24/blob/master/Lectures/Lecture11/note3.jpeg), [note4](https://github.com/hongseok-yang/graduatePL24/blob/master/Lectures/Lecture11/note4.jpeg), [note5](https://github.com/hongseok-yang/graduatePL24/blob/master/Lectures/Lecture11/note5.jpeg), [note6](https://github.com/hongseok-yang/graduatePL24/blob/master/Lectures/Lecture11/note6.jpeg), [note7](https://github.com/hongseok-yang/graduatePL24/blob/master/Lectures/Lecture11/note7.jpeg), [note8](https://github.com/hongseok-yang/graduatePL24/blob/master/Lectures/Lecture11/note8.jpeg), [note9](https://github.com/hongseok-yang/graduatePL24/blob/master/Lectures/Lecture11/note9.jpeg), [note10](https://github.com/hongseok-yang/graduatePL24/blob/master/Lectures/Lecture11/note10.jpeg), [note11](https://github.com/hongseok-yang/graduatePL24/blob/master/Lectures/Lecture11/note11.jpeg), [note12](https://github.com/hongseok-yang/graduatePL24/blob/master/Lectures/Lecture11/note12.jpeg)).

## 8. Study Materials

We will mainly follow Reynolds's book, and we may cover the materials appearing in Chapters 8 and 10 of Tennent's book.

* Main Textbook 1 : [Theories of Programming Languages, John C Reynolds](https://www.cambridge.org/core/books/theories-of-programming-languages/19530A88F3471B2A7D9891770B21DAF9), Cambridge University Press, 1998. 
* Main Textbook 2 : Semantics of Programming Languages, Robert D. Tennent, Prentice Hall, 1991. Chapters 8 and 10 only.

In addition to the two books above, the following books will have further information about the topics covered in the course. In particular, 
Harper's book goes deep into the type systems and operational semantics of a range of programming languages, Gunter's book into the domain theory, and Pierce's book into the type theory.

* Auxiliary Textbook 1 : Practical Foundations for Programming Languages, Second Edition, Robert Harper, Cambridge University Press, 2016.
* Auxiliary Textbook 2 : Semantics of Programming Languages: Structures and Techniques, Carl A. Gunter, MIT Press, 1992.
* Auxiliary Textbook 3 : Types and Programming Languages, Benjamin C. Pierce, MIT Press, 2002.
* Auxiliary Textbook 4 : Formal Semantics of Programming Languages: an Introduction, Glynn Winskel, MIT Press, 1993.

The following classic papers or their recent reprints contain deep insight into some of topics that we study throughout the course.

* John C. Reynolds, [Definitional Interpreters for Higher-Order Programming Languages](https://doi.org/10.1023/A:1010027404223), Higher-Order and Symbolic Computation, 1998. 
* Luis Damas and Robin Milner, [Principal Type-Schemes for Functional Programs](https://dl.acm.org/citation.cfm?id=582176), POPL 1982.

