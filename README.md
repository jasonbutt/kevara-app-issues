# Kevara — Public Issue Tracker

This is the public issue tracker for **[Kevara](https://kevara.app)** — a sovereign professional portfolio and Digital Embassy built natively on the [AT Protocol](https://atproto.com).

If something is broken, behaving oddly, or missing something obvious: you're in the right place. File an issue.

---

## What is Kevara?

Kevara is a **Portable Professional Trust Portfolio** — a premium profile layer built on top of the AT Protocol's decentralised identity stack.

The short version: your professional identity lives on your own Personal Data Server (PDS), not on our infrastructure. Your resume, endorsements, portfolio, and network connections are cryptographically signed records that belong to you, portable across any AT Protocol-compatible network — [Bluesky](https://bsky.app), [Gander](https://gander.social) 🇨🇦, [EuroSky](https://euro.social) 🇪🇺, and beyond.

Kevara provides the editorial-grade display layer, verification engine, and professional graph tools. You own the data. We just make it look exceptional.

**Kevara is currently in private beta.** Core features work. Edges are rough. That's expected.

---

## Before You File an Issue

A few quick checks:

- **Search first.** Your bug may already be tracked. Use the search bar above to scan open and closed issues before filing a new one.
- **One issue, one report.** Don't bundle multiple bugs into a single issue. They're harder to triage and easier to lose.
- **Check the known issues list.** The in-app Beta panel (Settings → Beta & Feedback) shows currently acknowledged issues pulled live from this repo.

---

## How to Submit a Bug Report

Use the **[Bug Report](.github/ISSUE_TEMPLATE/bug_report.md)** template when you open a new issue. It asks for the following:

| Field | What to include |
|---|---|
| **Category** | UI/Visual, Data/Profile, AT Protocol/PDS, Feed/Network, Settings, or Other |
| **Title** | Short, specific summary — "Profile banner not loading on EuroSky handles" beats "it's broken" |
| **What happened** | What you saw. Be specific about where in the app it occurred. |
| **Steps to reproduce** | The exact sequence that triggers the bug. If we can't reproduce it, we can't fix it. |
| **Expected outcome** | What *should* have happened. |
| **Your handle** | Optional, but helpful if we need to look at your specific PDS state. Your AT Protocol handle only — no passwords, no app passwords, no tokens. |

> **Note:** Bug reports submitted through the in-app form (Settings → Beta & Feedback) are automatically formatted with the correct labels and land here directly.

---

## Labels

| Label | Meaning |
|---|---|
| `beta-known` | Acknowledged known issue — shown in the in-app beta panel |
| `beta-report` | Submitted by a beta user via the in-app form |
| `ui` | Visual or layout issue |
| `data-profile` | Profile data, Sifa records, or PDS sync |
| `atproto-pds` | AT Protocol connection, DID resolution, or authentication |
| `feed-network` | Feed loading, Orbits, or network connectivity |
| `settings` | Settings panel behaviour |
| `other` | Anything that doesn't fit the above |

---

## What Happens After You File

- Issues are reviewed by the core team, typically within a few days during beta.
- Issues we can reproduce and confirm get labelled and prioritised into the sprint.
- Issues we can't reproduce will get a comment asking for more detail.
- Fixed issues are closed with a reference to the commit or release that resolves them.

We don't promise a fix timeline. We're a small team and this is a beta. But we read everything.

---

## What This Repo Is Not For

- **Feature requests** — We have a roadmap. Feature ideas are welcome but this tracker is for bugs only right now.
- **Support questions** — For help with setup, PDS connection, or account questions, reach out via [kevara.co](https://kevara.co) or find us on Bluesky at [@kevara.app](https://bsky.app/profile/kevara.app).
- **Security vulnerabilities** — Please do not file security issues publicly. Email **security@kevara.co** instead. We take responsible disclosure seriously.

---

## A Note on Privacy

Your AT Protocol handle is public information by design — it's a DID-anchored identity, not a login credential. If you include it in a bug report, it may be visible publicly in this repo.

**Never include:** app passwords, session tokens, PDS credentials, or any authentication material in issues. If you accidentally do, edit the issue immediately and contact us.

Kevara never stores your credentials on our servers. Your PDS is yours.

---

*Built on the [AT Protocol](https://atproto.com). Sovereign by design.*
# Kevara Public Issues

This is the public issue tracker for the Kevara beta programme.
