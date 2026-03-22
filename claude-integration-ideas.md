# Claude Integration Ideas

A running list of ideas for integrating Claude into projects and workflows.

---

## Ideas

<!-- Add your ideas below. Format: ### Idea Title -->

### Daily Routine Briefing Artifact

An interactive artifact with quick-action buttons to get an AI-generated briefing of daily information at a glance.

**Buttons / Actions:**
- **Calendar Briefing** — Summarize today's calendar events
- **Email Briefing** — Summarize prior day's emails
- **Text/Messages Briefing** — Summarize prior day's text messages
- **Daily Overview** — Combined summary of all of the above in one briefing

**Notes:**
- Buttons should each trigger a Claude prompt that fetches and summarizes the relevant data
- Could integrate with Google Calendar, Gmail, and a messaging API
- Output should be a clean, scannable briefing format

### Automatic Call Scheduling

A way for Claude to autonomously make phone calls to schedule appointments on your behalf.

**Capabilities to explore:**
- Detect when an appointment needs to be scheduled (from email, calendar gaps, or user prompt)
- Place outbound calls using a voice/telephony API (e.g. Twilio, Bland.ai)
- Conduct a natural conversation to find a mutually available time
- Confirm and add the appointment directly to the calendar

**Notes:**
- Could be triggered manually ("schedule a haircut for next week") or automatically based on context
- Needs a voice AI layer for real-time call conversation
- Should send a confirmation summary after the call completes

---

## Completed / Implemented

<!-- Move ideas here once they've been built -->

