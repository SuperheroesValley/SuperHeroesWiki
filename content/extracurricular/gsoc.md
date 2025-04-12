---
title: 11 - Google Summer of Code
weight: -16
---

**_Authors: [Emanuele Micheletti](https://www.linkedin.com/in/emanuelemicheletti/)_**

🎞️ Watch the presentation on youtube: [link](https://www.youtube.com/watch?v=vh-mnxwElyA)

[![ Watch the presentation on youtube](http://img.youtube.com/vi/vh-mnxwElyA/0.jpg)](https://www.youtube.com/watch?v=vh-mnxwElyA "Video Title")

GSoC, which stands for **Google Summer of Code**, is a project funded by Google focused on the Open Source world.
Its aim is to find paid contributors, with a duration of 3 months, dedicated to implementing new features or fixing complex bugs.
Getting selected for GSoC is not easy; typically, only about 2% of all applicants make it through the selection phase.
Selected participants will be compensated based on the size of the project they undertake, categorized as small, medium, or large.
The duration of the project is typically three months, but payment is based on the project's size rather than the time spent.
For more information on payment rates and project sizes, you can refer to the official GSoC website: [Contributor Stipends for 2024](https://developers.google.com/open-source/gsoc/help/student-stipends#total_stipend_amount)

Below are the official timeline and a more applicant-focused timeline, which is useful for understanding the essential steps.

Official path
![Gsoc Official Path](/media/gsoc_official_steps.png)

Real path for applicants
![Gsoc Official Path](/media/gsoc_real_steps.png)

### How to get selected for Google Summer of Code

#### Chosing the right organization

In GSoC, there is a maximum number of applications you can submit.
To increase the likelihood of being accepted, it's advisable to submit the maximum number of applications, as this is not frowned upon.
So far, the maximum number has always been 3.
It's a good practice to strategically select these 3 organizations, avoiding the fierce competition of other applicants and aiming to stand out. A general rule to follow is:

-   **1 small** org, **1 large** org, and **1 medium** org
-   **2 medium** orgs and **1 large** org

Ideally, the organization should not be directly related to what you want to do.
For example, if you are a web developer applying for Django, you will likely have many competitors.
Look for an organization whose product is not directly aligned with your skills.
It's highly probable that the projects within it still contain something of interest to you.

#### Choosing a Project Within the Organization

##### Project duration

Every year, the characteristics of project division change.
In 2023, there were _medium_ and _long_ projects, while in 2024, the project durations are categorized as _short_, _medium_, and _long_.
Generally, it's advisable to speak with the mentor or carefully read any _README_ files provided by the organizations to understand how this division is interpreted.
Some organizations may be more flexible, or sometimes projects may not require research and may not be well-defined, while other times, the conditions are more stringent.
However, it's always important to assess your time availability honestly.
A long project is generally considered full-time work for a duration of at least 3 months.

##### Previous Skills

This also varies from organization to organization.
Generally, in-depth skills are not required, but it's important to keep in mind that competition is very high, especially in very popular projects.
The best approach is to demonstrate genuine interest in the project, conduct research, and maintain a proactive attitude.
Asking questions in discussions and investigating possible solutions for issues is encouraged.
Of course, being familiar with GitHub or GitLab is a plus, as most of the communication and work will occur through these platforms.

#### Selection phase with the organization for application submission

This phase involves the screening process conducted by the organizations.
While it's not an official phase of GSoC, due to the high number of applicants, organizations typically pre-screen applications.
This means that if you submit your application without having obtained the unofficial approval from the repository maintainer or potential mentor, it will be completely ignored.
Of course, submitting the application does not guarantee participation in GSoC. It simply means that the future mentor is aware of you and will put in a good word on your behalf.

Usually, there are 3 possible kinds of pre-screening:

-   Selection based on "demonstrated ability": If you have created a personal project that has had moderate success and this project is directly related to an organization's project, you may be selected bypassing the entire selection phase.
-   Selection based on contributions to the repository: Some organizations label issues with the "GSoC" tag. In this case, the best way to be selected is to solve as many of these issues as possible.
-   Selection through competition: This type of selection typically occurs in organizations that do not have issues related to projects or when projects involve creating a new repository.
    A competition is created among all interested parties, usually involving the creation of a mini-project. The top performers are selected based on time and quality.

#### Preparing the Proposal

Once you've been notified that you've passed the selection phase, the mentor will likely contact you to explain how to best prepare the proposal.
Of course, follow their advice as closely as possible. Below are some rules that should apply to everyone, along with an example of a real proposal that was selected by Google for participation in GSoC.

##### Conducting Research

The proposal should detail the approach or approaches you intend to adopt to successfully complete the chosen project. Often, the projects involve particularly complex bugs to solve or new features to implement. That's why it's important to conduct thorough research to understand how to approach their solution.
The proposal should avoid overly detailed implementation specifics unless they directly relate to the primary focus of the project but in general the more details provided, the better. It's also helpful to indicate anticipated difficulties, points requiring experimentation, etc.
The approach doesn't have to be set in stone; the solution adopted may not necessarily align with the initial approach. The key is to demonstrate that research has been done, show familiarity with the subject matter, and prove that you are the right person to successfully complete the project.

An example of an application that was selected for the GSoC: [[**LINK**](/media/proposal_sample.pdf)]

#### During the waiting period for Google's announcement

During the waiting period for Google's announcement, neither you nor the mentor can do anything to increase your chances of being officially selected by Google.
Your proposals are evaluated by Google, and Google has the authority to not select a project for any reason (even if the organization has been announced).
This may occur if a project hasn't garnered enough interest or hasn't received a compelling or realistic proposal.

The only action you can take is to continue contributing to small issues within the organization to become familiar with the codebase, in anticipation of potential participation.

### Surviving Google Summer of Code

If you are selected, you will receive an email on the day of the official announcement from Google.
This email will contain all the information regarding payments, privacy, and other bureaucratic matters.
Be careful not to select the checkbox indicating "I waive monetary compensation".

#### Period Before the Official Start

There is a small window of time between the participation announcement and the official start of GSoC.
For many organizations, it doesn't matter whether you start immediately, but it's advisable to begin downloading the necessary tools and familiarizing yourself with the codebase.
If the project involves a specific tool, use it and perform various tests to fully understand its functionality.
Ask your mentor how they prefer you to organize your work; sometimes, mentors prefer asynchronous communication, while other times they prefer periodic update calls.

#### Start of the Coding Period

During this phase, it's a good practice to share a document with the mentor outlining the daily activities.
This document, being unofficial, doesn't need any particular format; it simply serves as a means for the mentor to provide feedback and to understand that you are working consistently.
It may also serve as a consultative document for you during the coding phase.

#### First Performance Review

The first performance review occurs midway through the period.
If you choose a "short" project, this will be the only performance review you receive.
The review involves feedback from both the mentor to you and from you to the mentor.
Upon successfully passing this review, you will receive the first payment (or the only payment in the case of short projects).

#### Second Coding Period

The same rule applies as for the first coding period.
It's very likely that the mentor will ask you to write a blog post about the work you've done.
In this case, it's good to plan to dedicate a few days to writing this post.
For many organizations, it's not strictly necessary for you to finish all the work by the GSoC deadline; it's mostly a formality.

#### Second Performance Review

The same rule applies as for the first performance review.
If you pass this review, you have successfully completed GSoC.

### Pros and Cons of Participating in GSoC

The advantages are numerous and depend on both the participants and the organizations. In general:

#### Pros:

-   Learning Opportunity: Participants gain extensive knowledge.
-   Networking: Participants get to know influential figures in the open-source world.
-   Contribution to Solutions: Participants can contribute to solving well-known problems and make a name for themselves in the open-source community.
-   Opportunity for Maintainership: Participants may become maintainers of the organization (depending on the organization).
-   Highly Marketable Experience: GSoC experience is highly marketable in the job market.
-   Financial Compensation: Participants receive payment.

#### Cons:

-   Overlap with Exams: GSoC typically coincides with exam periods, which can be challenging for some participants.

If a participant is not selected after several weeks of initial contributions, it's not necessarily a disadvantage.
Open-source contributions are always valuable for gaining experience; it's not wasted time.
