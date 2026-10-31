
# Risk Register: RCHN Patient Intake and Scheduling System

**Consultant:** Fabian Rodriguez  
**Role:** Associate Consultant, NovaTech Consulting  
**Engagement:** Regional Care Health Network (RCHN)  
**Date:** October 31, 2026

---

## Risk Entries

The probability and impact ratings are reasoned estimates based on the course scenario, not measured frequencies. The course uses Low = 1, Medium = 2, and High = 3. **Score = Probability × Impact**; 1–2 is Low, 3–4 is Medium, and 6–9 is High.

### Risk 1: Patient Data Migration

**Description:** If patient information does not transfer correctly during migration, then RCHN could experience inaccurate patient records, scheduling mistakes, and delays in deployment.  
**Probability:** Medium (2)  
**Impact:** High (3)  
**Score:** 6 — High  
**Response Strategy:** **Mitigate.** Test the migration process and verify patient records before deployment. Investigate any missing or incorrect information and correct it before approving the affected data for use.  
**Trigger or Monitoring Condition:** Missing or incorrect records appear in validation results, or known migration discrepancies remain unresolved as the launch readiness review approaches.  
**Owner:** **Developer.** The Developer can monitor migration validation, investigate technical errors, and work with RCHN IT staff to correct the information.

### Risk 2: Staff Training

**Description:** If clinic employees are unavailable or unable to complete training before deployment, then staff could struggle with the new system and cause delays in daily operations.  
**Probability:** Medium (2)  
**Impact:** Medium (2)  
**Score:** 4 — Medium  
**Response Strategy:** **Mitigate.** Coordinate training schedules with clinic managers, monitor completion, and arrange additional training opportunities when scheduling conflicts arise.  
**Trigger or Monitoring Condition:** Training attendance or completion falls behind the agreed plan, or a clinic reports staff cannot attend before its planned deployment.  
**Owner:** **Project Manager.** The Project Manager can coordinate clinic managers, monitor the training milestones, and adjust the rollout plan if needed.

### Risk 3: Incomplete Acceptance Testing

**Description:** If critical acceptance testing is not completed before deployment, then system problems could go undetected and affect the quality and reliability of the new system.  
**Probability:** Medium (2)  
**Impact:** High (3)  
**Score:** 6 — High  
**Response Strategy:** **Avoid.** Do not authorize deployment with unfinished critical acceptance tests. Complete those tests, document the results, and resolve or formally address critical defects before approving go-live.  
**Trigger or Monitoring Condition:** Required acceptance tests are incomplete, fail, or have unapproved critical defects at the agreed readiness checkpoint.  
**Owner:** **Product Manager.** The Product Manager can confirm that the acceptance criteria match user needs and coordinate sign-off with Developers and clinic stakeholders.

### Risk 4: Standardized Workflow

**Description:** If the six clinics cannot follow a standardized intake and scheduling workflow, then the project may require additional changes that could affect the scope, schedule, and cost.  
**Probability:** Medium (2)  
**Impact:** Medium (2)  
**Score:** 4 — Medium  
**Response Strategy:** **Mitigate.** Review existing intake and scheduling processes with clinic employees, confirm essential differences, and refine requirements before the team finalizes implementation decisions.  
**Trigger or Monitoring Condition:** A clinic identifies a required workflow step that the proposed standard process cannot support, or acceptance review reveals incompatible operating practices.  
**Owner:** **Product Manager.** The Product Manager can gather user feedback, manage requirement changes, and check that the agreed workflow provides value across the clinics.

### Risk 5: Resource Availability

**Description:** If key project team members are unavailable during important development or testing activities, then the project could fall behind schedule and require additional resources.  
**Probability:** Medium (2)  
**Impact:** Medium (2)  
**Score:** 4 — Medium  
**Response Strategy:** **Mitigate.** Review team availability against upcoming milestones, identify coverage gaps early, and coordinate task reassignment or additional support if needed.  
**Trigger or Monitoring Condition:** An assigned team member becomes unavailable for a scheduled critical task, or team capacity no longer covers the agreed sprint or testing work.  
**Owner:** **Scrum Master.** The Scrum Master can monitor team capacity and impediments, then coordinate with the Project Manager when resource changes are needed.

---

## Bring Forward

### Week 5 Assumptions — Project Plan Foundation

**Assumption 1:** RCHN staff at all six clinics will be available for training before the new system is implemented. If this is not true, the training and rollout schedule may need to be adjusted.

**Assumption 2:** The six clinics will be able to use a standardized patient intake and scheduling workflow. If major differences between clinic workflows are discovered, the project scope and implementation plan may need to change.

Source: [Week 5 Project Plan Foundation](https://github.com/TheFabiyo/IT3310-ProjectPortfolio/blob/main/05-Project-Plan-Foundation/week05-project-plan.md)

### Week 7 High-Priority Backlog Item

**RCHN-102: Confirm Patient Identity (Must Have).** As a front desk employee, I want to verify a patient's identity before updating their record so that I can avoid mistakes and protect patient information.

Source: [Week 7 Product Backlog](https://github.com/TheFabiyo/IT3310-ProjectPortfolio/blob/main/07-Product-Backlog/week07-product-backlog.md)

### Week 8 Schedule Activity

**WBS 3.4: Run Integration and User Acceptance Testing.** This activity is intended to verify patient identity checks, intake fields, appointment availability, and conflict detection before deployment approval.

Source: [Week 8 Project Schedule](https://github.com/TheFabiyo/IT3310-ProjectPortfolio/blob/main/08-Project-Schedule/week08-project-schedule.md)

---

## Assumption Connection

**Risk 2 — Staff Training:** This connects to my Week 5 assumption that employees at all six clinics would be available for training before implementation. If employees cannot complete training on time, it could delay deployment and affect our objective of having all clinic staff trained before using the new system.

**Risk 4 — Standardized Workflow:** This connects to my Week 5 assumption that all six clinics could use the same intake and scheduling process. If the clinics have major differences in how they operate, the team might need to change the system or project scope. This could affect our objective of creating a consistent intake and scheduling process across all six locations.

---

## Score Justification

**Risk 1 — Patient Data Migration:** I rated this risk as Medium probability and High impact, giving it a score of 6. We already know that data discrepancies were found during migration, so there is a concern that unresolved errors could affect the new system. If patient records are inaccurate, it could cause scheduling problems, affect patient information, and potentially delay deployment. I think this deserves immediate attention because all six clinics will depend on accurate information.

**Risk 3 — Incomplete Acceptance Testing:** I also rated this risk as Medium probability and High impact, giving it a score of 6. Since some acceptance testing is still incomplete, there is a possibility that important problems could go undetected. If the system is launched without properly testing its main features, employees and patients could experience issues that affect daily operations. I think completing critical testing is important for protecting project quality and making sure the system is ready before going live.

---

## Risk Reflection

### Highest Priority Risk and Project Impact

I think Patient Data Migration deserves the most attention because incorrect or missing patient information could create serious problems across all six clinics. Even though Incomplete Acceptance Testing received the same risk score of 6, I would prioritize patient data because the team has already identified discrepancies during migration. If these problems aren't resolved, they could affect the quality of the new system, delay the launch schedule, and increase costs if additional work is needed to correct the information. It could also cause employees and stakeholders to lose confidence in the system. I still think we should work toward the original launch date, but making sure patient information is accurate needs to remain a priority.

### Risk vs. Issue Distinction

One thing I learned this week is that a risk is something that could happen, while an issue is something that has already happened. We already know that patient data discrepancies were found, two clinics haven't completed training, and some acceptance testing remains unfinished. Those are existing issues, but Risks 1, 2, and 3 focus on the possible future consequences if those issues aren't addressed before deployment. Risk 4 involves the possibility that clinics cannot use the same workflow, and Risk 5 involves future project team unavailability. I checked each entry against the known scenario facts and wrote the risk as an uncertain event and its possible consequence instead of describing an existing issue as though it might happen. This matters because existing issues need action now, while risks need monitoring and a planned response.

---

*NovaTech Consulting | IT 3310 | Governors State University | Fall 2026*
