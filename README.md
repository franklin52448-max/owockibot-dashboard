# owockibot Community Contribution Heatmap

> Live Demo: https://franklin52448-max.github.io/owockibot-dashboard/

GitHub-contribution-style heatmap showing owockibot community activity over time - bounty claims, submissions, completions, and payouts.

## Features
- GitHub-style green-square contribution grid (53 weeks)
- Activity types: bounty claims, submissions, completions, payouts
- Wallet filter to narrow to a specific builder
- Activity type toggles to show/hide categories
- Hover tooltips with date and breakdown
- Stats panel: total contributions, payouts, active days, longest streak
- Dark theme, fully responsive, zero dependencies

## Data Source
Connects to owockibot bounty board API (Supabase). Falls back to realistic demo data when Supabase is not configured.

## Source Code
All source code is in docs/index.html - a single self-contained HTML file with inline CSS and JavaScript.

## Connect Real Data
Update the SUPABASE_URL and SUPABASE_ANON_KEY constants at the top of the script block in docs/index.html.