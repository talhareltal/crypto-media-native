# crypto-media-native

Before you announce your next big thing, get Claude to tell you if it's news.

Built for crypto CMOs, founders and comms leads who'd rather hear "not news" from an AI than from a reporter who stopped opening their emails.

More of this, daily: **The Crypto Media Club** on Telegram: [t.me/CryptoMediaClub](https://t.me/CryptoMediaClub)

Know who you're pitching. Curated X lists:
- [Crypto journalists](https://x.com/i/lists/1750070019994616223)
- [Crypto media outlets](https://x.com/i/lists/1743980521045082134)
- [Crypto podcasts](https://x.com/i/lists/2053763774641754172)

## The test

Show an agent this:

> "Halcyon Protocol announces strategic partnership with Driftwood Labs to accelerate Web3 adoption."

A media-native agent asks: did Driftwood announce it too? Did money move? Is anything live? Who outside these two companies cares?

An agent that polishes the headline and suggests a stronger quote is not media-native.

## What you can ask it

- "We're announcing a partnership next week. Is it news?"
- "Here's our funding release. What will a reporter ask?"
- "Exclusive or embargo for our Series A?"
- "Our agency says we got 80 placements. How many are real?"
- "Here are our Q1 updates. Which deserve a release?"
- "Why did nobody cover our mainnet launch?"
- "We just got exploited. What do we say?"

## What you get back

Short and direct. Something like:

> **Verdict:** Not news.
> **Why:** Nothing happened. "Will explore" is a plan.
> **Missing:** Launch date. Partner confirmation. Any number.
> **Do this:** Joint X thread now. Release when it's live.

No compliments. No ten-point lists. No "exciting milestone".

## What's inside

```
SKILL.md                      voice, maxims, routing, output format
references/
  news-test.md                is it news, and where it goes if not
  announcement-types.md       funding, TGE, listings, launches, hacks, hires...
  fluff-patterns.md           words and moves reporters ignore
  timing-and-access.md        exclusive vs embargo vs blast, timing
  coverage-audit.md           earned vs paid vs syndicated
examples/
  teardown-partnership.md     what good output looks like
  failure-autopsy.md          what bad output looks like
```

Claude only loads the reference file the task needs.

## Install

**Claude (app):** zip the folder and upload it under Skills in settings.

**Claude Code:**
```
git clone https://github.com/talhareltal/crypto-media-native ~/.claude/skills/crypto-media-native
```

**Other agents:** copy the folder into your agent's skills directory (`.agents/skills/` for the cross-agent standard).

## Maxims

- A partnership the partner didn't announce is a press release, not a partnership.
- "Strategic investment" with no number is a rumor you paid to distribute.
- Syndication is distribution, not coverage.
- Testnet is not launch. Waitlist is not launch. Launch is launch.
- Users you can't define are not users.
- If the quote is the best part, there is no story.
- No news is better than weak news. Weak news costs you the next pitch.

## What it won't do

- Give legal advice. Hacks, tokens and regulation: talk to counsel.
- Name outlets as pay-to-play. It shows you the signals.
- Help dress paid content up as earned coverage.

## About

Built by Tal Shmuel Harel, co-founder of Chainstory. Yes, a PR person wrote a skill that tells you when not to do PR. That's the point.

All examples are invented. Any resemblance to a real release is a coincidence, and probably a sign that release needed this skill.

MIT license.
