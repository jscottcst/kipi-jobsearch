# Application Pipeline Rules

> When to advance, park, follow up, or close out an opportunity.

## Pipeline Stages <!-- pin -->

| Stage | Meaning | Next Action |
|-------|---------|-------------|
| Prospect | Found a role or company worth targeting | Research fit, decide to apply or park |
| Applied | Application submitted | Log date, set Day 7 follow-up |
| Screening | Recruiter phone screen scheduled or completed | Prep, then follow up within 24h post-call |
| Interviewing | Active in interview loop (any round) | Prep per round, follow up same day after each |
| Offer | Received written offer | Evaluate, negotiate if warranted, set decision deadline |
| Accepted | Offer accepted | Close all other active opportunities gracefully |
| Closed-Lost | Rejected or withdrew | Log reason, note re-engage trigger if any |
| Parked | Interesting but not hiring now | Set resurface date (30-90 days) |

## Auto-Close Rules <!-- pin -->

- **Applied + no recruiter contact + 21 days = Ghosted** - move to Closed-Lost, log as "no response"
- **Post-screen + no next steps + 14 days = Closed-Lost** - one final follow-up first, then close
- **Post-interview + no feedback + 14 days = Closed-Lost** - one final follow-up first, then close
- No decision needed. System surfaces these in the morning briefing for one-click close.

## Re-Engagement Triggers

These events allow re-engaging a Closed-Lost or Parked opportunity:

- **Role re-posts** at the same company (detected via LinkedIn scrape)
- **New relevant role opens** at a target company
- **Company makes relevant news** (funding, expansion, new product in your domain)
- **Recruiter reaches out** proactively after prior close
- **Mutual connection** offers a warm intro to the hiring team
- **Parked date arrives** (resurface from morning briefing)

## Parking Rules

- Role looks good but position is on hold or timing is off = Park with a resurface date
- Company is a strong target but no open roles = Park, set 30-day resurface to re-check
- Parked opportunities surface automatically in the morning briefing on their date
- No action required until the date arrives

## Fit Scoring (quick pass before applying) <!-- pin -->

Apply if 3+ of these are true:
- Role type matches (SE, Systems Engineer, or IT Engineer)
- Industry is financial services, fintech, or adjacent tech
- Company size is in ICP range (100-10,000 employees)
- Remote or hybrid available in EST
- No hard requirement for prior SE title or quota experience

Park if 1-2 match. Pass if 0.
