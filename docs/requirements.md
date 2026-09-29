# Requirements

Working draft. Edit via pull request as the club decides things.

## Goal

Let students book after-school office hour periods with teachers without email back-and-forth, and let teachers control when they are available.

## Users

| Role | Can do |
|---|---|
| Student | View available slots, book a slot, cancel their own booking, see their upcoming bookings |
| Teacher | Create/edit/delete availability, see who booked each slot, cancel a slot |
| Admin (maintainer or staff) | Manage teachers, view all bookings |

## Core Rules

- A slot can be booked by at most one student (unless the teacher allows a group size > 1).
- A student cannot hold two bookings in the same time period.
- Cancellation allowed until a cutoff (proposed: 1 hour before start).
- Times are shown in the school's local time zone.

## MVP (v0.1)

1. Teacher can publish slots (date, start, end, location)
2. Student can see all open slots
3. Student can book and cancel
4. Double-booking is prevented at the database level
5. Login restricted to school accounts

## Later (v0.2+)

- Email/in-app confirmation and reminders
- Recurring weekly availability
- Waitlist
- Calendar export (Google Calendar / .ics)
- Teacher notes / reason for visit

## Open Questions (turn each into an Issue)

- [ ] Backend and database: Supabase, Firebase, or something else?
- [ ] Auth: school Google accounts? Does the school allow it?
- [ ] Does the school allow storing student info on third-party services?
- [ ] Hosting: Vercel or another platform?
- [ ] Who at the school approves and uses the finished tool?

## Suggested First Issues

1. Decide backend and auth
2. Scaffold the Next.js project and set up linting
3. Design the database schema (users, slots, bookings)
4. Build the slot list page
5. Build the booking flow with double-booking protection
6. Build the teacher availability page
7. Add login and role handling
8. Deploy a preview to Vercel
