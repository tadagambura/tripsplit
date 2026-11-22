# TripSplit: Spec

**Split group trip costs and settle up fast** · #29 of 33 in the build order · Harder · Revenue potential: Medium · Plans, Trips & Occasions · Source: ChatGPT + Perplexity

## One-liner

Create a trip, add friends, log who paid for what (equal, uneven or percentage splits), and TripSplit works out the fewest payments to settle up. Works offline; share by link.

## Problem / audience

- **Who it's for:** Friend groups, couples, stag and hen groups, festival-goers, families.
- **The problem it solves:** Groups lose track of who paid for what and who owes whom.
- **Example:** Four friends log hotels, taxis, food and tickets, and at the end the app says exactly who pays whom.

## MVP features (ship with only these)

1. Trips with participants
2. Expenses with equal, uneven or percentage splits
3. Simplified debts (fewest transfers)
4. Summary export as an image or PDF
5. Works offline; share by link

## Not in MVP

- Multi-currency
- Unlimited trip history
- Premium themes

## Monetisation

| Model | Detail |
|---|---|
| Free | Trips, with ads |
| Premium | £4.99 one-off: unlimited trips, exports, currencies |
| Ads | Light |

Prices are starting points; test before committing.

## Retention: The Progression Loop

| Stage | Design |
|---|---|
| Cue | Active trip; settle-up reminder |
| Tiny win | Log an expense |
| Progress | Balances settling |
| Share | Every trip invites the group |
| Next step | Next trip (links to PackRight and Daymark) |
| Cadence | Per trip |

Follow the portfolio guardrails: no guilt-trip notifications, no fake urgency, progress is
never wiped, at most one notification a day by default.

## Platform & data

- **Platform:** Expo app + Supabase (everyone needs to see the same data).
- **Data:** Supabase: multi-user by nature.
- **Stack:** shared portfolio foundation (Expo, PostHog, RevenueCat, AdMob, shared Progression Loop module).

## Growth engine

- **Content pillars:** Group travel money; Awkward money conversations; Trip budgeting
- **Shareable output:** Every trip invites the group

## Risks

Needs accounts, sync and a correct settle-up algorithm. Quiet between trips.

## Launch checklist

- [ ] Name checked on the App Store, Play Store and a trademark search
- [ ] MVP features done and tested
- [ ] Progression Loop wired (cue, tiny win, progress, milestone, next step)
- [ ] Privacy policy and terms
- [ ] Landing page
- [ ] Analytics wired (D1/D7/D30 retention)
- [ ] Payments / ads wired
- [ ] Added to growth-engine as an app config
