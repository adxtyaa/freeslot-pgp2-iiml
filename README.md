# FreeSlot

FreeSlot is a single-file static app for finding overlapping free time across IIM Lucknow Term IV timetables.

Built with Codex.

## Usage metrics

The app records anonymous usage counters (unique users, daily active users, visits, page loads, lookups run, time on page) as plain increments in [abacus.jasoncameron.dev](https://abacus.jasoncameron.dev) — no personal data is collected. Day buckets use IST. Tracking only runs on the deployed `github.io` site, so local development does not pollute the numbers.

## Course phase labels

Course badges are populated from the original timetable's `mid` and section fields. When a class has `PRE-MID` or `POST-MID` data, the app shows the section label, such as `PRE-B` or `POST-A`, next to the course code.
