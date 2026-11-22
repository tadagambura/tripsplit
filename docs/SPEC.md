# TripSplit: Spec

**Rank in portfolio:** #14 of 15 (easiest → hardest) · **Difficulty:** Medium

## One-liner

Split group trip costs and see who owes who.

## Problem / audience

- **Who it's for:** Friends on holidays, stag/hen trips, house-shares, festivals.
- **The problem it solves:** Groups lose track of who paid for what and who owes who.

## MVP features (ship with only these)

1. Create a trip, add people
2. Log expenses (who paid, split equally or custom)
3. Balances and minimal settle-up (fewest transfers)
4. Share trip via link

## Not in MVP

- Multi-currency
- Exports (CSV/PDF)
- Unlimited trip history

## Monetisation

| Model | Detail |
|---|---|
| Free | Trips, with ads |
| Paid | £2.99 per trip or £1.99/month: exports, currencies, history |
| Ads | Light |

Prices are starting points from the portfolio brief; test before committing.

## Platform & stack

- **Platform:** Expo + Supabase (everyone in the group needs to see the same data).
- **Stack:** shared portfolio foundation (Expo, PostHog, RevenueCat, AdMob). See the portfolio roadmap.
- **Data:** Supabase: multi-user by nature.

## Growth engine hooks

- **Shareable output:** Every trip invites the whole group: built-in distribution.
- **Content pillars:** Group travel money; Awkward money conversations; Trip budgeting

## Notes

Strong built-in virality (every user invites friends), but needs accounts, sync and a correct settle-up algorithm. Competes with Splitwise.

## Launch checklist

- [ ] Name checked on App Store / Play Store / trademark search
- [ ] MVP features done and tested
- [ ] Privacy policy + terms
- [ ] Landing page
- [ ] Analytics wired
- [ ] Payments / ads wired
- [ ] Added to growth-engine as an app config
