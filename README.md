# Universal Student Academic Manager

An open-source, configurable student record application for schools and educators. Original project by Moses Decontee Weah. Licensed under the MIT License.

## Included
- Student registration and student register pagination (50 or 100 per page).
- Search across the register and filter by class/grade and academic year.
- Attendance, marks/results, classroom activities, report cards and class promotion.
- CSV exports and JSON backup/restore.
- Progressive Web App (PWA) manifest, service worker and Android launcher icons (192px and 512px).

## Install as a phone icon
The app must be published on an HTTPS website. Open that website in Chrome on Android and select **Install App**, or use Chrome menu → **Install app / Add to Home screen**. See `INSTALL.txt`. Opening the HTML file from Downloads is not enough for full PWA installation. This is a PWA, not an APK.

## Important data and deployment status
The included browser edition currently stores records in local browser storage on the current device. It is not yet connected to a central online database and has no secure login or multi-user role enforcement. The SQL schema in `database/schema.sql` is a design reference, not a live database. Do not use this edition as the authoritative shared record system for 5,000+ students until a PostgreSQL backend, authentication, role-based access control, server-side pagination, backups and HTTPS deployment are implemented and tested.

## Local test
You may open `index.html` in a modern browser to test the offline starter edition. For PWA installation and service-worker behavior, serve the package from HTTPS or localhost.

## License
MIT. See `LICENSE`.
