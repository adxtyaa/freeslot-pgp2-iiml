# FreeSlot

FreeSlot is a single-file static app for finding overlapping free time across IIM Lucknow Term IV timetables.

Built with Codex.

## Usage dashboard

Open `dashboard.html` (e.g. `https://adxtyaa.github.io/freeslot-pgp2-iiml/dashboard.html`) to see usage metrics: all-time unique users, daily active users (DAU), page loads, and free-slot lookups ("jobs run") per day.

Counters are anonymous increments stored in [abacus.jasoncameron.dev](https://abacus.jasoncameron.dev) under the `freeslot-pgp2-iiml` namespace — no personal data is collected. Day buckets use IST. Tracking only runs on the deployed `github.io` site, so local development does not pollute the numbers.

## Course phase labels

Course badges are populated from the original timetable's `mid` and section fields. When a class has `PRE-MID` or `POST-MID` data, the app shows the section label, such as `PRE-B` or `POST-A`, next to the course code.
