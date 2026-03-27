---
{"dg-publish": true, "permalink": "/resources/wiki/come-and-try/email-sequence/", "tags": ["come-and-try", "email", "wiki"], "dg-home-link": true, "dg-pass-frontmatter": true, "dg-show-backlinks": true, "dg-show-inline-title": true, "dg-show-file-tree": true, "dg-enable-search": true, "dg-show-toc": true, "dg-link-preview": true, "dg-show-tags": true}
---


# The Email Sequence

When someone signs up at [comeandtrycroquet.com](https://comeandtrycroquet.com), a 28-day email sequence starts automatically. Nine emails — one every few days — timed to run alongside the in-person visits.

Clubs don't manage this. It runs in the background.

---

## What the sequence does

The emails do the same thing the volunteer does in person: they make the visitor feel welcome, curious, and like they belong. They're not promotional. They don't push membership. They reinforce the experience with stories, technique, and the kind of insider knowledge that makes someone feel like they're starting to understand the game.

Nine emails across four weeks. Each one is either a Head (tactical, curious, something you didn't know) or a Heart (a story, a moment, an emotional landing).

---

## The nine emails

| # | Day | Subject | Type |
|---|-----|---------|------|
| 0.1 | 0 | Welcome to the lawn (and 3 myths to ignore) | Head |
| 0.2 | 3 | The only three things you need to bring | Heart |
| 1.1 | 7 | The Art of the Stalk | Head |
| 1.2 | 10 | She couldn't find her name on the list | Heart |
| 2.1 | 14 | The only three shots you need | Head |
| 2.2 | 17 | The most important part of the game | Heart |
| 3.1 | 21 | She went backwards for eight months | Head |
| 3.2 | 24 | You are starting to look like a regular | Heart |
| 4.1 | 28 | Making it official? | The Ask |

The final email — Day 28 — is the only one that directly mentions joining. By then, four weeks have passed. Either the visitor is interested or they've moved on. The ask is gentle: "Can you see yourself here?"

---

## What volunteers need to know

**You don't manage the email sequence.** It runs automatically from sign-up. The system handles the timing, delivery, and all nine emails.

**The emails and visits are designed to work together.** Week 1 emails land around the taste test. Week 2 emails land around the first club day. The digital and in-person sides reinforce each other.

**If someone says "I got your email" — that's working.** It means the sequence is running and they're engaging. That's a warm visitor.

---

## The technical backend

The sequence runs through Plunk (email platform) on Coolify, using AWS SES as the sending backend. The drip automation is built and loaded with all nine templates. Currently in SES sandbox (emails go to verified addresses only); production access will enable full public sending.

For the full technical detail, see [[resources/wiki/come-and-try/for-operations\|Operations]] (internal).

---

## Related

- [[resources/wiki/come-and-try/home\|← Come & Try]]
- [[resources/wiki/come-and-try/running-a-session\|Running a Session]] — the in-person side
- [[resources/digital-marketing/email-and-nurture\|Email and Nurture]] — full email strategy document
