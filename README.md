# Pulse — SaaS Business Dashboard

A production-quality SaaS analytics dashboard built with pure HTML, CSS, and Vanilla JavaScript. No frameworks. No bloat.

![Dashboard Preview](Preview.jpg)

**[Live Demo →](https://feyisara-o.github.io/Pulse-Dashboard/)**

---

## Overview

Pulse is a business intelligence dashboard that gives founders, freelancers, and small teams a clear view of their key metrics in one place. Built as a frontend UI demonstration with simulated data and a live AI insight engine.

---

## Features

- **4 KPI Metric Cards** — Revenue, Active Clients, Orders, and Expenses with animated counters and period-over-period change indicators
- **Revenue Overview Chart** — Line chart comparing revenue vs expenses across the selected time period
- **Revenue Split Chart** — Doughnut chart breaking down income by category
- **AI Business Pulse** — Powered by the Claude API. Reads live dashboard metrics and generates a single actionable business insight
- **Monthly Goal Tracker** — Animated progress bar showing progress toward a revenue target
- **Transactions Table** — Recent client payments with Paid, Pending, and Overdue status badges
- **CSV Export** — Download transaction data as a spreadsheet with one click
- **Date Range Filter** — Switch between Last 7, 30, and 90 day views. All metrics and charts update instantly
- **Dark / Light Mode** — Full theme switching persisted in localStorage
- **Fully Responsive** — Mobile-first design. Works on all screen sizes

---

## Tech Stack

| Technology | Purpose |
|------------|---------|
| HTML5 | Semantic page structure |
| CSS3 | Mobile-first layout, theming, animations |
| Vanilla JavaScript | Interactivity, data rendering, API integration |
| Chart.js | Line and doughnut charts |
| Claude API | AI-powered business insights |

---

## Project Structure

```
pulse-dashboard/
├── index.html
├── css/
│   └── style.css
└── js/
    └── app.js
```

---

## Running Locally

No build tools or dependencies required.

```bash
git clone https://github.com/your-username/pulse-dashboard.git
cd pulse-dashboard
open index.html
```

Or simply open `index.html` in any browser.

---

## Design Decisions

**No framework** — Vanilla JS was the right choice for a project of this scope. It keeps the bundle lean, demonstrates core fundamentals, and produces code that is straightforward to read and maintain.

**Mobile-first CSS** — Base styles are written for mobile and scaled up with `min-width` media queries. This is the correct approach for modern web development where the majority of traffic is on mobile devices.

**CDN dependencies** — Chart.js and Google Fonts are loaded from CDN. Both are globally cached, production-grade, and faster than self-hosting for a project of this type.

**Simulated data** — The dashboard uses a hardcoded data layer. In a production product this would be replaced with API calls to a backend database.

---

## Author

**Feyisara O.** — Frontend Developer
[Portfolio](https://your-portfolio-url.com) · [LinkedIn](https://www.linkedin.com/in/mofeyisara-okunola-73121b277?trk=contact-info) · [Upwork](https://upwork.com/your-profile)
