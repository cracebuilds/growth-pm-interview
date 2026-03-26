# MapleHR — Starter Repo

## Quick Start

Open `index.html` in your browser. That's it.

No server, no install, no build step. All data is embedded directly in the HTML file.

## What's Here

```
index.html          The full app — markup, styles (Tailwind CDN), and JavaScript in one file
data/
  customers.json    18 simulated customer accounts across plan tiers
  modules.json      Module definitions with setup steps and plan requirements
  usage_events.json 170 behavioral events (logins, feature clicks, exports, etc.)
```

### The App

A simulated MapleHR platform with:

- **Homepage** — company info, notification banners, quick-access widgets, and an activity feed showing recent events for the selected account
- **Modules page** — active modules with setup progress, available modules on the current plan, and add-ons
- **Account switcher** — dropdown in the top bar to switch between customer accounts. The whole app updates to reflect that customer's plan, modules, and activity

### The Data

**Customers** span three plan tiers (Essentials, Advantage, Premium) with varying company sizes, add-ons, setup progress, and health indicators. Some are thriving, some are stalled, some are showing expansion signals.

**Usage events** include logins, locked feature clicks, manual data exports, setup steps completed/skipped, first feature uses, support tickets, usage limit hits, and add-on page views.

**Modules** define what's available at each plan tier, what setup looks like, and which features are add-ons.

## Complexity

The app starts simple on purpose. You're welcome to keep it as vanilla HTML/JS, or use your AI tool to restructure it into whatever stack you prefer — React, Vue, Svelte, a full server setup, whatever feels right. The starting point is intentionally low-friction so you can spend your time on the problem, not the setup.
