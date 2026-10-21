# Requirements Catalogue — Scenario B (Draft)

**Status:** Candidate draft. Requirements marked proposed are not confirmed stakeholder requirements. Priorities are provisional and should be reviewed after clarification.

| ID | Type | Requirement statement | Priority | Source / status | Rationale and verification idea |
|---|---|---|---|---|---|
| FR01 | Functional | The system shall allow an authorised user to view scheduled student support appointments. | Must | Week 3 candidate requirement; not stakeholder-confirmed | Test that an authorised account can view scheduled appointments and access follows agreed permissions. |
| FR02 | Functional | The system shall display the student support services available for appointment requests. | Must | Proposed from Scenario B | Check that the service list matches the services confirmed by the college. |
| FR03 | Functional | The system shall display appointment availability for a selected service and date. | Must | Proposed from Scenario B | Select a service/date and compare displayed availability with the schedule. |
| FR04 | Functional | The system shall allow a student to request an appointment. | Must | Proposed; confirm booking process | Submit a request using valid information and check that it is recorded or routed as agreed. |
| FR05 | Functional | The system shall record the information agreed as necessary for an appointment. | Must | Proposed; required fields unknown | Check that agreed required fields are saved and unnecessary fields are not requested. |
| FR06 | Functional | The system shall allow authorised staff to manage appointment availability. | Must | Proposed; exact roles unknown | Test availability management with an authorised staff account. |
| FR07 | Functional | The system shall associate each appointment with the relevant support service. | Should | Proposed | View an appointment and verify its service association. |
| FR08 | Functional | The system shall record the date and time of each scheduled appointment. | Must | Proposed | Create or schedule a test appointment and verify the saved date/time. |
| FR09 | Functional / access control | The system shall restrict viewing of appointment details according to agreed user permissions. | Must | Scenario privacy concern; roles/details unresolved | Test access using accounts with different agreed permissions. |
| FR10 | Functional / access control | The system shall restrict appointment changes to users authorised under the agreed policy. | Must | Proposed; policy needs confirmation | Attempt a change with authorised and unauthorised test accounts. |
| FR11 | Functional | The system shall support appointment changes and cancellations according to an agreed policy. | Should | Scenario identifies changes/cancellations as a concern; policy unknown | Test each confirmed change/cancellation rule. |
| FR12 | Functional | The system shall distinguish between the appointment types confirmed by the college. | Should | Scenario indicates different appointment types; list to confirm | Verify that each confirmed type can be identified in the system. |
| NFR01 | Privacy | The system shall collect only personal information agreed as necessary for arranging and managing an appointment. | Must | Proposed privacy requirement | Compare form fields with the approved list of necessary information. |
| NFR02 | Security | The system shall enforce the agreed access permissions for appointment information. | Must | Scenario privacy concern; details unresolved | Test access using accounts representing each agreed role. |
| NFR03 | Accessibility | The prototype shall be reviewed against applicable accessibility criteria, including relevant WCAG 2.2 guidance. | Should | Proposed quality goal | Record review findings against selected applicable criteria. |
| NFR04 | Usability | In a walkthrough, a reviewer should be able to identify a support service and find where to check its availability. | Should | Proposed; set measurable success criteria after review | Ask a reviewer to complete the task and record whether they succeed without help. |
| NFR05 | Reliability / consistency | The appointment details displayed by the system shall match the details stored for that appointment. | Must | Proposed | Compare saved test appointment details with details shown when retrieved. |
| NFR06 | Usability | The system shall present the selected service, appointment date and time in clearly labelled fields. | Should | Proposed | Review the screen and test whether a reviewer can correctly identify these values. |

## Notes
- The catalogue contains 18 candidate requirements (12 functional and 6 non-functional/quality requirements).
- These are draft proposals to help structure the project, not evidence that stakeholders have agreed to every feature.
- FR01 is the strongest direct link to the Week 3 lab. FR09/NFR02 express the access-control constraint that must be clarified.
- Confirm the exact user roles, appointment information, services, appointment types, booking process, cancellation rules and required personal data before treating relevant requirements as final.
