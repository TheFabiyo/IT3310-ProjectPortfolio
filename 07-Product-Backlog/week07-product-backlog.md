
# Product Backlog: RCHN Patient Intake and Scheduling System

**Consultant:** Fabian Rodriguez  
**Role:** Associate Consultant, NovaTech Consulting  
**Engagement:** Regional Care Health Network (RCHN)  
**Date:** October 16, 2026

---

## Product Backlog

### Story 1: RCHN-101, Standardize Patient Intake

**User Story:** As a front desk employee, I want a standardized patient intake form so that I can collect the same required information at every clinic.

**Acceptance Criteria:**
- Required fields must be completed before the form can be submitted.
- The same standard intake fields must appear at all six clinics.

**Story Points:** 5  
**MoSCoW Priority:** Must Have

### Story 2: RCHN-102, Confirm Patient Identity

**User Story:** As a front desk employee, I want to verify a patient's identity before updating their record so that I can avoid mistakes and protect patient information.

**Acceptance Criteria:**
- Employees must confirm patient identity using the approved verification process.
- The system must prevent record changes until verification is completed.

**Story Points:** 5  
**MoSCoW Priority:** Must Have

### Story 3: RCHN-104, Flag Missing Information

**User Story:** As a front desk employee, I want the system to identify missing required patient information so that I can correct it before completing intake.

**Acceptance Criteria:**
- The system must clearly identify missing required fields.
- Employees must be able to correct the information before submitting the form.

**Story Points:** 3  
**MoSCoW Priority:** Must Have

### Story 4: RCHN-103, Show Appointment Availability

**User Story:** As a scheduling employee, I want to see available appointment times so that I can schedule patients without having to check multiple systems.

**Acceptance Criteria:**
- The system must display available appointment slots for the selected clinic.
- Booked appointment slots must not appear as available.

**Story Points:** 8  
**MoSCoW Priority:** Must Have

### Story 5: RCHN-108, Warn About Scheduling Conflicts

**User Story:** As a scheduling employee, I want to receive a warning when an appointment conflicts with an existing booking so that I can prevent double bookings.

**Acceptance Criteria:**
- The system must detect conflicts before an appointment is confirmed.
- The warning must identify the conflict and prevent an overlapping booking.

**Story Points:** 5  
**MoSCoW Priority:** Must Have

### Story 6: RCHN-105, Send Appointment Reminders

**User Story:** As a patient, I want to receive appointment reminders so that I am less likely to forget an upcoming visit.

**Acceptance Criteria:**
- The system must send reminders using the patient's approved contact preference.
- Reminders must display the correct appointment date, time, and location.

**Story Points:** 8  
**MoSCoW Priority:** Should Have

### Story 7: RCHN-109, Customize Dashboard Colors

**User Story:** As a clinic employee, I want to customize my dashboard colors so that I can make the system more comfortable to use.

**Acceptance Criteria:**
- Employees must be able to choose from approved dashboard color options.
- The selected colors must remain saved for the employee's account.

**Story Points:** 2  
**MoSCoW Priority:** Won't Have This Time

---

## Prioritization Rationale

### Must Have Justification

I marked Confirm Patient Identity as a Must Have because protecting patient information is an important part of the new intake and scheduling system. If employees can't properly verify a patient's identity, it could lead to incorrect records or changes being made to the wrong patient's information. With RCHN operating across multiple clinics, I think this needs to be addressed early in development. Other features also depend on accurate patient information, so making this a priority should help prevent bigger problems later.

### Won't Have Rationale

I marked Customize Dashboard Colors as Won't Have This Time because I don't think it addresses the bigger issues they are trying to fix. While having a customizable dashboard might be nice for employees, improving patient intake and preventing scheduling conflicts should come first. We already have limited time and resources, so focusing on appearance doesn't seem necessary right now. I wouldn't completely rule it out, though. If employees bring up concerns about the system's appearance or usability during testing, we could reconsider adding it later.

---

## Backlog Reflection

### Persona Connection

I chose Standardize Patient Intake because it connects to the problems front desk employees were experiencing with the old system. From our Week 3 research, we learned how important it was for employees to have accurate and consistent patient information. Having a standardized intake process across all six clinics could help reduce confusion and prevent mistakes. I think this would also make their jobs easier since they wouldn't have to deal with different ways of collecting the same information.

### Scope Connection

I chose Warn About Scheduling Conflicts because improving the scheduling system was one of the main goals we focused on during Week 5. The backlog helped turn that general goal into something more specific for the developers. Instead of just saying the system needs better scheduling, we explained that it should detect overlapping appointments and warn employees before confirming a booking. I think having those details makes it easier for the development team to understand what's expected and gives them something they can actually test.

---

*NovaTech Consulting | IT 3310 | Governors State University | Fall 2026*
