# 🚀 July 2024 Release Notes 🚀

**Update to Requeue Reasons**

Requeueing refers to putting a client back in the queue after they have been matched, but *before* they have attended a first therapy session with a treatment clinician. It’s an important workflow, but since it’s a process to manage exceptions, it’s a window into ways that our current system isn’t totally serving our needs. During requeues, we capture “requeue reasons” to better understand these exceptions.

In July, we made some small changes to how we capture requeue reasons to improve our ability to learn from these exceptions. We added 1 new reason, ““clinician-initiated - conflicts with company/team meeting.” If “client-initiated — other” or “clinician-initiated — other” are selected, we also added a conditional text field that prompts the user for more info about the reason. These two “other” options account for ~19% of responses, so there is a big opportunity here to learn.

*Note: “client-initiated...” is a category we reserve for requeues that happen when the client has requested the requeue due to schedule, clinical fit, etc., while “clinician-initiated” is used for situations where the clinician has requested the requeue.
We’re excited for the to learn more from the data we’ll be able to gather with these changes!*

![image](https://github.com/user-attachments/assets/10173d3d-ab21-472c-8c49-4ba9c4caced3)

**Client Scheduler Onboarding and Full Launch**

This has been a HUGE month for our Client Scheduler product. Over the final weeks of July, we released a series of high-impact to clinicians to make client scheduling intuitive, simple, and easy.
  - Released Full-Time Onboarding Wizard for onboarding full-time clinicians
    - Introduces clinicians to the product and guides them through how Client Scheduler will work
    - Provides a template schedule and clear guidance on how to first establish availability
- Released Full-Time Ramp experience to onboarding full-time clinicians
    - We brought the ramp experience that we developed last year into a fully-automated and intuitive interface. It provides clinicians the context they need to set up their schedules and helps clinicians understand the guardrails we have around schedules to ensure we can meet client needs and demand.
- Released Client Scheduler to all Full-Time and Network clinicians (with the exception of those doing consults)
    - Network: provides a self-service model, taking the lift off clinical leads & allowing for real-time updates to give Network clinicians the flexibility they need.
    - Network clinicians can directly edit their autoschedule target # of scheduled sessions and available
    - Client Scheduler then guides clinicians to provide enough hours for the new clients needed, without breaching labor laws on max back-to-back or daily sessions.
- Released Network Onboarding Wizard for onboarding Network clinicians
    - Invites clinicians to set their target hours before accessing the tool, and explains how to manage availability.
- Released Network Ramp experience for onboarding Network clinicians
    - For the first time, we now offer an automated Ramp experience for network clinicians. We built on our learnings from full-time ramp to offer clinicians an automated experience that gets clinicians to their target and takes the guess-work out of the process.

![image](https://github.com/user-attachments/assets/7406133d-f0d1-4c7b-90bc-130cafe44032)
![image](https://github.com/user-attachments/assets/587ec6a8-d1b4-4ce3-8489-da68836b5714)
![image](https://github.com/user-attachments/assets/7eaeef81-4e1a-409d-8c61-50fc4f30d2a3)








# 🚀 June 2024 Release Notes 🚀

**Client Scheduler**

We’ve been working tirelessly on improving the scheduling experience for our clinicians. As part of new software launch, we “beta test” the tool with a small group to get their feedback & make updates before launching to the entire team. In June, we started beta testing Client Scheduler with the part-time team. So far, we’ve heard a lot of positive feedback. Updates for network users include:

- Client Scheduler for Network clinicians provides a self-service model, taking the lift off clinical leads & allowing for real-time updates to give Network clinicians the flexibility they need.
- Network clinicians can directly edit their autoschedule target # of scheduled sessions and available
- Client Scheduler then guides clinicians to provide enough hours for the new clients needed, without breaching labor laws on max back-to-back or daily sessions.
- “Edit mode” makes it more apparent when you’re making changes, and tracks edits as clinicians add/delete so they can check before saving.

![image](https://github.com/blakeparkinson/Care-Platform-Release-Notes/assets/1864277/f4dfbf51-31ef-4dcb-99a7-142aa0ebe7af)

**Switch All Clinicians from Zoom to Meet**

To simplify and scale we needed to align on a consistent strategy for video conferencing for sessions. We successfully made the conversion (all consults and client sessions are now conducted via Google Meet) and learned some lessons along the way.


---

# 🚀 May 2024 Release Notes 🚀

## 🎉 New Features

**Documentation Reminders**

Notes are a key part of clinical documentation, but not the full story. To better support clinicians in completing timely & high quality documentation, we’re expanding our “Incomplete Notes” feature to encompass notes, diagnosis codes and treatment plans.

Now, you’ll be reminded of the following documentation needs on your dashboard:
- When a session note is due, or if it is overdue
- When a diagnosis code is due, or if it is overdue
- If your client is missing an active & primary diagnosis code in their chart
- When a treatment plan is due, or if it is overdue
- If a treatment plan is present but not active
- If a treatment goal is missing a due date
- If a treatment goal is nearing its due date, or has expired

While this feature is not intended to be a replacement for the Looker dashboards on documentation timeliness and compliance and is not inclusive of all quality/compliance indicators, we hope that this feature **empowers clinicians by providing direct visibility** into their outstanding or upcoming documentation needs

<img width="622" alt="Screenshot 2024-05-30 at 1 50 01 PM" src="https://github.com/blakeparkinson/Care-Platform-Release-Notes/assets/171188179/09915656-ac69-4b37-9fc7-79baee813132">


*Note: In the case of a client returning to care with the same clinician, the due date listed on the treatment plan or dx code reminder may show the old first session date. We will refine this logic over time to improve this experience.*


**In-App Product Announcements**

To help communicate about new feature launches, we’ll be displaying announcements directly in the Care Platform. Our first version of this will go live today to announce the Documentation Reminders feature.


**Consult Nudges**

We launched a number of small, in-product nudges in Matchmaker to support our consult clinicians in improving the number of clinical fits generated at the consult appointment. These tooling updates are an important first step in using our product experience to help our consult clinicians make more informed decisions in the matching process to ensure our clients needs are met in a timely manner.


<img width="580" alt="Screenshot 2024-05-20 at 11 06 15 AM" src="https://github.com/blakeparkinson/Care-Platform-Release-Notes/assets/171188179/d878f496-60c3-4e4c-a13c-6389296fe044">





---

# 🚀 April 2024 Release Notes 🚀

## 🎉 New Features

- **Integrated Looker into the Care Platform for Clinicical Managers:** In a continuous effort to make the Care Platform a one stop shop, we've added Looker to the care platform. Clinical Managers will now be directed to the new "manager-dashboard" page on login, where they can interact with looker.

<img width="1511" alt="Screenshot 2024-05-02 at 4 23 59 PM" src="https://github.com/blakeparkinson/Care-Platform-Release-Notes/assets/1864277/0e64cd00-97d9-4856-92e7-9afcd131f4db">


## 🌟 Enhancements

- **Added 30 minute buffer window so no client surveys go left behind:** Sometimes clinicians need to schedule last minute appoinments, this change ensures that clients will still receive surveys even if they are scheduled last minute.

- **Ported the Utilization page to Roofdog (the new Care Platform):** With the Utilization page now living in the new Care Platform, we made updates that allow for an overall better and more accessible user experience.

## 🔧 Improvements

- **Centralized API Layer:** Rather than the Care Platform relying on the browser to make API calls to multiple servies and perform heavy computational logic, we've moved these calls to a dedicated API layer which allows the browser to do its primary job(rendering the page.) This also puts us in a place to begin building Role Based Access.

- **Introduced smart caching:** We're now caching data which skips trips to the server, and makes the care platform feel incredibly snappy overall.

![Alt Text](https://media.giphy.com/media/v1.Y2lkPTc5MGI3NjExZGx1dDhwZDRwenBvZzYyZHpveHZvbGowMWU0cmd4aHJ3N2Vka3R6byZlcD12MV9pbnRlcm5hbF9naWZfYnlfaWQmY3Q9Zw/a7Y6lravckuKA/giphy.gif)

To infinity and beyond,
Clinician Enablement Team
