# Requirements Catalogue — Scenario B (Draft)

**Status:** Candidate draft. Requirements marked proposed are not confirmed stakeholder requirements. Priorities are provisional and should be reviewed after clarification.

| ID | Type | Requirement statement | Priority | Source / status | Rationale and verification idea |
|---|---|---|---|---|---|
| FR01 | Functional | The system shall allow an authorised user to view scheduled student support appointments. | Must | Week 3 candidate requirement; not stakeholder-confirmed | Test that an authorised account can view scheduled appointments and access follows agreed permissions. |
| FR02 | Functional | The system shall display the student support services available for appointment requests. | Must | Proposed from Scenario B | Check that the service list matches the services confirmed by the college. |
| FR03 | Functional | The system shall associate each appointment with the relevant support service. | Should | Proposed | View an appointment and verify its service association. |
| FR04 | Functional | The system shall record the date and time of each scheduled appointment. | Must | Proposed | Create or schedule a test appointment and verify the saved date/time. |
| FR05 | Functional / access control | The system shall restrict viewing of appointment details according to agreed user permissions. | Must | Scenario privacy concern; roles/details unresolved | Test access using accounts with different agreed permissions. |
| NFR01 | Privacy | The system shall collect only personal information agreed as necessary for arranging and managing an appointment. | Must | Proposed privacy requirement | Compare form fields with the approved list of necessary information. |
| NFR02 | Security | The system shall enforce the agreed access permissions for appointment information. | Must | Scenario privacy concern; details unresolved | Test access using accounts representing each agreed role. |
| NFR03 | Accessibility | The prototype shall be reviewed against applicable accessibility criteria, including relevant WCAG 2.2 guidance. | Should | Proposed quality goal | Record review findings against selected applicable criteria. |

## More to be done and added.

## Notes
- The catalogue contains 18 candidate requirements (12 functional and 6 non-functional/quality requirements).
- These are draft proposals to help structure the project, not evidence that stakeholders have agreed to every feature.
- FR01 is the strongest direct link to the Week 3 lab. FR09/NFR02 express the access-control constraint that must be clarified.
- Confirm the exact user roles, appointment information, services, appointment types, booking process, cancellation rules and required personal data before treating relevant requirements as final.
