<p align="center">
  <a href="https://www.codemetal.ai/forge-hackathon">
    <img src="https://www.codemetal.ai/forge-hackathon/cm-logo-horizontal.svg" alt="Code Metal" width="320">
  </a>
</p>

<p align="center">
  <img src="https://github.com/user-attachments/assets/1fa604f6-68f7-4ce4-b424-2d680a90248f" alt="Code Metal Forge anvil animation" width="320">
</p>

<h1 align="center">Code Metal Forge Hackathon 2026</h1>
<h3 align="center">Operation Lost and Found — Search &amp; Rescue in Dangerous Environments</h3>

<p align="center">
  <img src="https://www.codemetal.ai/_next/image?url=%2Fforge-hackathon%2Fussocom.png&w=128&q=75" alt="United States Special Operations Command seal" width="64"><br>
  <b>Nov 6–8, 2026</b> · <b>$18,000 prize pool</b><br>
  Sponsored by U.S. Special Operations Command (USSOCOM) · Hosted &amp; produced by Code Metal
</p>

<p align="center">
  <a href="https://www.codemetal.ai/forge-hackathon">Event Site</a> ·
  <a href="mailto:forge@codemetal.ai">forge@codemetal.ai</a>
</p>

---

Welcome! This is the official GitHub organization for the **[Code Metal Forge Hackathon 2026](https://www.codemetal.ai/forge-hackathon)**. Every participating team builds, versions, and submits its work here.

## Contents

- [Rules for Using This GitHub Org](#-rules-for-using-this-github-org)
- [Key Times](#-key-times)
- [The Mission](#-the-mission)
- [The Challenge](#-the-challenge)
- [Judging & Prizes](#-judging--prizes)
- [Hardware & Mentorship](#-hardware--mentorship)
- [Agenda](#-agenda)
- [Teams](#-teams)
- [FAQ](#-faq)
- [Contact](#-contact)

---

## 📜 Rules for Using This GitHub Org

> [!WARNING]
> **PLACEHOLDER — TO BE UPDATED.** The rules below are a working draft and are subject to change by the organizers before and during the event. Check back for the final version.

**Access & accounts**

1. Every participant must use a personal GitHub account and accept the org invitation before the build starts. Two-factor authentication (2FA) is required.
2. Org membership is granted for the duration of the event only. Access may be reduced or removed after judging concludes.

**Repositories**

3. One repository per team, created by the organizers (or by the team on request). Use the naming convention: `team-<number>-<short-name>` (e.g., `team-07-beacon`).
4. Only commit to your own team's repository. Do not open issues, PRs, forks, or otherwise interfere with another team's repo.
5. Repositories remain **private** during the build. Visibility after the event will be decided by the organizers in consultation with teams.
6. Each repo must contain a `README.md` describing the project, team members, setup/build steps, hardware used, and how to run the demo.

**Submissions**

7. **Submissions close Sunday, Nov 8 at 12:00 PM EST.** The last commit on the default branch at or before the cutoff is your submission. Commits after the cutoff will not be considered for judging.
8. Tag your final submission commit: `git tag submission && git push origin submission`.
9. Only work produced during the event may be submitted. Pre-existing open-source libraries, frameworks, and SDKs are fine — credit them in your README.

**Security & data handling**

10. **Never commit secrets** — API keys, tokens, passwords, private keys, or credentials. Use environment variables or a `.env` file listed in `.gitignore`. Leaked secrets will be revoked and the repo may be locked until cleaned.
11. **No classified, Controlled Unclassified Information (CUI), ITAR/export-controlled, or otherwise sensitive government data** may be committed to this org. If you are unsure whether something qualifies, ask an organizer before committing.
12. No personal data about real individuals (location traces, images, audio, etc.) beyond synthetic or consented test data.
13. Large binaries (datasets, model weights, firmware images, SDR captures) should use Git LFS or be linked externally rather than committed directly.

**Conduct & IP**

14. All participants are expected to follow the event code of conduct in all repos, issues, and discussions.
15. Intellectual property and licensing terms for submitted work are governed by the event participation agreement. Add a `LICENSE` file only if instructed by the organizers.
16. Organizers and judges may be granted read access to all team repos for review.

---

## ⏱️ Key Times

All times Eastern (EST).

| When | What |
|---|---|
| **Fri, Nov 6 · 5:00 PM** | Reception opens — check-in for VIPs, speakers & judges |
| **Sat, Nov 7 · 10:00 AM** | Hackathon begins — hard start on the build floor |
| **Sun, Nov 8 · 12:00 PM** | Submissions close — hard cutoff, live demos follow |

---

## 🎯 The Mission

**Operation Lost and Found.** When infrastructure fails, responders need a faster way to reach people who are cut off.

Picture a hiker lost in the backcountry, or a town evacuating ahead of a wildfire. Time is critical, and the tools responders rely on have to keep working in exactly the conditions most likely to break them. These are degraded, asymmetric environments — inaccessible or disconnected from normal infrastructure — where RF communications, sensing, and resilient information sharing determine the outcome.

**Focus areas:** RF Communications · Sensing · Resilient Info-Sharing · Edge Compute

The goal: turn uncertainty into a faster, safer path home.

---

## 🧭 The Challenge

**How can responders locate, identify, and rescue isolated people in dangerous, inaccessible, or rapidly changing environments?**

| | Objective | Description |
|---|---|---|
| **OBJ.01** | **Locate Isolated People** | Establish position quickly with no reliable GPS, cellular network, or fixed communications. |
| **OBJ.02** | **Detect Life & Hazards** | Search for heat, motion, and sound signatures; identify emerging hazards such as gas or structural risk. |
| **OBJ.03** | **Map Changing Conditions** | Keep a shared operating picture current as fire, weather, water, and terrain evolve. |
| **OBJ.04** | **Deliver Critical Information** | Get actionable information to responders over degraded or congested communications channels. |

---

## 🏆 Judging & Prizes

Working prototypes are judged by experts from defense, emergency response, academia, and deep tech.

**Evaluation criteria**

- **Mission relevance**
- **A working live demonstration**
- **Deployability**

**$18,000 prize pool**

| Place | Prize |
|---|---|
| 🥇 First (Grand Prize) | $10,000 |
| 🥈 Second (Runner-Up) | $5,000 |
| 🥉 Third | $3,000 |

The winning team also earns a meeting with Code Metal leadership, and university participants on the winning team receive an automatic internship interview.

**Every hacker gets:** a limited-edition T-shirt, water bottle, sling backpack, and challenge coin.

---

## 🛠️ Hardware & Mentorship

**Resources available to teams**

- Embedded computing & microcontroller platforms
- Software-defined radio & wireless systems
- Imaging, thermal & environmental sensors
- Electronics, debugging & test equipment

**Mentorship:** Specialists from defense, deep tech, and Code Metal are on the floor and embedded with teams throughout the build. Special Operations Forces operators provide mission context and rapid user feedback; technical mentors help with sensing, communications, autonomy, embedded, and ML challenges.

---

## 🗓️ Agenda

### Day 1 — Fri, Nov 6 · Reception
- **17:00–20:00** — Opening reception, welcome from Code Metal and USSOCOM, and a fireside chat.

### Day 2 — Sat, Nov 7 · The Build
- **08:00** — Check-in, badges, team stations, challenge brief, and opening remarks. Team-matching for solo participants.
- **10:00** — Build starts. Mentor office hours all day; meals on the floor.
- **Overnight** — Venue stays open with on-call technical and security support.

### Day 3 — Sun, Nov 8 · Judging
- **Morning** — Final integration; lock in your submission.
- **12:00** — Submissions close. Teams present live demos to judges.
- **16:30** — Deliberation, winners announced, closing ceremony.

---

## 👥 Teams

- Teams have **up to four members**.
- Solo participants are welcome and will be matched with a team at Saturday morning's team-building session.
- Participants include university teams and individual technologists building alongside Special Operations Forces operators, first responders, academics, and deep-tech innovators.

<!-- Organizers: add the team roster / repo index here once teams are finalized.
| Team | Repo | Members |
|---|---|---|
| Team 01 | [team-01-name](../team-01-name) | ... |
-->

---

## ❓ FAQ

**Will food be provided?**
Yes — breakfast, lunch, dinner, snacks, and drinks from Friday's reception through Sunday's awards, served right on the build floor.

**Do I need a team?**
No. See [Teams](#-teams).

---

## 📬 Contact

- **Email:** [forge@codemetal.ai](mailto:forge@codemetal.ai)
- **Event site:** [codemetal.ai/forge-hackathon](https://www.codemetal.ai/forge-hackathon)
- **Code Metal:** [codemetal.ai](https://www.codemetal.ai/)

<p align="center"><sub>Sponsored by USSOCOM · Hosted &amp; produced by Code Metal · © 2026 Code Metal</sub></p>
