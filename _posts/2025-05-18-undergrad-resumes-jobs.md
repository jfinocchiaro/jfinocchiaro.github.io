---
layout: post
title: 'Finding a Computer Science/Data Science job (for undergrads)'
date: 2025-05-18
description: Some thoughts on formatting a CV, finding internships, and possible job titles
tags: 
categories: academic
featured: true
related_posts: true
---

If you're reading this, you're (probably) a BC student of mine, presumably studying Computer Science or Data Science. 
While Jesuit education principles are focused on developing the whole person, I also want to acknowledge that the whole person can't develop until you're psychologically safe and confident. 
I've found (personally and in talking to students my first year) that one of the biggest detriments to this is confidence in being able to find a job. 
So, cool, here we are. I'm giving (more) unsolicited advice, based on a mix of personal experience, different blogs, and the internet. 
Personally, I had no idea what Computer Science was when I started undergrad, and I had even less of an idea what jobs I could get with a CS degree (and likewise for my math degree), so let's start here and try to reverse engineer some good practices for getting the job you've decided sounds cool.
I'll note this list is incomplete, and doesn't take into account ways to blend CS with your other majors and minors.

## Jobs?

### CS
* __Software engineer__: For a long time, I think a software engineer was (and maybe still is) the "canonical" Computer Science job. Software engineering positions, however, can be broken up into a handful of categories: most notably, you might see jobs that say "full-stack", "front end", or "back end" developer. I'll defer to [this Udacity article](https://www.udacity.com/blog/2020/12/front-end-vs-back-end-vs-full-stack-web-developers.html) to describe the differences at a high level.

        * Job 1 at an entertainment company for a back-end developer asks for NodeJS/Typescript, MongoDB, MySQL, Snowflake, API development, noting that you'll interact with Semantic HTML and React.js on the front end
        * Job 2 at an online marketplace (full-stack) asks for experience with PHP, MySQL, TypeScript, Javascript, React, with Scala and ML as a bonus
        * Job 3 at a marketing company (full-stack) asks for OOP experience, exposure to Spring Boot or Java frameworks, UI development, familiarity of SQL, exposure to cloud platforms like AWS, exposure to version control.
        * Job 4 at a consulting firm (front-end) asks for HTML, CSS, Javascript, and an understanding of different Content Management Systems (e.g., Wordpress, Squarespace)

* __Mobile developer__: sometimes also titled "Software Engineer, Mobile" or something of the sort, this is software engineering for mobile apps. See [this discussion](https://www.wearedevelopers.com/lexicon/mobile-developer) regarding some differences between cross-platform (Android AND Apple) vs Native development.

        * Job 1 at a shopping rewards company (Android developer) asks for experience building native applications for android devicesand design patterns, Kotlin/Java, experience with APIs, XML, exposure to Agile development practices, and version control. 
        * Job 2 at an automobile company asks for Mobile Development, either Swift, Kotlin, Objective-C, or Java, familiarity with Javascript, and React/ReactNative. 
        * Job 3 at a wearables company asks for proficiency coding in languages such as C, C++, C#, Java, or assembly. The position uses Kotlin/Swift.

* __(Junior) ML Engineer__: Since ML isn't part of the core curriculum for many undergraduate CS departments (yet), many ML engineering roles have Master's or PhD level requirements, for better or worse. With that said, there are still some Bachelor's level ML roles (and you might also be interested in Data Scientist titles). This is the area that I have the most background, and will make one additional note: there are a plethora of data types/structures that ease pose their own challenges in ML. For example, financial companies and banks often work with time-series data to make forecasts about the future, while biotech companies struggle with the challenge of pattern detection from absurdly long sequences of molecules. In robotics and autonomous driving, companies might have to take a "multimodal" approach, merging LIDAR, RADAR, and image data to make decisions. Each of these data structures brings its own expertise, and is a niche on its own that one can specialize around.

        * Job 1 at an autonomous driving company asks for experience with distributed systems principles, solid Python or C++, experience with ML frameworks such as Tensorflow or PyTorch, preferred experience with cloud computing platforms.
        * Job 2 at a fintech company asks for familiarity of architectural frameworks for large, distributed applications, ranking and recommender systems background, Python, SQL, Pytorch/Tensorflow, and bonus if you have experience with Spark, Kafka, or Kubernetes.
        * Job 3 at a drug discovery company (asks for a Master's degree) asks for Pytorch/Tensorflow/JAX, Cloud computing (AWS/GCP/Azure), version control (Github), and CI/CD (Jenkins, Azure DevOps, etc.) 

* __Security Analyst, Security Engineer, Penetration Tester, etc.__: These are (from my understanding) common "entry level" cybersecurity positions. Cybersecurity, more than other careers in CS, is unified through certification processes such as those offered through [ISC2](https://www.isc2.org) and [CompTIA](https://www.comptia.org/training/by-certification/security). The CompTIA Security+ is considered as the "baseline" for working in the field, while the ISC2 CISSP is more helpful for promotion and advancement.   The [OffSec OSCP](https://www.offsec.com/courses/campaigns/pen-200/?utm_campaign=Google-Ads_Brand_PPC_PWK_2020_Update_NAM=&utm_medium=cpc=&utm_source=google=&utm_source=adwords&utm_term=kwd=offsec%20oscp:cid-9248778671:kwd-809885078389:dev-c:mt-e&utm_campaign=Brand_PPC_PWK_2020_Update_USA&utm_medium=ppc&utm_content=crid=416866894009&hsa_mt=e&hsa_ad=416866894009&hsa_net=adwords&hsa_src=g&hsa_kw=offsec%20oscp&hsa_tgt=kwd-809885078389&hsa_cam=9248778671&hsa_acc=7794287291&hsa_ver=3&hsa_grp=92741699943&gad_source=1&gad_campaignid=9248778671&gbraid=0AAAAAC44S4Td-OGXe1u1MkcZBLBIuGBgA&gclid=Cj0KCQjwiqbBBhCAARIsAJSfZkYvH038T9_WH6EmTef5DRVDbmg49lgs2BMDl8WxbNQFsyMHacxLwmQaAqurEALw_wcB) certification is also helpful, though expensive out of pocket and one of the hardest to pass (about 20-25% pass rate). I defer to [this website](https://cybersn.com/cybersecurity-career-center/) for more info on the differences between different titles within Cybersecurity.

        * Job 1 (Security Analyst) at a bank asks for knowdge of firewalls, intrusion detection, prevention products, disaster recovery, knowledge of data security and privacy laws and frameworks (FFIEC, FDIC, GLBA/SOX), and Microsoft office
        * Job 2 (Security Analyst) at an industrial equipment supplier asks for experience with Identity and Access Management, IT Risk Management, Business Continuity and Disaster Recovery Planning, Cloud-based technologies, Firewalls, and Computer Forensic Techniques
        * Job 3 (Security Engineer 2) at an online marketplace asks for familiarity with Operating Systems, Malware Functionality, experience with SIEM and SOAR platforms, and experience in common programming languages.
        * Job 4 (Penetration Testing Analyst) at a cybersecurity company for hedge funds asks for knowledge of pen-testing tools like metasploit and neosploit, knowledge of attack stages, experience with Linux and Windows OS, and experience in a scripting language (e.g., Python).

### Data Science
* Data analyst: 

        * Job 1 at a consulting firm asked for R, Python, Tableau SQL, Excel, Agile Development, Version Control, e.g., Github
        * Job 2 at a personalized medicine company asked for SQL, Excel, Looker or Tableau
        * Job 3 at a "Big 5" tech company asked for "preferred qualifications" including experience with (some of) SQL, Kusto, Python, Azure Data Explorer, Power BI, PowerApps, Azure Data Factory, and knowledge of AI
        * Job 4 at an entertainment company asked for experience in SQL, Python or R, and Looker or Tableau

* (Junior) Data Scientist

        * Job 1 at a business consulting firm asked for Python, SQL, familiarity with data viz tools (Tableau, PowerBI), knowledge of AI/ML
        * Job 2 at a data science consulting firm (meta, I know) asks for Python, SQL, R, experience with AWS, and Javascript familiarity
        * Job 3 at a software company asks for SQL, distributed systems (Hadoop, Spark, DataBricks), proficiency in Python or R, practical and theoretical experience with ML, and profeciency with statistics (e.g., hypothesis testing, ANOVA, etc.)


## Resume formatting
Because of the plethora of specializations within CS and variety of frameworks one can gain experience with, you'll want to make sure your resume emphasizes the background you do have. For example, while some university teach CSCI 1090 (or their equivalent) in R, we are currently teaching it in Python. Therefore, it does not suffice to simply put a course name or title in your reusme to convey what technical skills and frameworks you have experience with.
For an industry resume, especially at the entry level, you should not exceed a page.
I'll try to paint broad strokes for how to order it, but [Reddit](https://www.reddit.com/r/cscareerquestions/wiki/faq_resumes/) has better advice than I can write here. Check out the ```r/cscareerquestions``` subreddit.

### Sections and ordering
Typically, the sections of a CS resume go something like: (1) Name, Contact, and Links, (2) Education (second for current students, later if you have already graduated), (3) Experience and Projects, (4) Skills, (5) Research and Publications (if applicable... might also be listed under projects depending on the job you're going for).

 * __Name, Contact, and Links__: Use the name you want to be known as professionally, and an email address that is appropriately bland. I had a friend whose birthday was April 20th, and email was something like ```firstname_lastname_420@gmail.com```, and they had a pretty hard time finding a job out of undergrad until they made a new email.
 For links, I'd recommend including your LinkedIn, Github, and StackOverflow (if you have/use an account). Note that linking to a "stale" page might actually reflect nagetively, so make sure your Github is up-to-date and clean, meaning that your repos don't have anything that might be a security leak (e.g., passwords/API tokens), as that's a bad look if you did that at your work.

* __Education__: Include your GPA if you're an undergrad, majors, amd minors, and possibly relevant coursework (especially for internship applications in your "mid" years.) You don't need every class in the major, but include critical electives, like an ML class if you're applying for ML roles.

* __Experience and projects__: This can include class projects you're especially proud of. Don't include "intro" projects that are essentially copy+pasted from a million tutorials on the internet. I've seen this a ton, and it's a red flag to me. Even better if you've collected a dataset that isn't commonly used, but you are able to share publicly. Again, include Github links if you have them and the code is clean.

* __Technical Skills__: Have a section for languages and a section for frameworks/tools if needed, along with proficiency in strength or years for each. For example, I might put Python (advanced), SQL (intermediate), R (intermediate), C# (intermediate), Java (intermediate), C++ (intermediate), C (novice), and Julia (novice) for my languages. Sort these by experience. For frameworks, see the requirements for the jobs above: demonstrate that you have the skills to do the job. I might have my frameworks be PyTorch (adv.), Tensorflow (adv.), MongoDB (adv.), Docker (intermediate), etc.

## Finding internships

The internship search cycle seems to be year round. Despite the impression that all the business students find their internships in the fall, the spring is a fine time to find an internship as well if smoething in the fall doesn't work out. 
I recommend you start earlier in the year, and I think searching for internships after your sophomore year makes sense. I've heard of folks finding internships after their freshman year, but it's not required.
If a summer internship doesn't work out, spend some time developing personal projects if you can to build up that Github portfolio, and don't be afraid to look for fall internships as well. Many universities have ways for you to get academic credit for internships you do during the schoolyear.

I like [StackOverflow Jobs](jobs.stackoverflow.com) since they seem to not have sponsored results at the top, but LinkedIn and ZipRecruiter are fine as well. There are other job boards within fields (e.g., the [Responsible Tech Job Board](https://alltechishuman.org/responsible-tech-job-board)) but that's for another day.
Finally, go to career fairs! BC has such a strong alumni network, that's a great opportunity to put a face to a name. As great as your resume might be, what's even better is being a good coworker that others enjoy collaboriating with.

## Gaining industry knowledge beyond the classroom

Check out Substack, Podcasts, and Reddit! This is something I regret not doing more as an undergrad. On Substack, I like The Pragmatic Engineer and ByteByteGo. I don't listen to many podcasts in this space, but I'll link [these recs](https://www.reddit.com/r/cscareerquestions/comments/7b22sr/good_podcasts_for_computer_sciencetech_field/). Finally, on Reddit, check out ```r/cscareerquestions```, ```r/computerscience```, and ```r/compsci```.
