# Tenure

A lifetime record for every home appliance.** Tenure gives each appliance a digital passport that holds its brand, serial number, warranty, repair history and moves, so owners, families and technicians share one record.

Built by Team Xerxes for the NIT Rourkela Innovathon.

- Live prototype: https://tenure1.netlify.app
- Repository: https://github.com/xerxes-2026/Tenure-

# What it does

- Setup in three steps: pick a brand and type from 43 brands with logos, add a label photo, then confirm the serial, purchase date and place.
- Passports: repair log, location log, warranty status and recurring-fault flags.
- Sign-in: four verification methods (mobile code, email code, password with a second step, and fingerprint or face), in the style of common apps.
- Dashboard: filters for all appliances, warranty, attention, type and room, with spend charts, repairs by part and a warranty timeline.
- Offers: request a warranty check, pickup or resale offer for one appliance or all of them. Duplicates are skipped.
- Help: two support lines, topic chips and a help assistant.

## What is not built yet

- AI reading of real label photos (the prototype uses example results)
- Server accounts, real SMS and email sign-in
- Payments and pickup fees (the fee is shown as to be confirmed)

# Run it locally

No install is needed.

1. Clone or download this repository.
2. Keep `setup-flow.html` and the `img/` folder together.
3. Open `setup-flow.html` in a modern browser.

Passports are saved in the browser only (`localStorage`). Clearing site data removes them.

# Project layout

```
setup-flow.html        The whole prototype: HTML, CSS and JavaScript in one file
img/brands/            Brand logos (JPEG)
img/fault-*.jpg        Sample fault photos
img/tenure-logo.svg    Tenure logo
img/xerxes-logo.png    Team logo
```

# Notes

- Model numbers, prices and offers in the prototype are examples.
- Brand names and logos belong to their owners. They are shown only to identify the brands.
- The sign-in demo code is shown on the sign-in card. Nothing is sent to a phone or an email address.

# Team

- Gourav Bhoi (Team Leader)
- Jeevan Kumar Majhi
- Zails XaXa
- Megha Mayuri Sahoo
- Swatipragnya Biswal
- Kirtiswarupa Sahoo

# Licence

To be decided by the team.

---
© 2026 Tenure. All rights reserved.
