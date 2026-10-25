# Claude business skills

5 free Claude skills that do the boring work in a small business. Shared by [@aipranjal](https://www.instagram.com/aipranjal/).

A skill is a saved set of instructions Claude follows every time. Upload these once and just ask: "chase this invoice", "reply to these reviews", "answer this lead".

| Skill | What it does | Ask Claude |
|---|---|---|
| [invoice-chaser](invoice-chaser/SKILL.md) | Payment reminders from a friendly nudge to a firm final notice, email + WhatsApp | "Client hasn't paid invoice #208, 12 days late" |
| [review-replier](review-replier/SKILL.md) | Replies to Google / Zomato / Amazon reviews in your tone, including angry ones | "Reply to these 10 reviews" |
| [lead-reply](lead-reply/SKILL.md) | Answers a new enquiry with one qualifying question and a next step, plus 2 follow-ups | "Reply to this WhatsApp lead" |
| [proposal-writer](proposal-writer/SKILL.md) | Messy call notes -> a clean one-page proposal with price options | "Turn these call notes into a proposal" |
| [weekly-report](weekly-report/SKILL.md) | A week of numbers -> what changed, why, and 3 things to do next | "Here's this week's sales, make my weekly report" |

All five refuse to invent prices, dates, offers or numbers: anything missing comes back as a `[placeholder]` for you to fill.

## Install

**Claude.ai (web, desktop, mobile):** Settings -> Capabilities -> Skills -> upload a skill zip from the [`zips/`](zips) folder (one zip per skill).

**Claude Code:** copy the skill folders into `~/.claude/skills/` (or your project's `.claude/skills/`).

## License

MIT, see [LICENSE](LICENSE). Use them, change them, share them.
