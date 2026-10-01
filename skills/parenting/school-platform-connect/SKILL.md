---
name: school-platform-connect
description: "Connects your assistant to the school platforms a parent uses (GrowApp, Moodle) and to birthday invites forwarded on WhatsApp or iMessage. Reads notices, homework, tests, grades and deadlines, then turns them into one daily list and calendar suggestions. Use when the user wants help managing school tasks, results, birthdays or invites for their children."
license: CC0-1.0
compatibility: Works with any agent that can read the sources listed under Requirements. Written as plain instructions, no vendor lock-in.
metadata:
  author: swarm-hq
  version: "1.0.0"
  vertical: parenting
---

# School platform connect

Connect an assistant to GrowApp, Moodle and WhatsApp invites, read only, for parents.

## Requirements

- Parent access to the school platform: your own login for GrowApp, or your own or your child's login for Moodle, kept in a password manager, never typed into chat
- A way to read the platform: signed-in browser session, or for Moodle the mobile app web service or the calendar export link
- Optional: calendar access to add events with your approval

## When to use

- Each school morning
- When a birthday or event invite is forwarded to the assistant
- When you ask "what homework, tests or results are due?"
- Once, to set up a new school platform

## Steps

1. Set up once: ask which platforms the family uses. Never ask for a password in chat. Use the password manager or a secure sign-in link from the tool you use.
2. GrowApp: read the notices, menu, events and photos feed through the parent's own signed-in session, the same pages the parent sees. This is not an official API, so say if a page layout changes and a post cannot be read.
3. Moodle, option 1 (best): if the school enables the Moodle mobile web service, request a token with the user's own login, then call only read functions: core_enrol_get_users_courses (courses), mod_assign_get_assignments (homework and due dates), gradereport_overview_get_course_grades and gradereport_user_get_grades_table (results), core_calendar_get_calendar_events (tests and events).
4. Moodle, option 2: use the calendar export link (Calendar, Export calendar). It is a read-only iCal URL that shows deadlines and events without a password. Treat the URL as a secret.
5. Moodle, option 3: read the pages in a signed-in browser session. A parent account (Moodle "Parent" role linked to the child) is the correct setup if the school offers it. Do not use the child's login unless the parent and the school are fine with it.
6. Merge everything into one list: due this week, tests coming, new results, notices that need action, birthdays and events. Say which child each item is about, and "not sure" if it does not say.
7. Invites: when the parent forwards an invitation (WhatsApp, iMessage or email), read date, time, place and RSVP date. Propose a calendar event and a reminder to buy a gift one week before, and wait for approval before adding anything.
8. Two parents: if the household has two assistants, offer to tell the other parent's assistant about a shared commitment. The other assistant asks its own parent before adding it.

## Rules

- Read only. Never submit homework, post in a forum, message a teacher, accept an invitation, RSVP or pay anything without explicit approval. For Moodle, never call a function that saves, submits, enrols or sends.
- Passwords and tokens stay in a password manager or secret store. Never print them, put them in a note, a log or a shared document.
- Check the school's rules for apps and automated access first. If the school says no, stop and use notices and email instead.
- Keep children's names, photos and school names out of anything public. Do not copy photos of children anywhere.
- Say what was read and what was not. If a page, grade or file could not be read, list it under "Could not read" instead of guessing.
- Validation status: GrowApp reading is used in practice through the parent's own session. The Moodle read functions above were tested on the public Moodle demo site with a public demo account (a learner user), not on a real school. A real school can turn the mobile web service off or limit it, so test with one harmless read first.
- Do not claim a grade is final. Quote the number and the course exactly as shown.

## Output format

```
School (date)/- Due this week: child, subject, item, date/- Tests coming: child, subject, date/- New results: child, subject, result as shown/- Needs action: item, date/- Invites: event, date, place, RSVP by/- Suggested for the calendar: events and gift reminders, waiting for your OK/- Could not read: list
```
