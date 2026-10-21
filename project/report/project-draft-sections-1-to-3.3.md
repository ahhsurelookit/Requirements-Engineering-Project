# Requirements Engineering Project — Draft Sections 1–3.3

**Scenario B: College Student Support Appointment System**
## 1. Problem, Stakeholders and Goals

### 1.1 Background and current situation

The college provides student support services, including academic support, careers advice and learning support. The scenario describes a current process that relies on email, phone calls, calendars, spreadsheets and informal methods. Students may be unsure which service to contact, availability may be unclear, and staff may spend time manually coordinating appointments. Changes and cancellations can also be difficult to manage. Appointment information may include personal details, so access and privacy need careful consideration.

### 1.2 Problem statement and goals

**Problem statement:** Students and staff need a clearer, more consistent way to find and coordinate student support appointments. The current mix of communication channels and manual records can make availability difficult to understand and appointment changes harder to manage.

**Goals:**
- Help students identify the appropriate support service.
- Make appointment availability easier to understand.
- Reduce avoidable manual coordination for staff.
- Make appointment changes easier to manage under an agreed policy.
- Protect students' personal information through agreed access controls.

These are goals drawn from the scenario, not proof that a particular solution has been validated.

### 1.3 Stakeholders, needs and proposed elicitation

| Stakeholder / role | Possible need or concern | Evidence / source |
|---|---|---|
| Students | Find relevant support and suitable appointment times; understand how to request or change an appointment; privacy of personal information | Scenario; needs to be investigated |
| Student support staff | View and coordinate appointments; understand availability and appointment details | Scenario and candidate requirement in Week 3 lab |
| Support administrators | May organise schedules and appointment records | Proposed stakeholder role; confirm responsibility |
| College management / service manager | Ensure the service meets student needs and is manageable | Proposed stakeholder role; confirm responsibility |
| IT support staff | May maintain the system and support access/security | Proposed stakeholder role; confirm responsibility |
| Data protection representative | May advise on handling personal information | Proposed stakeholder role; confirm responsibility |

**Proposed elicitation:** Interview students and support staff to understand the current process and common difficulties; analyse existing appointment guidance or policies if available; ask the service manager about appointment types, access roles and change rules. No interview is claimed as completed.

Important questions include: “Which roles may view appointment details, and what can each role see?” (ask support staff/service manager) and “What information is necessary to arrange an appointment?” (ask support staff and the appropriate privacy contact).

### 1.4 Scope and system boundary

**Proposed in scope:** displaying available support services; checking appointment availability; requesting or arranging appointments under a confirmed process; recording agreed appointment details; allowing authorised users to view schedules; and supporting changes/cancellations if the college confirms the rules.

**Not yet established / outside the current draft:** automated reminders, waitlists, integration with existing college systems, automated approval, and any specific cancellation or no-show policy. These should not be treated as requirements until confirmed.

### 1.5 Assumptions, candidate requirements and open questions

| ID | Type | Description | Evidence / status | Action needed |
|---|---|---|---|---|
| A01 | Assumption | The system will handle appointment records for the support services identified by the college. | Working assumption | Confirm services and scope |
| A02 | Assumption | Different user roles may need different levels of access to appointment information. | Privacy concern in scenario; exact roles unknown | Confirm roles and permissions |
| CR01 | Candidate requirement | The system shall allow an authorised user to view scheduled student support appointments. | Week 3 lab; not stakeholder-confirmed | Confirm authorised roles and visible details |
| CR02 | Candidate requirement | Students should be able to request appointments through the system. | Proposed feature | Confirm whether requests are direct or staff-mediated |
| Q01 | Open question | Which roles may view appointment details, and what can each role see? | Unresolved | Ask support staff/service manager |
| Q02 | Open question | What are the rules for changing or cancelling appointments? | Scenario identifies difficulty but gives no policy | Ask service manager/support staff |
| Q03 | Open question | What personal information is necessary to arrange an appointment? | Unresolved | Ask support staff and privacy contact |
| Q04 | Open question | Are reminders required? | Not specified | Ask students and service manager |

## 2. Requirements Catalogue

See [`../requirements/requirements-catalogue.md`](../requirements/requirements-catalogue.md) for the 18-item draft catalogue. Requirements marked proposed must be confirmed.

### 2.1 Requirements analysis notes

FR01 is the most directly supported candidate requirement from the Week 3 lab. It identifies the function but leaves the phrase “authorised user” undefined. The role and the appointment details that may be viewed must be clarified before the requirement is finalised. FR09 and NFR02 describe access control, but their detailed rules depend on that same clarification.

FR04, FR05, FR06 and FR11 describe plausible capabilities, but the exact booking process, required fields, staff responsibilities and cancellation rules have not been confirmed. NFR04 needs a measurable success criterion after a walkthrough is designed. The catalogue should be updated as new evidence is obtained rather than treating every proposal as agreed.

## 3. Requirements Modelling

### 3.1 Use Case Diagram (UC-D01)

Insert `../diagrams/UC-D01-use-case-diagram.drawio` (export it as a PNG from diagrams.net for the Word report). The diagram shows the actor “Authorised user” outside the system boundary and the use case “View scheduled student support appointments” inside it. The exact role and permissions remain open questions.

### 3.2 One Use Case Narrative

| Field | Your content |
|---|---|
| Use case / ID | UC01 — View scheduled student support appointments |
| Primary actor / goal | Authorised user (exact role to be confirmed). Goal: view scheduled student support appointments they are permitted to access. |
| Preconditions / trigger | Trigger: user opens the appointment schedule. Whether login or any additional precondition is required must be confirmed. |
| Main successful flow | 1. User opens the appointment schedule. 2. User selects a date. 3. System checks the user's permission. 4. If permission is granted, the system displays scheduled appointments for the selected date. |
| Alternative / exception flows | If permission is not granted, appointment details are not displayed. The exact message or next action is not specified and needs confirmation. |
| Outcome / postconditions | An authorised user can view the scheduled appointment information they are permitted to access. |
| Related requirements | FR01, FR09, NFR02 |

### 3.3 Activity Diagram (AD01)

Insert `../diagrams/AD01-activity-diagram.drawio` (export it as a PNG from diagrams.net for the Word report). The workflow starts when a user opens the appointment schedule, selects a date and the system checks permissions. If permission is granted, the scheduled appointments for that date are displayed. If access is denied, appointment details are not displayed. The exact roles and denial response remain open questions.

## Next sections to complete

- 3.4 Conceptual UML class diagram (CD01), including justified multiplicities and open questions.
- 3.5 Model consistency check.
- Section 4: 4–6 connected prototype screens and an honest walkthrough record.
- Section 5: explain selected NFRs already in the catalogue.
- Section 6: priorities and the lecturer's actual change request; do not invent the request.
- Section 7: 3–5 user stories with testable acceptance criteria.
- Section 8: traceability, review and validation evidence.
- Section 9: actual GitHub repository link and genuine commit examples.
- Section 10: accurate AI Use Record.
