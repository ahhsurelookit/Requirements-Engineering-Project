# Week 5 — Activity Diagram

## 1. Process Modelled
Create Equipment Booking in the College Equipment Booking System.

## 2. Purpose
The activity diagram shows what happens during the booking process, including the steps and the decision about availability.

## 3. Activities
- Select Equipment
- Select Date
- Check Availability
- Enter Booking Details
- Submit Booking
- Booking Recorded

## 4. Decision and Guards
The decision is “Is equipment available?”
- [available] continues to Enter Booking Details, Submit Booking and Booking Recorded.
- [not available] leads to an unknown note because the next step has not been confirmed.

## 5. Unknowns
It is not known what should happen when the requested equipment is unavailable.

## 6. Stakeholder Question
What should happen when the requested equipment is unavailable?

## 7. Modelling Decision
I have not added a waiting list, alternative equipment, approval, payment, notification or cancellation process because the lab says not to invent a solution without supporting information.

## 8. Reflection
The activity diagram helped me show the steps in a process and how a decision changes the flow. It also showed that I need to ask a stakeholder what happens when equipment is unavailable.

## Short assessed-project application
**Process / Use Case:** View scheduled student support appointments (provisional; confirm this matches the project requirement).

**Activity 1:** Open the appointment schedule.

**Activity 2:** Select a date.

**Activity 3:** View the appointments for that date.

**Possible decision:** Is the user allowed to view these appointments?

**Possible guard(s):** [permission confirmed] / [permission not confirmed]

**One unknown:** Which user roles are allowed to view appointment details?

**Who could answer it?** Student support staff or the person responsible for managing the service (to be confirmed).

**Question to ask:** Which roles can view appointment details, and what information can each role see?

These are proposed planning steps for the assessed-project section, not confirmed system requirements.
