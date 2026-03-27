---
{"dg-publish": true, "permalink": "/resources/wiki/mycroquet/home/", "tags": ["mycroquet", "wiki", "platform"], "dg-home-link": true, "dg-pass-frontmatter": true, "dg-show-backlinks": true, "dg-show-inline-title": true, "dg-show-file-tree": true, "dg-enable-search": true, "dg-show-toc": true, "dg-link-preview": true, "dg-show-tags": true}
---


# MyCroquet

The CAQ player and club management platform. Live at [my.croquetwade.com](https://my.croquetwade.com).

---

## What it is

MyCroquet is a modular platform built for Queensland croquet — players, clubs, and membership officers all in one place. Built on PocketBase (database) and Next.js (front end), running on the CAQ Coolify VPS.

It replaces the patchwork of spreadsheets, Airtable bases, and one-off systems that clubs have been using.

---

## Current modules

| Module | Status | Who it's for |
|--------|--------|-------------|
| **Player Profile** | Live | Players — name, handicap, club, contact |
| **Handicap System** | Live | Players and captains — GC and AC handicaps |
| **Come & Try** | In progress | Membership officers — prospect pipeline, session tracking |

---

## Accessing MyCroquet

**URL:** [my.croquetwade.com](https://my.croquetwade.com)

Access is managed by capability tags — your account permissions determine what you can see. Current capabilities:
- `come_and_try` — prospect pipeline and session management
- `membership_officer` — full member records
- `captain` — club team and handicap management
- `gallery_curator` — photo and media uploads
- `admin` — full system access

Contact your club administrator or [hello@croquetclaude.com](mailto:hello@croquetclaude.com) to request access.

---

## For clubs: handicap management

The handicap system tracks GC and AC handicaps for all registered QLD players. Handicaps are calculated from game results submitted through the platform. Captains can view and manage their club's players.

Full system documentation: [[projects/handicap-system/handicap-system-plan\|Handicap System Plan]]

---

## Roadmap

Planned modules in the build queue:
- Session booking for Come & Try (organiser dashboard)
- SMS reminders for Come & Try sessions
- Club-to-club messaging
- Tournament and pennants management

Build progress: [[projects/handicap-system/mycroquet-tasks\|MyCroquet Task Board]]

---

## Related

- [[resources/wiki/home\|← CAQ Wiki]]
- [[resources/wiki/come-and-try/home\|Come & Try]] — the module currently in progress
