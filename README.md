# U13 Softball Bingo Pool — planning prototype

## Open it
Double-click `index.html` to explore the browser-only demonstration. No server is required. The demo can be hosted on GitHub Pages for preview purposes, but doing so **does not** make it a secure multiuser application.

## Included
- Customizable team name, price, and 13 family labels
- Select 6 unique numbers out of 49; create test bingo cards
- Eight manual sample draw result slots
- Cumulative unique-number hits and leaderboard
- Organizer demo: mark sample entries paid, family totals, CSV export
- Shareable sample URL parameter `?support=Player%201`
- Responsive layout for mobile and desktop

## Important limitations
**Demo only.** All records are stored in the local browser via `localStorage`, so cards created on one person's device are **not** shared with other devices. There is no real payment processing, ticket issuing, verified draw process, live database, or secured admin access. Do not enter real participant personal information and do not use this version for live paid games.

## Before a real launch
1. Confirm with your Ontario softball association and AGCO whether the proposed Lotto 6/49 bingo-pool format is licensable, and whether your organization meets charitable eligibility requirements.
2. Have the licensing authority review approved rules, entry eligibility, prize distribution/ties, ticket details, online sales, and geographic restrictions.
3. Use the approved electronic raffle system / licensed service provider as required. Do not assume a generic GitHub Pages and payment-form site is acceptable.
4. If an actual multi-user database is authorized, implement secure server-side administration, privacy policy, audit trail, approved payment management, and a verified draw mechanism.

Official information: https://www.agco.ca/en/lottery-and-gaming

This is an original, from-scratch prototype based on the general idea of a bingo-pool fundraiser, not copied code from another team's repository.
