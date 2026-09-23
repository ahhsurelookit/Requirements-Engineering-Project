#Week 3 - Requirements Analysis and Specification

##1. Information from Week 2

##2. Candidate Requirements
"People are sometimes unsure whether a camera is available" - Problem

"Technicians need to know what equipements is due back" - Stakeholder need

"The system shall record the expected return date for each booking" - Candidate Requirement

"The college should build a mobile app" - Solution Idea

"We assume all users will have a college login" -  Assumption

"A lecturer wants reliable availability information before promising equipment" - Stakeholder need


##3. Requirements Surgery


##4. Functional Requirements
Requirement 1
"The system shall be user-friendly"
What is the problem?: User friendly to who? what one might find easy, another  might find difficult. It's ambigiuous.

One clarification question: Which specific user tasks or workflows should we measure to define 'user-friendly'.

Missing Information: Who is the target audience this system is made for? For novice users? Experts? 

Requirement 2
"The system shall notify users about bookings."

What is the problem?: It's ambiguous, what users get notified and how do they get notified?

One clarification question: Which trigger events prompt a notification and what delivery channel?

Missing Information: Target audience, delivery channel and trigger event.

Requirement 3
"The system shall allow staff to create, edit and delete bookings and send reminders."

What is the problem?: Its a compound statement. Its combining distinct actions into one question.

One clarification question: Which staff are allowed to access? Are they receptionists? Managers? IT?

What information is missing?: User roles and reminder rules: how they are sent out and when?

##5. Quality Requirements
"The technician needs to know whether equipment is available before confirming a booking"

WHO?
Who Needs this?: The technician.

WHAT?
What does the system need to do?:  Needs to know whether equipment is available before confirming a booking.

WHEN?
Does a condition apply?  When the technician attempts to select or finalize a date and time slot for a booking.

WHY? 
Why is this needed? Prevent double booking.

HOW WILL WE KNOW?
How could we verify it?: Book an item that is already reserved for that time. Verify the system blocks the confirmation and shows an error message.

ID: FR-01 Requirement: The system shall allow an authorised user to view equipment availability for a selected date. Source: Stakeholder. How could we verify it?: Log into the system with authorized credentials.

ID: FR-02. Requirement: The system shall allow registered students to book an available study room for up to two consecutive hours per day. Source: College Students. How could we verify it?: Attempt to make a second booking on the same day to verify that the system blocks any total duration exceeding the two-hour daily limit.

ID: FR-03. Requirement: Source: How could we verify it?

##6. Project Application

##7. Reflection

