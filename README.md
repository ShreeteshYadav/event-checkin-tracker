# event-checkin-tracker

# Technical Event Registration & Check-in Tracker

A lightweight, zero-dependency web application built to manage participant registrations, live event check-ins, and real-time attendance and drop-off metrics.

## Features
- **Live Metrics Dashboard:** Automatically calculates total registrations, checked-in count, attendance percentage, and drop-off rate.
- **Instant Check-in & Timestamping:** Ticking a participant's checkbox marks them as present, highlights their row, and stamps their exact arrival time.
- **Search & Status Filtering:** Filter attendees by name, email, participant ID, or check-in status at the registration desk.
- **Walk-in Registration:** Add new registrants on the fly.
- **Local Persistence & CSV Export:** Saves state automatically in browser `localStorage` and exports the updated attendance log to CSV with one click.

## Tech Stack
- HTML5, CSS3, Vanilla JavaScript (`localStorage` & Blob CSV export)

## How to Use
1. Open the live web app link (hosted via GitHub Pages).
2. **Add Registrants:** Enter a participant's full name, email, and category in the top bar and click **+ Add Registrant**.
3. **Check In Attendees:** Use the search bar to locate a participant by ID, name, or email, and tick their **Checked In** checkbox. The dashboard metrics and arrival timestamp will update immediately.
4. **Export Data:** Click **Export CSV** at any time to download the complete attendance log.
