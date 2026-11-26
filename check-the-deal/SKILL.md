---
name: "check-the-deal"
description: "Check whether a sale price (Black Friday, Cyber Monday, Prime Day or any discount) is really a good deal before buying: usual price, model variant, alternatives, returns, verdict."
---

# Check the deal

Use when the person shares a product (name, model number or link) and a sale price and wants to know if it's worth buying. Give a clear verdict they can act on in under a minute. This is shopping information, not financial advice.

## Inputs
- Product name and, ideally, the exact model number (ask for it once if missing: deals hide in model numbers).
- Sale price and the store.
- Optional: what they need it for, budget, deadline.

If the person gives a link, open it (WebFetch) to read the exact model number, price, seller and return terms. If the page can't be read, ask them to paste the model number and price.

## Steps
1. **Identify the exact model.** Find the full model number and release year. Check whether it is a store-specific or "derivative" model made for sales events (often a slightly different model number, fewer ports, a lower-grade panel or less storage than the well-reviewed version). Say plainly if it is.
2. **Usual price.** Search the web for the model's typical price over recent months (retailer listings, reputable deal sites, review sites). State the range you found and where it came from. You cannot see live price-history charts: tell the person to confirm in a free price-history tracker for that store before buying.
3. **Is it the lowest?** Compare the sale price with the typical range and any recent lows you found. Note if the "was" price looks inflated.
4. **Alternatives.** Name 2 comparable options (one cheaper, one better) with why, so the person can compare value, not just the discount.
5. **Fine print.** Check the seller (the store itself vs a third-party seller), the return window (holiday purchases often get extended returns: say if found), restocking fees, and warranty.
6. **Fit.** If the person said what it's for, say whether this model actually meets that need.

## Output (keep it short)
**Verdict:** Buy now / Wait / Skip, in one line with the main reason.

| Check | Finding |
|---|---|
| Exact model | ... (flag derivative/doorbuster versions) |
| Sale price vs usual | $X vs typical $Y–$Z |
| Lowest recently? | Yes / No / Can't confirm (check a price tracker) |
| Better-value alternatives | 1. ... 2. ... |
| Seller and returns | ... |

**Before you click buy:** confirm the price history in a tracker, confirm the model number on the checkout page matches, and screenshot the price and return policy.

Then list the sources you used as links.

## Rules
- Never invent prices, price history or specs. If you couldn't find something, say "couldn't confirm" and how to check.
- Prices change by the hour: give the date you checked.
- Don't buy anything or enter payment details for the person; the decision and checkout are theirs.
- Rule of thumb to share: buy only if it is the lowest price in about 3 months, it is the right model, and returns are easy.