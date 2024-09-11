---
layout: page
title: CSCI 3358-- Foundations of algorithmic (un)fairness
description: Fall 2024 at Boston College
importance: 1
---

<h3> Instructor: Jessie Finocchiaro </h3>
<p> Tuesday, Thursdays 9a-10:15a, 245 Beacon St Room 125A </p>
<p> <a href="mailto:jessie.finocchiaro@bc.edu"> Email</a>: {first name}.{last name}@bc.edu </p>
<p> Office hours: W 3-4, H 10:30-12 </p>

<p> <a href ="https://calendar.google.com/calendar/u/2?cid=Y19lYzc3MjU2Yjc5ZGFkOTJkMDAwMDI0ZDUyYTcyM2NlYzdlMDY3MWU0NTUzNWI0ZjU5ZmMzZjRiOTU3YTQwMjE5QGdyb3VwLmNhbGVuZGFyLmdvb2dsZS5jb20">Class Calendar (office hours, due date reminders, etc.)</a> Must be logged in to BC account. </p>

<h2> This is a draft of the course plan. Schedule and grading schemes are subject to change </h2>

<p>  </p>

<h3> Course description </h3>
<p> Computation is being increasingly used to support decision-making in our society: algorithmic predictions of repayment likelihood are given to banks to help them determine whether or not they should give someone a loan; in the COVID-19 pandemic, algorithms were used to allocate initially scarce vaccines; facial recognition algorithms allow us to use our faces as "keys" to unlock our phones and even houses. In these high-stakes settings, concerns of fairness and justice are salient. This course will equip students with the mathematical tools to understand and address some of these concerns. Topics will include: how to computationally define and diagnose (un)fairness, the role of uncertainty in fairness, disparate treatment vs disparate impact, and contextualization within US anti-discrimination law.  </p>

__Prerequisites__: CS1, comfort with probability (Randomness and Computation) required.

<h3> Course learning goals </h3>
By the end of this course, I hope you are able to... 
* Identify bias in datasets and algorithms;
* Explain __how__ bias is present, and what algorithmic solutions can supplement non-algorithmic solutions;
* Translate mathematical concepts about parity and fairness into their real-world applications, and be able to explain and acknowledge the shortcomings of algorithmic solutions;
* Communicate these finding to both technical and non-technical audiences.



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
Due dates will generally be at 5:00pm. If your submission is uploaded by the time I go to download everyone’s submissions, that is okay. Sometimes I might download submissions right away, but I might not always. This allows some flexibility so that submissions at 5:05pm are less stressful, but waiting on the order of a day enters the danger zone.

If you are not going to be able to closely make a given deadline, please feel welcome to email me and ask for an extension. I will grant two days of extension throughout the semester (for any assignment besides the case study), but in extenuating circumstances, will do my best to be more flexible.

The exception to this is the case study. Because this is an in-class presentation for a slated day, the deadline is firm. If an emergency arises, please notify me as soon as possible.


<<<<<<< HEAD
| Mode of participation | Portion of grade | Examples |
| :--- | :---: | :---:|
| Participation | 15 | Notes, CS Experience, Not being on your laptop/phone/airpods during class |
|Case Study presentation | 15 | A 30-minute presentation leading class discussion on a topic covered in class.
| Homework | 30 | Variety of coding and theoretical assignments |
| Final Project| 40 | Includes project proposal, final presentation, project writeup |
=======
The first week of class, the students collectively agreed to proceed with a standards-based grading approach, as outlined [here](https://www.jessiefin.com/assets/pdf/csci_3358_SBG_proposal.pdf).
>>>>>>> f94c60f (Re-add everything to git repo)


<h4> Participation </h4>
I want to make sure our class is a place where you are able to share your experiences and that your classmates have the opportunity to learn from you. In the era of large language models, I unfortunately have to make this as LLM-proof as possible. A classroom where discussion is lively is one that is the most fun and the most learning happens. If you buy in, others will too, and it will be a better experience for everyone.

<h5> Notes </h5>
Tuesday class structure will tend to be more of a lecture-style format, where Thursdays will dive into a case study going deeper into what we learned on Tuesday. Before we dive into case studies, I will spend the first 30 minutes of Thursday's class going into more depth and answering questions that you still have after Tuesday's lecture.

To better understand what you gleaned from class on Tuesday, I am going to ask you upload your notes on Tuesday's lecture by Wednesday at noon. Since lectures will involve a decent amount of math, which is not easy to type in real time, I encourage you to take handwritten notes. Your upload of these notes can simply be a picture of your handwritten notes.


<h5> CS Experience </h5>

Computer Science is so much more than programming, and in this course, we are exploring one way CS interweaves with human experience. I ask that you attain 3 "CS Experiences", which can take place in one of the following ways, but cannot repeat an experience more than twice:
* Attend a CS research seminar (and send me a pic of you at the seminar + a paragraph summarizing what you took away from it)
* Write a ~500 word biography of a computer scientist. If you don't know who to write a biography of, let me know, and I'll give you some recommendations related to what you're interested in.
* Attend a department social event
* Go to a CS-related club (BCCSS, WICS, ...)
* Visit the [career center](https://www.bc.edu/bc-web/offices/student-affairs/sites/careers/about/make-an-appointment.html) for a resume review or apply for a job!

Each experience is with 2% of your final grade, and falls under participation.

<h3> Case study presentation </h3>

Thursdays in this class will generally be dedicated to digging in deeper to the topic presented on Tuesday. It will be your responsibility to present a case study (approximately 30 minutes) in groups of 2-3. I will provide some references to get you started on the topic, but it is up to you to go deeper and explain the connection to the class material. Feel free to get creative! 


<h4> Homework </h4>

Five homework assignments will be given throughout the semester. The assignments will be long, but material will be progressively covered as the due date draws nearer. Your life will be easier if you don't procrastinate.

* __Homework 1 due__: Sept 4 (overview of probability, prereqs)

* __Homework 2 due__: Sept 20 (group fairness via parity)

* __Homework 3 due__: October 4 (calibration and individual fairness)

* __Homework 4 due__: November 1 (utilitarianism, welfare, and social choice)

* __Homework 5 due__: November 15 (fairness in resource allocation and fair division)


<h4> Final project </h4>

[Project description](https://www.jessiefin.com/assets/pdf/csci_3358_finalproject.pdf)

Throughout the course, you will be working on a larger-scale class project in groups of 2-3 on a topic of your choosing. There are so many important and fascinating challenges that we simply won't have time to cover in class. This project is your opportunity to get some hands-on experience with something that piques your interest. Because this project is a large portion of your grade, it shouldn't be all done between Thanksgiving and finals. To this end, we will have some regular check ins.

The [AI Incident Database](https://incidentdatabase.ai) might be a great place to find inspiration for your project if you need ideas.

__Sept 13__: Project proposal due. (I will do my best to have feedback and suggested literature to you by Sept 20)

__Sept 27__: Update 1 due. At this point, you should understand what the challenges are that you're going to face and how you plan to overcome them. 

__Oct 11__: Update 2 due. At this point, you should have access to data that you will need for your project, if necessary. If applicable, experiments should be planned.

__Nov 8__: Update 3 due. You should have some preliminary results, at the very least. 

I would recommend the work for the project is done before the Thanksgiving holiday so you can relax and enjoy some time off, and only have to work on your final presentation after the break.


__Dec 12ish__: During final exam period, project presentations. At the beginning of the exam period, technical reports due as well.


<h3> Required texts and materials </h3>

No textbooks are required for this course, though the following will be helpful resources:
* <a href="www.fairmlbook.org"> Fairness and Machine Learning, Limitations and Opportunities</a> by Barocas, Hardt, and Narayanan
* <a href="https://procaccia.info/wp-content/uploads/2020/03/comsoc.pdf">Handbook of Computational Social Choice</a> edited by Brandt, Conitzer, Endriss, Lang, and Procaccia

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


