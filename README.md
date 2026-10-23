# LeadLane

**The personal productivity board for player-coaches: tech leads and engineering managers who still ship code.**

Prioritise your work, keep context on your team, capture what you're learning, and log your wins for review season. It all lives in one HTML file, and your data never leaves your machine.

### 👉 [Try it live](https://mithunmanohar.github.io/lead-lane/)

No sign-up. Anything you enter stays in your own browser. Want to see it with data? Download [`demo/leadlane-demo-data.json`](demo/leadlane-demo-data.json) and load it via **Settings → Import JSON/YAML**.

<!-- Add a screenshot or GIF here: ![LeadLane board](docs/screenshot.png) -->

---

## Built out of frustration

You write code. You also run a team. Your day is split between pull requests and people: priorities, deliverables, 1:1s, hiring, incidents, and a review cycle that always arrives too soon.

Jira tracks your *team's* work. Nothing tracks *yours*. So the important things end up scattered across sticky notes, Slack messages to yourself and a doc you forgot to update. Meanwhile, the technical work you actually enjoy keeps getting pushed to tomorrow.

LeadLane is the board I built to fix that for myself. It holds one view of everything a player-coach juggles, so you can stop managing the chaos and **spend your time on what matters.**

---

## What's inside

### ✅ Tasks: a kanban that respects your priorities
- **Sections** for each area you own (e.g. *Platform Reliability*, *Hiring*, *Side Project*)
- Five columns: **Backlog → To do → In progress → Tracking → Done**
- **P1 / P2 / P3 lanes** inside each column, so the urgent work stays at the top
- Drag and drop, deadlines with labels like *"today"* and *"2d late"*, search, filters and archiving
- A **Status dashboard** showing what you created, started and finished, month by month

### 👥 My Team: the context good managers remember
- Role, team, birthday and start date for every person
- A dated **log per person** for 1:1 notes, feedback and things to follow up on
- **Role history** recorded automatically when someone's title changes
- **Birthday reminders** on your board three days ahead

### 💡 Insights: your personal leadership playbook
- Capture principles, observations, lessons learned and decision heuristics
- Drag to reorder so the ones that matter most stay on top

### 🏆 Milestones: evidence for review season
- Log achievements with a category and supporting evidence (metrics, links, feedback)
- **Copy review draft** turns them into a bullet list you can paste into a self-assessment

### 🌗 And more
- Dark and light themes
- Print-friendly layout
- Export and import as JSON or YAML

---

## Why local-first?

Your 1:1 notes, performance context and team birthdays are **sensitive**. They don't belong in yet another SaaS tool.

- 🔒 **Private by design**: no account, no server, no tracking. Your data stays in your browser and in a file you control.
- ⚡ **Zero setup**: no install, no build step, no dependencies. Open the file and start.
- 🧳 **Portable**: one HTML file and one JSON file. Copy them anywhere.
- 🕰️ **Built to last**: no service to shut down and no subscription to cancel.

---

## Get started in 2 minutes

### 1. Make a home for LeadLane

Create a folder in a safe, convenient place, for example:

```
~/Documents/LeadLane
```

> 💡 **Tip:** choose a folder that's synced by iCloud Drive, Dropbox, OneDrive or Google Drive. Your data file is then backed up off your machine automatically.

### 2. Put `leadlane.html` in that folder

Download [`leadlane.html`](leadlane.html) and save it into the folder you just made.

### 3. Open it in Chrome, Edge or Brave

Double-click the file or drag it into a browser window. Bookmark it so it's one click away.

### 4. Turn on auto-save to a JSON file

Click **Set up file sync** in the banner (or go to **Settings → Pick Folder for Auto-Save**), then choose **the same folder**. Allow LeadLane to edit files there. If the browser asks, pick **"Allow on every visit."**

That's it. A file called **`leadlane-data.json`** now sits next to `leadlane.html` and updates on every change:

```
LeadLane/
├── leadlane.html        ← the app
└── leadlane-data.json   ← your data, saved automatically
```

---

## Keeping your data safe

LeadLane keeps your data in two places:

| Where | What it's for |
|---|---|
| **Your browser's storage** | The working copy. Fast and always there, with a built-in backup copy. |
| **`leadlane-data.json`** in your folder | Your safety net. A readable file you can see in Finder or Explorer, back up, and move. |

A few good habits:

- **Clearing your browser data erases the browser copy.** The JSON file is what saves you. Keep auto-save on.
- **Moving to a new machine?** Copy your LeadLane folder across, open `leadlane.html`, and use **Settings → Import JSON/YAML** to load `leadlane-data.json`.
- **Using Safari or Firefox?** Those browsers don't support folder auto-save. Use **Settings → Export JSON** regularly instead.

---

## Browser support

| Browser | Board & data | Auto-save to JSON file |
|---|:---:|:---:|
| Chrome, Edge, Brave (and other Chromium browsers) | ✅ | ✅ |
| Safari, Firefox | ✅ | Manual export only |

---

## FAQ

**Is this a Jira replacement?**
No. Jira runs your team's work. LeadLane runs *yours*: the personal layer of priorities, people context and career evidence that team tools don't cover.

**Does anything get sent to a server?**
No. The only external request is for the Inter font from Google Fonts. Your data never leaves your machine.

**Can I customise it?**
Yes. It's one readable HTML file with no build step, so you can open it in an editor and make it your own.

---

## Contributing

Ideas, bug reports and pull requests are welcome. Please open an issue first for anything big. LeadLane is deliberately small and focused, and it will stay a single file.

---

<p align="center"><b>LeadLane</b> · for the ones who lead <i>and</i> build.</p>
