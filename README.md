# The System

A complete self-knowledge and productivity system. Built for when life feels unmanageable.

Web app · Android · Windows · Pen & Paper

---

## What it is

The System is a free, open source tool that accompanies the [Life Improvement 101](https://disputant186.substack.com) essay series. It is not a to-do list. It is not a habit tracker. It is a structured system of self-knowledge that replaces the scrolling habit with something that actually helps.

Every tool in it is built around one problem — the amnesia problem. The gap between understanding something about yourself and actually living it.

---

## Downloads

| Platform | Link |
|---|---|
| Web app (works on everything) | [babuanon.github.io/thesystem](https://babuanon.github.io/thesystem) |
| Android APK | [Releases](https://github.com/BabuAnon/thesystem/releases) |
| Windows installer | [Releases](https://github.com/BabuAnon/thesystem/releases) |
| Printable PDF | [the-system-printable.pdf](https://babuanon.github.io/thesystem/the-system-printable.pdf) |

No account. No login. No data leaves your device.

---

## The eight tools

**Today** — Your daily entry point. Five steps, two minutes. Open this every time before anything else. Read your default code, diagnose where you are, drop data about yourself, pick one repair action. Then close it and get to work.

**Who I Am** — The living document of your operating code. Default rules you read every twelve hours. Destructive patterns you have cracked. Preventive measures for each one. Raw observations that graduate into permanent knowledge over time.

**Show Up** — Seven daily goals. Vague enough to always be doable. Weekly grid, monthly history, yearly summary. Start at 50% hit rate. The name of the game is daily, not maximum.

**Conquer** — Single-goal execution. One objective, one countdown, tasks defined the day before. The answer cannot be left blank. Ever.

**Deadlines** — The spine of everything. Set the deadline first, then the plan. Colour coded by urgency. Review every Sunday.

**Solve** — Three phases per problem: Diagnose (the Sherlock framework, three filters, agency fork), Solution (replacement behaviour, cascading benefit, life without the problem), Resolve (decision, one action, learning extracted to Who I Am).

**Get Up** — The recovery script. Opened when you fall, not when you are calm enough to analyse. De-escalation first. Five steps. Clears every time you open it — always fresh.

**Why** — The fuel. Your altar, your vision wall, your goals, the two questions. Open when you feel lost. It should slap you back to your senses.

---

## How the tools connect

The sections are not independent. Data flows between them.

- **Today → Who I Am** — observations pushed directly to Data Processing
- **Who I Am → Today** — Default Code previewed every time you open Today
- **Solve → Who I Am** — learnings extracted to Daily Rehearsal on resolution
- **Get Up → Who I Am** — contingency plan pushed to Preventive Measures
- **Deadlines → Everything** — set them first, let everything else follow
- **Show Up → Sunday Review** — live weekly percentage pulled automatically
- **Why → Get Up** — vision wall images appear during recovery

---

## Sunday Review

The heartbeat of the system. Every Sunday, two to three hours. Review your Show Up percentage, what worked, what broke the chain, the three most important things next week, and your Why. Non-negotiable.

The Sunday Review button is in the top header on mobile and in the sidebar on desktop.

---

## Themes

Three themes — Dark, Paper, and Dim. Switch from the header on mobile or the sidebar on desktop. Preference saves automatically.

---

## Data and privacy

All data is stored in your browser's localStorage. Nothing is sent to any server. Nothing is tracked. No account required.

**Export** your data regularly as a JSON backup. **Import** it on any other device to restore everything. Export and Import are in the ⋯ menu on mobile and in the sidebar on desktop.

---

## Pen and paper version

A complete printable PDF version of the system is available for people who prefer to work on paper. All eighteen pages — instructions, every tool as a fillable template, the Sunday Review, a print guide on the cover page.

Download: [the-system-printable.pdf](https://babuanon.github.io/thesystem/the-system-printable.pdf)

---

## Building from source

The entire app is a single HTML file — `index.html`. No build step, no dependencies, no framework.

```bash
git clone https://github.com/BabuAnon/thesystem
cd thesystem
# Open index.html in any browser
```

### Android (Capacitor)

```bash
npm install @capacitor/core @capacitor/android
npx cap add android
npx cap sync
cd android
.\gradlew assembleDebug
```

### Windows (Electron)

```bash
npm install electron electron-builder --save-dev
npx electron .          # development
npx electron-builder    # build installer
```

---

## The essay series

The System accompanies a six-part essay series on self-knowledge, motivation, and practical philosophy.

[Life Improvement 101 — disputant186.substack.com](https://disputant186.substack.com)

Parts 1 through 6 cover the mental models behind every tool in this system. Reading the essays is not required to use the app, but it will change how you use it.

---

## License

MIT. Free to use, modify, and distribute.

---

*Built by [Sharma](https://disputant186.substack.com). Three years of building, breaking, and rebuilding — distilled into one tool.*
