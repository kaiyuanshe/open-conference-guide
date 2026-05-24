---
name: open-conference-guide
description: Plan and execute open-source/community conferences using the Open Conference Guide knowledge base. Use when a user asks to design a conference plan, organize a meetup, run an open-source annual conference, create a conference timeline, recruit speakers, build a sponsorship plan, choose a venue, manage volunteers, prepare onsite runbooks, create budgets, write CFPs or speaker invitations, produce post-event surveys, or review conference execution risks.
---

# Open Conference Guide

Use this skill to help users plan and execute open-source, technical, nonprofit, or community conferences. Treat the repository as the knowledge base. Load only the chapters and templates needed for the user's current planning stage.

## Core Workflow

1. Clarify the conference shape:
   - conference goal and theme
   - expected size
   - city or online/offline format
   - date or target month
   - audience
   - budget constraints
   - paid/free ticket model
   - volunteer capacity
2. Classify the event:
   - use `conf_classify.md` for Meetup, regional, national, or international complexity.
   - use `subject.md` to turn the goal into a theme and content direction.
3. Create the minimum viable plan first:
   - read the `## 最小可执行版本` section in each relevant chapter.
   - avoid overbuilding a small event with large-conference processes.
4. Build the execution plan:
   - use `time_phase.md` for timeline.
   - use `organization.md` and `people_classify.md` for roles.
   - use domain chapters for the user’s active workstream.
5. Produce reusable artifacts:
   - use files in `templates/` whenever the user asks for tables, copy, checklists, or runbooks.
   - adapt templates to the user's event details instead of returning generic placeholders.
6. Check risks before finalizing:
   - summarize key risks by workstream.
   - identify missing owners, dates, dependencies, and decision points.
   - recommend the smallest next actions for the coming week.

## Reference Map

Start with `SUMMARY.md` for the full table of contents.

### Foundation

- `conf_classify.md`: decide event complexity and how much process is necessary.
- `subject.md`: define goal, theme, audience, and outcome.
- `organization.md`: set up the organizing committee and meeting cadence.
- `people_classify.md`: identify speakers, audience, volunteers, sponsors, vendors, partners, media, and venue staff.

### Preparation

- `time_phase.md`: create a T-4 month to post-event timeline.
- `sponsor.md`: design sponsorship levels, benefits, contracts, and payment tracking.
- `call_for_speaker.md`: invite speakers, write CFPs, review proposals, confirm schedules.
- `venue.md`: choose city, date, venue, routes, equipment, contracts, and backup plans.
- `design.md`: manage visual identity and event materials.
- `publicity.md`: plan promotion, media, community channels, and post-event coverage.
- `sales_ticket.md`: design ticketing, registration, gifting, and onsite check-in.
- `travel.md`: manage speaker and guest travel.
- `catering.md`: plan meals, tea breaks, and special dietary needs.
- `content.md`: manage copy, documents, scripts, and versioned content.
- `material.md`: plan badges, signage, gifts, printed materials, and logistics.
- `tools.md`: select communication, project management, registration, analytics, and onsite tools.
- `producer_system.md`: assign content owners for tracks, forums, workshops, or side events.

### Onsite and Follow-Up

- `onsite.md`: create the onsite execution plan.
- `volunteer.md`: recruit, train, schedule, and thank volunteers.
- `finance_legal.md`: manage budgets, contracts, invoices, reimbursements, and authorization risks.
- `questionnaire.md`: design pre-event and post-event surveys.
- `post_materials.md`: archive photos, videos, slides, reports, and public links.
- `relationship.md`: maintain speaker, sponsor, partner, volunteer, media, and attendee relationships.
- `counting_revenue.md`: evaluate post-event value beyond money.

## Templates

Use `templates/README.md` as the template index.

Common template choices:

- timeline: `templates/master_schedule.md`
- sponsorship: `templates/sponsor_benefits.md`
- CFP announcement: `templates/cfp_announcement.md`
- speaker invitation: `templates/speaker_invitation.md`
- volunteer roster: `templates/volunteer_roster.md`
- onsite runbook: `templates/onsite_runbook.md`
- materials checklist: `templates/materials_checklist.md`
- budget: `templates/budget.md`
- post-event survey: `templates/post_event_survey.md`
- post-event review: `templates/post_event_review.md`

## Response Patterns

When the user asks for a conference plan, return:

1. assumptions
2. event classification
3. minimum viable version
4. timeline
5. team roles
6. workstream plan
7. templates to use
8. immediate next actions

When the user asks for a specific artifact, return the artifact directly and tailor it to the event. If critical details are missing, make conservative assumptions and list them at the top.

When the user asks for a review, inspect the plan against:

1. missing owner
2. missing deadline
3. budget risk
4. venue or equipment risk
5. speaker risk
6. sponsor delivery risk
7. volunteer capacity risk
8. onsite execution risk
9. post-event follow-up gap

## Output Style

Prefer practical tables, checklists, and dated action plans. Keep advice specific to the user's event size. Separate general guidance from examples labeled `案例参考`. For small community events, lead with the minimum viable version instead of a full large-conference process.
