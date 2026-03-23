# Contributing to the Mars Architecture

First: thank you for engaging with this. The whole point of putting this in public is to have it stress-tested by people who know things I don't.

## What I'm Looking For

### Technical Critique
- "This won't work because X" — with specifics
- "You've underestimated Y" — with numbers or references
- "The assumption about Z is wrong because..." — with explanation

### Prior Art
- "NASA studied this in [year] and concluded..."
- "This is similar to [proposal name], which failed because..."
- "Robert Zubrin / SpaceX / ESA proposed something like this, here's how yours differs..."

I haven't done an exhaustive literature review. If this idea has been tried and rejected, I genuinely want to know why.

### Domain Expertise
If you have professional experience in:
- Spacecraft systems engineering
- Mars EDL (entry, descent, landing)
- ISRU (in-situ resource utilization)
- Crewed mission planning
- Nuclear power systems
- Cryogenic propellant storage
- Space policy or international partnerships

...your critique carries extra weight. Please identify your background (even vaguely—"I work in aerospace" is enough).

### Cost Reality Checks
My cost estimates are based on public analogues (SLS, Orion, ISS, Commercial Crew). If you have better sources or different analysis, I want to hear it.

### Improvements
If you see a way to make this architecture stronger, simpler, or more survivable—tell me or submit a PR.

---

## What I'm NOT Looking For

### Vague praise or criticism
"This is great!" or "This will never work" without specifics doesn't help me improve it.

### Scope creep
"You should also include nuclear thermal propulsion / space elevators / Starship-specific variants" — maybe, but the current architecture is deliberately vehicle-agnostic where possible. Major additions need strong justification.

### Political arguments
"NASA will never do this because of Congress" is true but not useful. The architecture assumes partnership specifically to address political durability. Policy critique welcome; partisan commentary isn't.

---

## How to Engage

### Open an Issue
Use issues for:
- Technical questions or critiques
- Pointing out errors or inconsistencies
- Identifying gaps or unstated assumptions
- Suggesting improvements

Please use a descriptive title: "MAV delta-V margin seems insufficient" not "Problem with vehicles"

### Submit a Pull Request
PRs welcome for:
- Factual corrections
- Clarifications
- Additional analysis
- Diagrams or visualizations
- Translations

For significant changes, open an issue first to discuss.

### Just Share It
If you don't have technical feedback but know someone who might—a space professional, a policy expert, a YouTuber who covers this stuff—share it with them. The best ideas improve by being challenged, and they need to reach the right people first.

---

## Tone

Be direct. Be specific. Don't worry about hurting my feelings—I put this out here to find out if I'm wrong.

But also: assume good faith. This is one person's attempt to think through a hard problem. If something seems obviously wrong, consider that I might have a reason, or I might have just missed it. Ask before assuming incompetence.

---

## What Happens to Good Feedback

If you identify a real flaw or improvement:
1. I'll acknowledge it in the relevant document
2. I'll credit you (unless you prefer anonymity)
3. The architecture will be updated
4. The CHANGELOG will reflect the change

This is meant to be a living document. It will get better as more people engage with it.

---

## A Note on Expertise

I'm a computer science teacher, not an aerospace engineer. I've read extensively, but I haven't built spacecraft.

That's exactly why I need your help. The core insight (natural redundancy from mission cadence) seems sound to me, but "seems sound to a CS teacher" isn't the bar we need to clear.

If you know why this won't work, tell me. If you know why it might, tell me that too.

---

## Contact

For all feedback and questions, use [GitHub issues](../../issues). Keeping discussions public helps others learn from the conversation.

---

*Thanks for reading this far. Now go find something wrong with the architecture.*
