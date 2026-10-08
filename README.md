# Eva’s Budget

A small personal budgeting app: spending and income in HKD and RMB, daily/weekly/monthly category limits, savings goals and regular income.

- Runs as an installable web app (add it to your iPhone home screen from Safari).
- Data lives in a private Firebase (Firestore) database behind Google sign-in. Nothing personal is stored in this repository.
- Exchange rates come from the European Central Bank (via Frankfurter), with ExchangeRate-API as a fallback.

When you change the app files, bump `VERSION` in `sw.js` so installed copies pick up the update.
