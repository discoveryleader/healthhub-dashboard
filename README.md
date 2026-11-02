# HealthHub Dashboard

A family health-records dashboard for parents and guardians managing health information for more than one child. Built from the HealthHub Dashboard v2 design.

**Live features**
- Child selector: Both kids / Evan / Jeffrey
- Overdue vaccine alert, upcoming appointments, incomplete records
- Allergies, medications and conditions summary
- Search that filters recent records
- Notifications popover
- Smart Add → Vaccine record flow (scan with AI prefill, or manual entry); saving the overdue DTaP clears the alert

## Run it

No build step. Open `index.html` in a browser:

```bash
open index.html
```

Or serve it locally:

```bash
python3 -m http.server 8790
```

All data is hardcoded sample data.
