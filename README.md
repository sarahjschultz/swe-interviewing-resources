# Interview Prep for Software Engineers
This is an curated list of resources that I collected during 2024 while looking for a new role following my sabbatical from @ProductPlan. I use the word _curated_ intentionally, because not all resources are created equally and these felt like they wasted the least amount of my time while also driving outcomes. You'll need to supply your own personal grit and dogged determination, but I know you can do it. 

## General Preparation Approach and Guidance
Depending on how long it has been since you've been in the interview circuit, you may need to skip this section and jump straight to studying for technical interviews before wasting too much energy on the necessary (but ultimately insufficient) topics of resumes, cover letters, LinkedIn profiles, etc. I'll leave that up to you. 

### Resumes
If you are applying to a company which uses an Applicant Tracking System, then your resume keyword density will matter. I know it's kind of silly and that you are so much more than your keyword count, but that's just how it is. I liked the tool [ResumeWorded](https://resumeworded.com/) for feedback on how your resume will read in those systems, and only recommend the free version (unless you have the disposable income).

If you are applying to startups where the applicant tracking system is less streamlined and your resume is more likely to be read by a human on a first pass, follow the widespread recommendations to tailor your resume to the job description you are applying to. 

[This is a great resource](https://www.techinterviewhandbook.org/resume/) for more resume tips. Note that it is tailored more towards engineers interviewing for FAANG roles, but I think you can easily generalize the principles you see there.

Another great resource is [here](https://www.faangtechleads.com/resume/checklist). Don't worry about upgrading for the paid version unless you have the disposable income and/or are not getting ANY interview requests after 50+ applications.

### Cover Letter
You gotta write a cover letter. Full stop. Be yourself and remember that real humans read cover letters and are more likely to connect to you if you are authentic and friendly. Don't be a weird robot unless you are actually a weird robot. 

### Write Down All Your Best Projects Over the Last 1-2 Years
A common interview approach that I am encountering from _startups_ in 2024 is for teams to ask to do a "portfolio review" of one of your "most complex" projects. They don't necessarily want to see the source code, but they do want you to be able to talk in detail about the problem you were solving, how you measured success, and the impact and scalability of your work. Take some time up front to write these down (a spreadsheet works well for this) so that you are prepared. 

### LinkedIn Premium
I do not think this is worth your cash unless you've applied to 50+ jobs and have had zero replies. The main benefit that I can see from Premium is that you can message recruiters or hiring managers directly. This could be useful if you feel like NO ONE is looking at your applications, but based on what I've heard, it's still a bit of a crapshoot.

## Behavioral Interviews
[This](https://www.techinterviewhandbook.org/behavioral-interview-rubrics/) is a great resource for behavioral interview prep EVEN IF you are not applying for a FAANG role.

If you are applying for Staff+ roles, I also recommend reading [Will Larson's Staff Engineer book](https://www.amazon.com/Staff-Engineer-Leadership-beyond-management-ebook/dp/B08RMSHYGG) as preparation for behavioral questions around technical leadership outside of the management track. 

## Technical Interviews
Technical interviews is where you will spend the bulk of your time interviewing for software roles. In this current season, across startups and FAANG roles, I am being scheduled for between 3-6 rounds of technical interviews per organization. So in my opinion, this is where the bulk of your energy for prep should be invested. 

### Data Structures and Algorithms
Most of my early round interviews seem to focus on these topics, so I recommend front-loading prep here. I actually found this somewhat straightforward because the practice is drill-like and targeted (and there are often CORRECT answers), unlike system design where problems and solutions can be extremely open-ended and most experienced engineers can make persuasive arguments for wildly divergent solutions. 

If you need to refresh fundamentals, I highly recommend the MIT OpenCourseware Algorithms Course -- MIT 6.006. You can find it on Youtube [here](https://www.youtube.com/watch?v=HtSuA80QTyo&list=PLUl4u3cNGP61Oq3tWYp6V_F-5jb5L2iHb). 

If you need to go back even further in terms of fundamentals, I really love Harvard's CS50 taught by David Malan. You can find it on Youtube [here](https://www.youtube.com/watch?v=8mAITcNt710&t=49413s&pp=ygUMY3M1MCBoYXJ2YXJk)

For drill, I recommend doing the problems assigned in those courses AND I recommend Leetcode. 

I do not like Hackerrank for drill under any circumstances. Let's talk about why. First of all, the easy/medium problems are too easy and you'll never actually encounter them in live interviews so spending time there is wasteful. Second, the "assessments" they offer are wildly varied in difficulty level, even if they occur within a prescribed "course". I think this can be highly demotivating if you are crushing problems left and right and then you get decimated on the very first quiz. Don't spend your time there.

Back to Leetcode. I've been surprised at the number of teams who are straight up using Leetcode for first and second round technical interviews. I think it is worthwhile to get used to this platform and be comfortable executing problems here. Second, I think the Premium version is actually worth your money for this reason: when you do solve a problem (even if it is suboptimal) they offer an Editorial video walkthrough of the brute force and then optimized solutions, with runtime analysis. Every video I've encountered is EXCELLENT and I think makes it worth the money. 

I like the [Grind75](https://www.techinterviewhandbook.org/grind75?weeks=6&hours=25&grouping=topics&order=difficulty) list of problems, grouped by topic and ordered by difficulty as a way to get rolling.

[These cheatsheets](https://www.techinterviewhandbook.org/algorithms/array/) are great topic-by-topic algorithms support. 

### Language
Pick your strongest language and drill all of your problems in this language. Don't worry too much about learning every new language you encounter in job descriptions in order to excel in an interview. Even startups are open to running problems with you in the language of your choice so that they can focus more on your grasp of the fundamentals, vs getting tripped up over new/unfamiliar syntax. 

### System Design
If you are interviewing for a senior or Staff+ role at an organization > 50 people, you should be prepared for at least one round of your technical interviews to focus on system design. If you are not senior or Staff+, don't spend your precious time here. 

Resources I like for this specifically are: 
- [This](https://github.com/donnemartin/system-design-primer) free OS SystemDesign primer. They have an excellent [study guide](https://github.com/donnemartin/system-design-primer?tab=readme-ov-file#system-design-topics-start-here) which can help you cut down on the total volume of topics based on your time horizon for interviews.
- [Grokking Modern System Design Interview for Engineers & Managers on Educative.io](https://www.educative.io/courses/grokking-modern-system-design-interview-for-engineers-managers) -- this course is only accessible if you have a paid Educative account, but IMO it is worth the investment if you are interviewing at this level.
- [This Youtube Channel](https://www.youtube.com/c/SystemDesignInterview) has great videos and is free if you don't want to shell out for Educative

You might not like hearing this (I didn't) but most of the people I've chatted with who have landed Staff+ roles in the last year at orgs > 50 people, have recommended participating in **mock system design interviews** to prepare. I have not used these yet, but the tools recommended to me were:
- https://igotanoffer.com/
- https://interviewing.io

