# Om Sai Tours and Travels — Project Summary

## Overview
An Android-focused tour discovery and booking project with a mobile client, REST API, MongoDB data layer, and browser-based admin console.

## Technology stack
- Expo / React Native with TypeScript
- Node.js and Express REST API
- MongoDB with Mongoose
- Browser-based HTML/CSS/JavaScript admin console
- CSV templates for administrative data import/export

## Intended capabilities
- Browse tour packages and search destinations
- Customer signup/login and profile
- Wishlist and booking history
- Server-side validation of traveller counts (1–20) and booking totals
- Booking status and cancellation workflow
- Support enquiries and admin management/report export

## Project structure recorded in the source archive
- `mobile/` — Expo app
- `backend/` — API, data models, seed script and a booking-validation test
- `admin/` — browser-based admin console
- `docs/` — API, setup, test cases, project report and architecture source
- `excel-templates/` — CSV templates for project data

## Status and limitations
The project documentation identifies online payment processing, secure email password reset, push notifications, full map integration, complete translation, and production deployment as items requiring further configuration or testing. Test cases in the report are expected outcomes, not proof of passing tests.

## Security and demonstration guidance
Use demo data for academic demonstrations. Before real-world use, verify access control, HTTPS, database backup/recovery, secret management, and end-to-end behaviour. Keep real credentials out of source control.

## Supporting documentation
See the [portfolio artifact index](../../docs/portfolio/PROJECT_ARTIFACTS.md). The full source archive and PDF reports exist in the project workspace/library; binary files are not represented by this Markdown summary.
