---
layout: page
title: CSCI 2244-- Randomness and Computation
description: Spring 2025 at Boston College
importance: 2
---

<h3> Instructor: Jessie Finocchiaro </h3>
<p> Tuesday, Thursdays 10:30-11:45a, 245 Beacon St Room 229 </p>
<p> <a href="mailto:jessie.finocchiaro@bc.edu"> Email</a>: {first name}.{last name}@bc.edu </p>
<p> Office hours: TBD </p>

<p> <a href ="https://calendar.google.com/calendar/u/2?cid=Y19lYzc3MjU2Yjc5ZGFkOTJkMDAwMDI0ZDUyYTcyM2NlYzdlMDY3MWU0NTUzNWI0ZjU5ZmMzZjRiOTU3YTQwMjE5QGdyb3VwLmNhbGVuZGFyLmdvb2dsZS5jb20">Class Calendar (office hours, due date reminders, etc.)</a> Must be logged in to BC account. </p>

<h2> This is a draft of the course plan. Some details sucject to change. </h2>

<p>  </p>

<h3> Course description </h3>
<p> CSCI 2244 provides an introduction to fundamental concepts and tools that enable advanced work in modeling and computation involving randomness. The focus is on discrete probability. Topics include probability spaces, random variables, conditional probability, limit theorems, and Markov chains. Selected topics in linear algebra are discussed in connection with the analysis of covariance. Randomness in the sense of algorithmic succinctness (e.g., Kolmogorov complexity) is mentioned in passing, but is not discussed at length. Computational illustrations in Python are given throughout the course.  </p>

__Prerequisites__: The official prerequisites for CSCI 2244 are Computer Science I (CSCI 1101), calculus (MATH 1102/1103 or equivalent), and either CSCI 2243 Logic & Computation or MATH 2216 Introduction to Abstract Mathematics. In particular, students entering CSCI 2244 should be comfortable with fundamental programming techniques, differential and integral calculus with functions of one real variable, boolean algebra of sets, recursion and induction, and basic mathematical reasoning. Writing short programs in Python will be required in some of the problem sets. Please install Python 3.9 or higher, if you don't already have it.

If your CS1 course did not use Python as the programming language, don't panic. Python is easy to learn, and you won't need all of its features right away. See https://docs.python.org/tutorial/ to get started.

<h3> Course learning goals </h3>




<h3> Tentative schedule </h3>

| Date | Topic                                               | Case Study topic                                  | Text reference                                           | Assignments/Activities                       |
|:------|:---------------------------------------------------|:-------------------------------------------------:|:---------------------------------------------------------|:----------------------------------|
| 8/27    | Introduction             |                                                   |   [BHN Ch 1](https://fairmlbook.org/pdf/fairmlbook.pdf)  |                                   |
| 8/29    | Prediction problems                                    |                                                   |   [BHN Ch 7](https://fairmlbook.org/pdf/fairmlbook.pdf)  |                                   |
|  9/3   | Audits and Case study                                 | [Gender Shades](https://gendershades.org)         |                                                          |   HW 1 on probability due Sept 4  |
|  9/5   | Prediction problems                               |                                                   |                                                          |                                   |
| 9/10   | Quantitative definitions of group fairness        |                                                   |   [BHN Ch 3](https://fairmlbook.org/pdf/fairmlbook.pdf)  |                                   |
| 9/12   | Incompatibility of fairness metrics               |                                                   | [KMR 2016](https://arxiv.org/abs/1609.05807)                                |  Project prposal due September 13 |
| 9/17   | Calibration                                       |                                                   |  [BHN Ch 4](https://fairmlbook.org/pdf/fairmlbook.pdf)   |                                   |
| 9/19   | Incompatibility case study                        | [COMPAS](https://www.propublica.org/article/how-we-analyzed-the-compas-recidivism-algorithm) |                 | HW 2 due Sept 20        |
| 9/24   | Quant defs case study                             | [Lending discrimination](https://www.cnn.com/2023/12/14/business/navy-federal-credit-union-black-applicants-invs/index.html) and [Fair Lending](https://www.hud.gov/program_offices/fair_housing_equal_opp/fair_lending#_Examples_of_Lending)                                                        |                                                          |                                   |
| 9/26   | Individual fairness                               |                                                   |                                                          | Project update 1 due Sept 27      |
| 10/1   | Feedback loops                                    |                                                   | [Runaway feedback loops in predictive policing](https://arxiv.org/abs/1706.09847) |          |
| 10/3   | Calibration Case study                            | [Early Warning Systems](https://jcperdomo.org/pdfs/difficult_lessons.pdf) |                                  |                                   |
| 10/8   | Individual Fairness case study                    |  [Algorithmic hiring](https://www.ml.cmu.edu/news/news-archive/2016-2020/2018/october/amazon-scraps-secret-artificial-intelligence-recruiting-engine-that-showed-biases-against-women.html)            |                                                          |                                   |
| 10/10  | Feedback loops case study                         | [Predictive policing](https://incidentdatabase.ai/cite/54/#r1525) |                                          | HW 3 due Oct 11                   |
| 10/15  | Fall break  |                                     |                                                   | Enjoy the holiday!                                       |                                   |
| 10/17  | Intro to welfare/resource allocation              |                                                   |  [HCSC Ch 11](https://www.cse.unsw.edu.au/~haziz/comsoc.pdf) |                               |
| 10/22  | Scarce resource allocation                        |                                                   |                                                          |                                   |   
| 10/24  | Intro to social choice                            |                                                   |                                                          |    Project update 2 due Oct 25    |
| 10/29  | Scarce resource allocation case study             | [Pooled COVID testing](https://arxiv.org/abs/2206.10660) |                                                   |                                   |
| 10/31  |  Social choice case study                         | [Citizens assemblies](https://www.parliament.uk/get-involved/committees/climate-assembly-uk/about-citizens-assemblies/) |   | HW 4 due Nov 1     |
| 11/5   | Fair division                                     |                                                   | [HCSC Ch 13](https://www.cse.unsw.edu.au/~haziz/comsoc.pdf) |                                |
| 11/7 | Fairness notions in resource allocation             |                                                   |  [HCSC Ch 2, 6](https://www.cse.unsw.edu.au/~haziz/comsoc.pdf)   | Project update 3 due Nov 8|
| 11/12 | Fair division case study                           | [Rent division](https://sigecom.org/exchanges/volume_13/2/GOLDMAN.pdf) | [HCSC Ch 13](https://www.cse.unsw.edu.au/~haziz/comsoc.pdf) |           |
| 11/14 | Fairness notions in social choice case study       | Participatory budgeting                           |                                                          | HW 5 due Nov 15                   |
| 11/19 |  Privacy                                           |                                                   |                                                          | Work on your final project!      |
| 11/21 |  US Anti-discrimination law                        |                                                   |   [BHN Ch 6](https://fairmlbook.org/pdf/fairmlbook.pdf)  | Work on your final project!      |
| 11/26 |  Privacy case study                               | [Facial and gender recognition](https://cmci.colorado.edu/idlab/assets/bibliography/pdf/Scheuerman2020-cscw-databaseidentity.pdf) |   | Work on your final project!      |
| 12/3 |  US Anti-discrimination case study 1                | [Discrimination in housing ads](https://www.justice.gov/opa/pr/justice-department-secures-groundbreaking-settlement-agreement-meta-platforms-formerly-known#:~:text=The%20Department%20of%20Justice%20announced,Fair%20Housing%20Act%20(FHA).)                                                       |                                                          | Work on your final project  |
| 12/3 |  US Anti-discrimination case study 2                | [Ban the box](https://www.dropbox.com/scl/fi/7fbm7n16jkshdnvp74lr2/BTBworking.pdf?rlkey=46a87tm6mqilfwzl36ck09hmy&e=2&dl=0)                                                                                                                 |                                                          | Work on your final project  |
| 12/12 | Final project presentation                         |                                                   |                                                          | Final project presentations   |



<h3> Grading and late policies </h3>
Grades will be composed of 3 aspects: problem sets, in-class exams, and participation. The assignments and exams will be synced across sections.


<h4> Homework </h4>
Problem sets will be due on Canvas most Fridays (check each problem set on Canvas for possible exceptions). _You must submit at least six problem sets that demonstrate a serious attempt at completion in order to be eligible for a passing grade in the course._ Each problem set will be posted approximately one week before the due date.

Late submissions will receive no credit except in very unusual circumstances (at the discretion of the instructor). However, I will drop your lowest homework grade (such as a zero from a missed assignment) no questions asked. The average score on the problem sets will contribute 10% of your course grade. 

Your work on the problem sets will be crucial in developing a mastery of the material. Think twice before deciding to skip a problem set or not do it fully, as this will likely negatively impact your performance on exams.


<h4> In-class exams </h4>
Three exams will be given before the end of classes (see the schedule for dates). The exams will cover material from class, from the problem sets, and from the book. You may use your own cheat sheet (single-sided sheet of letter-sized paper of your own notes) during exams. No sharing of materials or information is allowed. The average of each student's exam scores will contribute 80% of their course grade.
Brief quizzes may also be given during some class periods, possibly without prior notice. The overall quiz score will count as 10% of the course grade.

There will be no make-up exams or quizzes. In order to allow for unexpected events, I will drop each student's lowest quiz score.

<h4> Participation </h4>
Showing up to class and without engaging does not count as participating. This class is hard for a lot of folks, but engaging with the material and putting in hard work might help round your grade up from, for example, a B to B+, or A- to A. However, I won't round a B+ to A- based on participation. Moreover, engaging with the material is the best way to actually learn it (what we're all here for!)

In lieu of a hard participation grade, I ask that you write a one-to-two sentence summary of the class by noon the following day, and ask any questions about concepts you didn't fully understand. We will spend the first few minutes of the following class recapping and answering these questions.



<h3> Required texts and materials </h3>

No textbooks are required to purchase for this course, though the following will be helpful resources:
* Prof Alvarez's textbook for the course (on Canvas)
* [Grinstead and Snell's Intro to Probability](https://math.dartmouth.edu/~prob/prob/prob.pdf)
* [Mitzenmacher and Upfal's Probability and Computing](https://www.cs.purdue.edu/homes/spa/courses/pg17/mu-book.pdf)


<h3> Communication expectations </h3>
I will do my best to be generally responsive, while still protecting my personal boundaries. In general, the best way to contact me is by <a href="mailto:finocch@bc.edu">email</a>.

I will do my best to respond to emails within 24 hours (excluding weekends, which might delay responses), and I expect you to do the same. When grading, I will do my best to have grades uploaded to the portal within a week, but will let the class know if this isn't attainable.

In writing your emails, please write in complete sentences and take the time to give more context on your problem than you think I need. It will help me get a better idea of your understanding and thinking, and I can provide better feedback with this in mind.

<h3> Accommodations and accessibility </h3>

Your experience in this class is important to me. If you have already established accommodations with <a href="https://www.bc.edu/content/bc-web/academics/sites/connors-family-learning-center/services/ADHD-Learning-Disability-Support-Services.html"> Connors Family Learning Center (learning disabilities and ADHD) </a> and/or <a href = "https://www.bc.edu/content/bc-web/offices/student-affairs/sites/dean-of-students/disability-services.html">Disability Services </a> (all other disabilities), please communicate your approved accommodations to me at your earliest convenience so we can discuss your needs in this course.

If you have or suspect you have a disability but have not yet established services through the Connors Family Learning Center or Disability Services, you can see the relevant website for information about the registration process. 

Each office provides resources and coordinates reasonable accommodations for students. Reasonable accommodations are established through an interactive process between you, your instructor, and the relevant office.  It is the policy and practice of Boston College to create inclusive and accessible learning environments consistent with federal and state law.

<h3> Class recording policy </h3>

Boston College seeks to protect the integrity of what transpires in the classroom among students and professor, any course materials prepared by the professor, and the privacy of students and faculty. With this in mind, you are prohibited from recording (audio or video) any lectures, seminars, or other classroom activities without the express permission of the instructor. Authorized recordings (including any made in order to accommodate ADA considerations) and all other course materials (including any materials posted on Canvas) may only be used for the purposes of an individual’s (or group’s) study in the course, and may not be shared with any wider audience on or off campus unless the instructor has explicitly given such permission.

This class or portions of this class will be recorded by the instructor for educational purposes. These recordings will be shared only with students enrolled in the course and will be deleted at the end of the end of the course.

If you ask, I will probably give permission. However, I don't want to be recorded without my knowledge. That already happens enough in the rest of our lives.


<h3> Religious accommodation </h3>

Both Massachusetts law  and my humanity beg that I make reasonable accommodations to help students avoid negative academic consequences when their religious obligations conflict with academic requirements. I commit to making every reasonable effort to allow students to observe their religious holidays without jeopardizing your success in this course, and I will not ask you to choose between religious observance and academic work, though you will have to make up any work missed during your absence. Please let me know as early as possible if you notice any conflicts between requirements for this course and your religious observances, so that we can agree to a solution.

<h3> Inclusion and incident reporting </h3>
In a class about fairness and discrimination, the topics of discussion that emerge may be very personal to you, or to your classmates. I expect you to be respectful of everyone in the learning environment (including myself) who share their experiences and to not minimize or dismiss someone's emotions or experience. We are all here to learn from each other. 

Professional courtesy and sensitivity are especially important with respect to individuals and topics dealing with differences of race, culture, religion, politics, sexual orientation, gender, gender variance, and nationalities. Class rosters are provided to the instructor with the student’s legal name. I will gladly honor your request to address you by an alternate name or gender pronoun. Please advise me of your name and pronouns early in the semester so that I may make appropriate changes to my records.
You can also [update your name and pronouns in Canvas](https://cteresources.bc.edu/documentation/canvas-guide-for-students/setting-pronouns-and-changing-your-display-name/) at any time. You can also review the [Name Change resource](https://www.bc.edu/content/bc-web/offices/student-services/registrar/name-change.html#tab-update_your_legal_name_with_the_university) from the Office of Student Services for more information about how you can update your name in various campus systems. If you are an LGBTQ+ student looking for additional support as you prepare to discuss your name or pronouns on campus, you are encouraged to [contact Ira Kirschner](mailto:kirschni@bc.edu), Associate Director, [Thea Bowman AHANA and Intercultural Center](https://www.bc.edu/content/bc-web/offices/student-affairs/sites/ahana/about.html).

In order to advance Boston College’s goal of creating a community in which everyone is treated with respect, dignity, and compassion and where acts of prejudice, hatred, and discrimination are not tolerated, the university created the <a href = "https://cm.maxient.com/reportingform.php?BostonCollege&layout_id=1">bias-related incident reporting form</a>. This form allows targets and witnesses to hate crimes or bias-related incidents to easily report the behavior and get connected to networks of care. In subsequent conversations with the Dean of Students Office, students can also get a better handle on the available institutional processes for addressing harm. You can learn more about the process at the <a href="https://www.bc.edu/content/bc-web/offices/student-affairs/sites/dean-of-students/about/bias-protocol.html#tab-introduction">Hate Crimes & Bias-Related Incidents Protocol website</a>.

<h3>Classroom technology policy</h3>

A note on cell phones, texting, and checking one’s email during class: Research has shown us that even having our cell phones on the table in front of us diminishes our ability to learn well; further, taking notes via computer diminishes one’s ability to process information. Checking texts, emails, and messages is also unprofessional and disrespectful to our class community. Please turn off your phone, email, and computer during class; I will do so as well. I appreciate your cooperation with this important aspect of creating a class of which we all want to be a part. If there is a one-time exception (e.g., waiting on news for a family event), please let me know and I will generally be okay with making an exception. 

On generative AI: Think of GenAI models like an electric bike. While they have their place and can help cyclists with active recovery, no one will become an elite road cyclist by solely riding an e-bike. In the same way, a LLM doing your homework for you will not help you become a better computer scientist. (Analogy courtesy of Bo Waggoner.)


