# Week 1 — Initial Discovery

## 1. Facts

- The college is thinking about implementing a system to book shared equipment.
- Laptops, cameras, projectors, specialist equipment
- Currently bookings are made by emails, spreadsheets, ad hoc's
- Equipment can be booked out twice.
- Unclear if equipment is available.
- Manual checking of bookings by staff.
- Equipment not returned as expected.

## 2. Assumptions

- The college has a large number of students and staff.
- Students and staff may need different permissions.
- The college has IT support to help maintain its systems.
- The college may have a limited budget for a new system.

These assumptions need to be checked before making decisions.

## 3. Unknowns

- How many students and staff attend the college?
- Which classes need equipment most often?
- How many laptops, cameras and projectors are available?
- What is the budget for the proposed system?
- Who is allowed to book specialist equipment?

## 4. Stakeholders

- Students — need to find and book available equipment.
- Lecturers — need equipment for classes.
- Equipment technicians — manage equipment and returns.
- College management — oversee college resources.
- IT support staff — may help maintain the system.
- Equipment suppliers — may provide or replace equipment.

## 5. Goals

The system should help the college to:

- Reduce double-bookings.
- Make equipment availability easier to check.
- Reduce the time staff spend managing bookings.

## 6. Scope

### Likely in scope

- Checking equipment availability.
- Recording equipment bookings.
- Keeping track of expected return dates.
- Helping staff identify equipment that has not been returned on time.

### Out of scope or not yet established

- Developing a mobile app.
- Purchasing new equipment.
- Connecting the system to other college software.

These features should not be included without further evidence that they are needed.

## 7. Candidate Requirements

### Functional requirements

- FR-01: The system should allow authorised users to check equipment availability.
- FR-02: The system should allow authorised users to request equipment for a specified date and time.
- FR-03: The system should record equipment bookings and expected return dates.
- FR-04: The system should allow authorised staff to view equipment bookings.

### Non-functional requirements

- NFR-01: The system should be easy to use so that users can complete common booking tasks without unnecessary assistance.
- NFR-02: The system should prevent unauthorised users from accessing or changing booking information.

These are candidate requirements and may change when more information is available.

## 8. Requirement Surgery

### R1: The system should be easy to use.

**What is wrong?**

Easy to use is vague because different users may have different levels of experience.

**Improved version:**

The system should allow authorised users to check equipment availability for a selected date.

**How could it be checked?**

Ask users to check availability for a date and see whether they can complete the task successfully.

### R2: The system should be secure.

**What is wrong?**

The requirement does not explain what information needs protection or who should have access.

**Improved version:**

The system should prevent unauthorised users from viewing or changing booking records.

**How could it be checked?**

Test whether a user without the required permissions can access or change a booking.

## 9. Reflection

This practical helped me understand why it is important to investigate a problem before deciding on a solution. I also learned that assumptions and unknowns should be recorded instead of treated as facts.

I still need to find out who is allowed to book equipment, what information must be recorded and what happens when equipment is returned late.
