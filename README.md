# ⚾ Hitters Edge v7.0

MLB prop betting intelligence system. Pulls live data from MLB Stats API and Baseball Savant. No subscriptions required.

## Live App
**[Open Hitters Edge](https://YOUR_USERNAME.github.io/hitters-edge)**

## What It Does
- Fetches today's MLB lineups, pitcher stats, and batter stats automatically
- Scores every batter on 4 prop types: H+R+RBI, Hits, Total Bases, HR
- Grades picks A/B/C based on 3 protocol checks
- Pitcher K props and game totals
- Hot/Cold streaks based on last 14 days vs season average
- P&L tracker with full bet history saved in your browser
- Parlay builder
- Player tracker showing who wins and loses most for you

## Scoring System
- **A-Grade** = lineup spot 1-2 + OBP ≥ .320 + vulnerable pitcher (2+ vuln flags)
- **B-Grade** = 2 of 3 protocol checks
- **TB score** penalizes high walk rate (walks = 0 total bases)
- **Hot** = batting .050+ above season average in last 14 days
- **Ace** pitchers eliminate entire opposing lineup

## Data Sources (all free, no API keys)
- MLB Stats API — lineups, pitcher stats, batter stats, game logs
- Baseball Savant — exit velocity, barrel rate

## Setup
1. Fork this repository
2. Go to Settings → Pages → Source: main branch → Save
3. Your app is live at `https://YOUR_USERNAME.github.io/hitters-edge`

## Daily Use
1. Open the app in any browser
2. Wait 3-4 minutes for data to load (pulls stats for every player)
3. Check Guide tab for picks sorted by prop type
4. A-Grade only for real money bets
5. Log bets in the Log tab — results save in your browser

## Betting Protocol
- A-Grade only for real money
- $25 max per bet until win rate is proven over 20+ graded picks
- -140 or better odds only
- Confirm lineup before betting
- No chasing losses
