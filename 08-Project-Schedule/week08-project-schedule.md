# Project Schedule: RCHN Patient Intake and Scheduling System

**Consultant:** Fabian Rodriguez  
**Role:** Associate Consultant, Project Manager, NovaTech Consulting  
**Engagement:** Regional Care Health Network (RCHN)  
**Date:** October 22, 2026

---

## Work Breakdown Structure

### Grouping 1: Patient Intake System
- 1.1 Standardized patient intake forms
- 1.2 Patient identity verification
- 1.3 Missing information validation

### Grouping 2: Appointment Scheduling System
- 2.1 Appointment availability display
- 2.2 Scheduling conflict detection
- 2.3 Appointment reminder functionality

### Grouping 3: System Testing and Deployment
- 3.1 Intake and scheduling integration testing
- 3.2 User acceptance testing
- 3.3 System deployment across six clinics

### Grouping 4: Staff Training and Support
- 4.1 Staff training materials
- 4.2 Staff training across six clinics
- 4.3 Initial post-launch support

### WBS Rationale

I organized the WBS around the main goals we focused on during Week 5, which included improving patient intake and scheduling across all six clinics. I separated the intake and scheduling systems because they address different problems, but both are important to the overall project. I also included testing, deployment, and staff training because developing the system alone wouldn't be enough if employees couldn't properly use it.

Some smaller features from our backlog were grouped together under the larger system components rather than listed separately. I left out dashboard customization because we previously decided it wasn't a priority compared to the core features. I think this structure gives us a better understanding of the work involved without making the schedule unnecessarily complicated. Appointment reminders would still need to be confirmed as part of the approved phase-one scope.

---

## Task Dependencies

**Dependency 1**
- Predecessor: Confirm intake and scheduling requirements
- Successor: Configure patient intake system
- Type: Finish-to-Start

**Dependency 2**
- Predecessor: Configure patient intake system
- Successor: Configure appointment scheduling
- Type: Finish-to-Start

**Dependency 3**
- Predecessor: Configure appointment scheduling
- Successor: Test integrated system
- Type: Finish-to-Start

### Dependency Logic

One important dependency is completing the patient intake system before moving forward with the appointment scheduling system. If the intake work gets delayed by two weeks, it could push back the scheduling work and eventually delay testing. Since these activities depend on each other in our proposed schedule, there wouldn't be much flexibility unless we adjusted how the work was organized. One possible solution would be to have developers work on parts of the scheduling system that don't require the intake system to be finished. This could help reduce the delay, but we would need to make sure the two systems still work together properly.

---

## Activity Schedule

| ID | Activity | Duration (Working Days) | Predecessors | Start Week |
|---|---|---|---|---|
| A | Confirm intake and scheduling requirements | 5 | None | 1 |
| B | Configure patient intake system | 10 | A | 2 |
| C | Configure appointment scheduling | 10 | B | 4 |
| D | Test integrated system | 5 | C | 6 |

### Scheduling Assumptions

I estimated the durations based on how much work each activity might require. Confirming requirements seemed like something that could take about five working days, while configuring the intake and scheduling systems would likely take longer. I placed the activities in an order where the basic patient information system is completed before connecting it to scheduling. I also allowed time for testing once both systems are ready. One uncertainty is whether the existing patient information can be transferred and used without issues. If there are compatibility problems or additional changes needed, it could affect the schedule and require more development time.

---

## Milestones

### Milestone 1: Patient Intake Configuration Completed

**Target:** End of Project Week 3

**Exit Criteria:** The patient intake system has been configured with standardized forms, patient identity verification, and missing information checks. The team has reviewed the configuration and confirmed it is ready for integration with scheduling.

### Milestone 2: Integrated System Testing Completed

**Target:** End of Project Week 6

**Exit Criteria:** The intake and scheduling systems have completed their planned integration tests. Patient information transfers correctly, appointment availability is displayed accurately, and scheduling conflicts are detected. Any critical issues have been resolved before moving forward.

### Critical Path Analysis

For the critical path exercise, the first path consisting of activities A, B, and D takes 9 working days, while the second path consisting of A, C, and D takes 11 working days. This makes the second path the critical path because it has the longest duration and determines when the project can finish.

If one of the activities on the critical path gets delayed by two days, the overall project could take 13 days instead of 11. The first path has two days of float, so there is some flexibility without affecting the completion date. This calculation is separate from our proposed RCHN schedule, which uses different activities and estimated durations.

---

## Schedule Reflection

### Scope Connection

I chose Staff Training and Support because it connects to our Week 5 scope, where we included employee training and initial support after the new system is launched. Since RCHN operates across six clinics, it's important that employees understand how to use the new system before relying on it for their daily work. Breaking this part of the project into training materials, staff training, and post-launch support helps us better understand what needs to be completed. I also think including these steps in our schedule could help prevent problems during the transition.

### Objective Connection

I chose Integrated System Testing Completed because it supports our overall goal of improving patient intake and scheduling. Before introducing the new system across all six clinics, we need to make sure the different features work together properly. Completing this milestone would help us identify problems before employees start using the system. However, the team would still need to confirm the testing requirements and whether our estimated timeline is realistic. I think this milestone is important because moving forward without proper testing could create more problems than the old system already had.

---

*NovaTech Consulting | IT 3310 | Governors State University | Fall 2026*
