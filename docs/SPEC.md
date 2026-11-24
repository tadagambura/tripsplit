# TripSplit: Spec

**Split group trip costs and settle up fast** · #15 of 17 · Wave 2: Recurring keepers · Used: Per trip · Harder · Revenue potential: Medium · Plans, Trips & Occasions · Source: ChatGPT + Perplexity

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

Prices are starting points; test before committing. **Portfolio premium promise:** free has ads; the moment you pay you get no ads, cloud backup and storage, and sync across your devices, plus this app's extras.

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

## Animation and tone: five signature animations

**Playful.** Celebrations, confetti, cute characters, satisfying sounds and mild comic reactions. Nothing tragic.

- Settled up: Kaos and a friend shake hands and an 'ALL SQUARE!' stamp lands
- Expense added: the receipt flies into the pot
- Trip complete: the suitcase stamps itself with a sticker
- Friend joins: stickmen pile into a tiny car
- Currency switched: coins spin and change colour

**Line we don't cross:** No drama about who owes money.

## AI

**None.** Not needed. Plain code does everything this app does. (Portfolio rule: plain code first, code does the maths,
cheapest model, shared budget cap, premium-gated.)

## Platform & data

- **Platform:** Expo app + Supabase (everyone needs to see the same data).
- **Data:** Supabase: multi-user by nature.
- **Backend:** Shared data from day one: everyone on the trip sees the same expenses. Premium backup and sync use the shared portfolio backend (see the master repo's HOSTING.md).
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
- [ ] Added to the Growth & Maintenance Engine as an app config
