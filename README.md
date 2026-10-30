# Elastic: an adaptive habit tracker

**Prototype by Anvitha Abbagani. Made-up habits, history and browser data.**

**Live:** https://elastic.abbagani.com

Most habit trackers assume you show up with the same energy every day. On a low-energy day,
partial effort counts as failure and one missed day resets the streak to zero, which is when people
quit. Elastic is built around that day: every habit has a Mini, Plus and Elite tier, and momentum is
kept as fuel that eases off instead of resetting.

**What the prototype does:**
- **Dashboard:** log Running Practice, Deep Work and Waking Up Early at Mini, Plus or Elite in one tap.
  Hide a habit for today, or Snooze every goal. Deep Work has a focus timer, and a simulated browser
  extension offers active GitHub minutes (idle time filtered out) to add.
- **Fuel** replaces the streak in the top bar. It never drops to zero after a missed day.
- **Objectives:** each goal's progress, deadline and projected finish date.
- **Achievements:** milestones you set, tied to a goal, that come into colour as they fill.
- **Insights:** a Protocol Insight with COM-B scores (Capability from fuel, Opportunity from Hide for
  today, Motivation from Mini vs Plus/Elite), Progress Velocity, a 21-day heatmap and effort
  distribution.
- Confetti for Elite only, and a six-step Quick tutorial (Back and Next, with the relevant part of the screen highlighted) that walks through a low-energy day.

**What it doesn't do:** use a real AI model (the insight is rule-based), run a real browser
extension, or offer accounts, sync, social features or levels. State is kept in this browser only.

It is one HTML file with no build step. The only network request is for its Google Fonts.
