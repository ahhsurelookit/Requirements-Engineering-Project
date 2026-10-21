# Week 3 — Requirements Analysis and Specification

## 1. Information from Week 2

In Week 2, I identified stakeholders, their possible needs and concerns, and questions that still need to be answered.

The main lesson was that requirements should be based on information from stakeholders rather than assumptions. More information is needed before all the requirements can be finalised.

## 2. Candidate Requirements

The following statements relate to the College Equipment Booking System worked example.

| Statement | Type |
|---|---|
| People are sometimes unsure whether a camera is available. | Problem / observation |
| Technicians need to know what equipment is due back. | Stakeholder need |
| The system shall record the expected return date for each booking. | Candidate requirement |
| The college should build a mobile app. | Solution idea |
| We assume all users will have a college login. | Assumption |
| A lecturer wants reliable availability information before promising equipment. | Stakeholder need |

## 3. Requirements Surgery

### Requirement 1: The system shall be user-friendly.

**Problem:** User-friendly is ambiguous. What one person finds easy, another person might find difficult.

**Clarification question:** Which user tasks should be easy to complete?

**Missing information:** Who are the target users, and how will ease of use be measured?

### Requirement 2: The system shall notify users about bookings.

**Problem:** It does not explain which users receive notifications or how they are sent.

**Clarification question:** Which events should trigger a notification, and who should receive it?

**Missing information:** The recipients, delivery method and events that trigger notifications.

### Requirement 3: The system shall allow staff to create, edit and delete bookings and send reminders.

**Problem:** This combines several different functions into one requirement.

**Clarification question:** Which staff members should be allowed to create, change or cancel bookings?

**Missing information:** User permissions and the rules for sending reminders.

## 4. Functional Requirements

The following requirements relate to the College Equipment Booking System worked example.

### WHO, WHAT, WHEN, WHY and HOW WILL WE KNOW?

**WHO?** The equipment technician.

**WHAT?** The system should allow an authorised user to check equipment availability before confirming a booking.

**WHEN?** When checking equipment for a selected date and time.

**WHY?** To help prevent double-bookings.

**HOW WILL WE KNOW?** Attempt to book equipment that is already reserved for the same period and check whether the system prevents the conflicting booking.

### Candidate functional requirements

| ID | Requirement | Source | How could it be verified? |
|---|---|---|---|
| FR-01 | The system shall allow an authorised user to view equipment availability for a selected date. | Candidate requirement from the lab example | Log in with an authorised account, select a date and check that availability is displayed. |
| FR-02 | The system shall record the expected return date for each equipment booking. | Technician's stated need in the lab example | Create a booking with an expected return date and check that the date is saved. |
| FR-03 | The system shall allow authorised staff to view equipment that is due to be returned. | Technician's stated need in the lab example | Create test bookings with return dates and check that the relevant equipment can be identified. |

These are candidate requirements and should be reviewed against the information available in the case.

## 5. Quality Requirements

Quality requirements describe how the system should operate.

| ID | Quality requirement | Why does it matter? | How could it be checked? |
|---|---|---|---|
| NFR-01 | The system should prevent unauthorised users from accessing or changing booking information. | Booking information should be protected. | Test access using accounts with different permissions. |

### Review of the availability requirement

**Requirement:** The technician needs to know whether equipment is available before confirming a booking.

This is a stakeholder need, rather than a complete system requirement.

**WHO?** The equipment technician.

**WHAT?** Check equipment availability before confirming a booking.

**WHEN?** When checking a selected date and time.

**WHY?** To reduce the risk of double-booking.

**HOW WILL WE KNOW?** Test whether a booking that conflicts with an existing reservation is prevented.

## 6. Project Application

My assessed project is Scenario B: College Student Support Appointment System.

### Candidate requirement

The system shall allow an authorised user to view scheduled student support appointments.

**Source:** This is a proposed requirement based on the purpose of the system. It has not yet been confirmed by a stakeholder.

**Type:** Functional requirement.

**What is unclear?** Which users are authorised to view appointments, and what appointment information can they see?

**Clarification question:** Which users should be allowed to view appointment details?

**How could it be verified?** Test whether an authorised user can view scheduled appointments and whether access follows the agreed permissions.

**Unknown:** What appointment details should students and support staff be allowed to view?

**Who could answer?** Student support staff and the person responsible for managing the service.

## 7. Reflection

### 1. What makes a requirement difficult to understand?

Vague wording, missing information and combining several functions into one requirement can make it difficult to understand.

### 2. What information do you still need for your project?

I need to confirm the types of appointments available, who can manage appointments and what information needs to be recorded.

### 3. Who could provide that information?

Students, student support staff, support administrators and the person responsible for the service could help answer these questions.
