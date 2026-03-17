# SALE User Guide

**Version 1.0 | March 2026**

## Table of Contents

1. [What Is the SALE?](#1-what-is-the-sale)
2. [When to Use the SALE (and When Not To)](#2-when-to-use-the-sale-and-when-not-to)
3. [How to Fill Out the SALE](#3-how-to-fill-out-the-sale)
4. [Worked Example](#4-worked-example)
5. [Key Provisions Explained](#5-key-provisions-explained)
6. [Operationalizing the SALE: The Board Resolution](#6-operationalizing-the-sale-the-board-resolution)
7. [Frequently Asked Questions](#7-frequently-asked-questions)

---

## 1. What Is the SALE?

The SALE (Simple Agreement for Liquidity Exit) is a standardized, open-source instrument for secondary sales of private company stock. It is designed for small-ticket secondary transactions — typically an early employee or seed investor selling shares to a new buyer — where the cost and complexity of a custom stock purchase agreement ("SPA") would be disproportionate to the transaction size.

The SALE combines three functions into a single document:

- **Purchase Agreement:** The Seller sells, and the Buyer purchases, a specified number of shares at a negotiated price.
- **Deemed Joinder:** The Buyer automatically becomes a party to the Company's existing Investors' Rights Agreement, ROFR/Co-Sale Agreement, and Voting Agreement — without separate signature pages.
- **ROFR/Co-Sale Waiver:** The Company waives its right of first refusal and co-sale rights for this specific transaction.

The SALE is designed to be executed by three parties: the Seller, the Buyer, and the Company. The Company signs solely to confirm the waiver and update its cap table — it is not a party to the economic terms of the transaction.

### How the SALE Differs from a Bespoke SPA

A custom SPA for a secondary stock sale typically costs $5,000–$10,000 in legal fees, requires weeks of negotiation, and involves separate documents for the purchase agreement, ROFR waiver, and joinder. The SALE eliminates all of these by providing a single, standardized form with only a handful of variables to negotiate.

The tradeoff is flexibility: the SALE is designed for straightforward transfers and does not accommodate complex deal structures (earnouts, escrows, indemnification baskets, etc.). See Section 2 for guidance on when a bespoke SPA is more appropriate.

---

## 2. When to Use the SALE (and When Not To)

### Good Candidates for the SALE

- A departing employee selling vested common stock to an outside buyer.
- A seed investor transferring a small preferred stock position.
- Any secondary sale where (a) the transaction value is under $500K, (b) the shares are in a Delaware corporation, (c) the Buyer is an Accredited Investor, and (d) the Company is willing to cooperate.

### When to Use a Custom SPA Instead

- **Large transactions** (generally over $500K), where the economic stakes justify custom indemnification, escrow, and representation provisions.
- **Complex structures** involving earnouts, contingent consideration, installment payments, or deferred closing.
- **Non-Delaware entities.** The SALE is drafted for Delaware corporations and references the DGCL. It should not be used as-is for LLCs, LPs, or entities incorporated in other states or countries.
- **Non-Accredited Buyers.** The SALE relies on Securities Act exemptions (Section 4(a)(7) and Rule 144) that require the Buyer to be an Accredited Investor.
- **Situations where the Company refuses to participate.** The SALE requires the Company's signature to effect the ROFR waiver and cap table update.

---

## 3. How to Fill Out the SALE

The SALE contains a limited number of blanks and bracketed fields. Here is every field you need to complete.

### Cover Page

No fields to complete. The cover page contains the license, disclaimer, and attribution information.

### Preamble

| Field | What to Enter |
|-------|---------------|
| [Date] | The date the SALE is signed by all parties. |
| [SELLER NAME] | Full legal name of the Seller. |
| [BUYER NAME] | Full legal name of the Buyer (or entity name). |
| [COMPANY NAME] | Full legal name of the Company, including "Inc." or "Corp." |

### Second WHEREAS Clause

Choose one of two options:

- **Option A:** "desires to facilitate this transfer…" — Use this if the Company has **not** adopted a formal Secondary Liquidity Policy.
- **Option B:** "has adopted a Secondary Liquidity Policy…" — Use this if the Company **has** adopted a formal policy using the companion Board Resolution Template (see Section 6 below).

### Section 2(a): The Transaction

| Field | What to Enter | Notes |
|-------|---------------|-------|
| Class/Series | e.g., "Common Stock" or "Series A Preferred Stock" | Must match the Company's records exactly. |
| Number of Shares | The number of shares being sold | Whole shares only. |
| Reference Price | $ per share | See Section 2(b) below. |
| Discount | __% | The negotiated discount to the Reference Price. |
| Total Purchase Price | $ total | = (Number of Shares) × (Reference Price) × (1 − Discount). |

### Section 2(b): Valuation Standard

Check one box:

- **409A Fair Market Value:** Use this when the Reference Price is the Company's most recent 409A valuation. This is the most common choice for Common Stock transfers.
- **Last Preferred Stock Price:** Use this when the Reference Price is the per-share price from the Company's most recent preferred stock financing round. More common for Preferred Stock transfers.

### Section 3(d): Administrative Fee

Check one box to indicate who pays the $2,500 administrative fee:

- **Seller** — More common when the Seller is the one seeking liquidity.
- **Buyer** — Sometimes negotiated when the Buyer is a fund or platform executing high volumes.

### Signature Blocks

Complete the name, title, address, and email fields for all three parties (Company, Seller, Buyer).

### Exhibit A: Wire Instructions

Complete the wire transfer details for the Seller's receiving account:

- Bank Name
- Account Number
- Routing Number (ABA)
- Account Holder Name

---

## 4. Worked Example

**Scenario:** Jordan, a software engineer, is leaving TechCo, Inc. (a Delaware corporation) after four years. Jordan holds 50,000 shares of vested Common Stock. An outside investor, Apex Capital LLC, wants to buy Jordan's shares. TechCo's most recent 409A valuation set the fair market value at $4.00 per share. The parties negotiate a 20% discount to account for illiquidity and transfer restrictions.

### The Math

| Item | Value |
|------|-------|
| Number of Shares | 50,000 |
| Reference Price (409A FMV) | $4.00 |
| Discount | 20% |
| Purchase Price Per Share | $4.00 × (1 − 0.20) = **$3.20** |
| Total Purchase Price | 50,000 × $3.20 = **$160,000** |
| Administrative Fee | $2,500 (paid by Seller) |
| Net Proceeds to Jordan | $160,000 − $2,500 = **$157,500** |

Note: If TechCo is required to withhold taxes (e.g., because Jordan exercised ISOs and owes AMT, or because the shares are RSUs), the withholding would be deducted from the $160,000 before remitting the balance to Jordan per Section 6(a).

### How the Fields Would Be Filled In

- **Date:** March 15, 2026
- **Seller:** Jordan Smith
- **Buyer:** Apex Capital LLC
- **Company:** TechCo, Inc.
- **Class/Series:** Common Stock
- **Number of Shares:** 50,000
- **Reference Price:** $4.00
- **Discount:** 20%
- **Total Purchase Price:** $160,000.00
- **Valuation Standard:** ☑ 409A Fair Market Value
- **Admin Fee Payer:** ☑ Seller
- **WHEREAS clause:** Option B (TechCo has adopted a Secondary Liquidity Policy)

---

## 5. Key Provisions Explained

### The Pricing Anchor (Section 2(b))

The SALE forces the parties to explicitly state two things: the Reference Price (anchored to an objective benchmark — either the 409A FMV or the last preferred round price) and the Discount applied to that Reference Price.

This structure is deliberate. By requiring the discount to be stated as a percentage and displayed prominently in the document, the SALE creates a psychological check against predatory pricing. A Seller who sees "-40%" staring back at them from the signature page is more likely to push back than a Seller who simply sees a dollar amount without context. The Reference Price anchors the negotiation to an objective, auditable number, and the discount becomes the sole variable for price negotiation.

From a tax and audit perspective, anchoring to the 409A or last preferred round price and applying a stated discount is designed to produce a defensible, arm's-length price. Auditors reviewing the Company's 409A valuation can see that the secondary transaction was priced at a deliberate discount to FMV for illiquidity — not at a distressed price that would signal the Company's equity is worth less than its 409A suggests.

### The ROFR/Co-Sale Waiver (Section 3(a))

Most venture-backed companies have a Right of First Refusal and Co-Sale Agreement ("ROFR Agreement") that gives the Company and/or its Major Investors the right to purchase shares before they can be sold to a third party. Without a waiver, a secondary sale cannot close.

The SALE includes an automatic waiver by the Company. By signing, the Company confirms that it has either (a) obtained any necessary waivers from Major Investors, or (b) allowed the applicable notice and exercise periods to lapse. This waiver applies only to the specific shares in this transaction — it does not waive the Company's rights for any future transfers.

**Important:** The Company should complete its internal ROFR process (notifying Major Investors, allowing the exercise period to lapse) *before* signing the SALE.

### The Deemed Joinder (Section 3(b))

When shares change hands, the new holder must become a party to the Company's governance agreements (IRA, ROFR Agreement, Voting Agreement). Normally, this requires a separate Joinder Agreement with its own signature page for each agreement.

The SALE eliminates this by including a deemed joinder provision: by signing the SALE, the Buyer automatically becomes bound by the Company Agreements to the same extent as the Seller. No separate joinder documents are needed.

The Buyer "steps into the shoes" of the Seller with respect to the Transferred Shares only. The Buyer does not assume any of the Seller's pre-Closing obligations.

### The Non-Reliance / "Big Boy" Acknowledgement (Section 4(a))

This is the provision that protects the Company and Buyer from post-closing litigation by the Seller.

**Seller's side:** The Seller acknowledges that the Buyer and Company may possess material non-public information (MNPI) — such as an upcoming acquisition, financing round, or financial results — and expressly waives any right to rescind the transaction based on the existence of such information. The Seller also waives the protections of California Civil Code Section 1542 (and analogous laws in other states), which would otherwise preserve claims that the Seller didn't know about at the time of signing.

**Why this matters:** In secondary sales, information asymmetry is inherent. The Company knows more than the Seller about its own prospects. Without this waiver, a Seller who later discovers that the Company was acquired at a premium could argue the sale should be unwound. The "Big Boy" acknowledgement forecloses that argument.

**Buyer's side:** The Buyer confirms it is an Accredited Investor purchasing for its own account, and acknowledges the shares are restricted securities.

### The Administrative Fee (Section 3(d))

The $2,500 flat fee covers the Company's legal and administrative costs of processing the transfer — reviewing the SALE, updating the cap table on Carta (or equivalent), coordinating with the transfer agent, and providing the Standard Disclosure Packet.

This fee is one of the most important design features of the SALE. Companies frequently block or delay secondary transfers because processing them costs money — paralegal time, counsel review, transfer agent coordination — with no offsetting revenue to the Company. The standardized fee removes this friction by ensuring the Company is compensated for its administrative burden. It transforms secondary processing from a cost center into a break-even (or marginally positive) activity, giving the Company a financial incentive to process transfers promptly rather than ignore them.

The fee is intentionally standardized to remove it as a negotiation point. It is payable at Closing, and legal title does not transfer until both the purchase price wire and the administrative fee have been received.

### The Standard Disclosure Packet (Section 3(c))

The Company agrees to provide the Buyer with three items: (i) the most recent unaudited financial statements (balance sheet and income statement), (ii) a summary capitalization table showing the Buyer's post-transaction percentage ownership on a fully diluted basis, and (iii) a certification of good standing.

This is a deliberately minimal disclosure package — it gives the Buyer enough information to make an informed decision without imposing a burdensome diligence obligation on the Company. The Company makes no representations about its future financial performance, which is consistent with the "Big Boy" framework: the Buyer is purchasing with full knowledge that it may not have complete information.

All information in the Standard Disclosure Packet is treated as Confidential Information, and the Buyer's confidentiality obligation survives for one year after Closing or termination.

---

## 6. Operationalizing the SALE: The Board Resolution

The SALE is designed to work best when the Company has pre-approved secondary transfers at the Board level. Without this, every SALE transaction requires a separate Board vote to waive the ROFR — which reintroduces the friction and delay the SALE is designed to eliminate.

The companion **Board Resolution Template** (available in the repository as `Board_Resolution_Secondary_Liquidity_Policy.md`) provides a form Unanimous Written Consent that a Company's Board can adopt to establish a Secondary Liquidity Program with the following guardrails:

### Why the Program Structure Matters

Boards are understandably cautious about secondary transfers. Their primary fears are:

- **409A contamination.** If employees trade stock at fire-sale prices, auditors may lower the 409A FMV, which is manageable — but if they trade too high, auditors might force the company to raise the strike price for future option grants, hurting talent acquisition. The Board Resolution addresses this with a **Pricing Guardrails** provision that caps the purchase price below the last preferred round price (preventing an up-round signal) and sets a maximum discount to prevent distressed-sale signals.

- **Cap table chaos.** If 20% of the cap table tries to exit at once, it creates panic and signals a company in distress. The Board Resolution includes a **Volume Cap** (expressed as a percentage of fully diluted capitalization — typically 5%) that prevents a "run on the bank" while still providing meaningful liquidity.

- **Unwanted shareholders.** Companies do not want competitors, hostile actors, or unaccredited investors on their cap table. The Board Resolution restricts transfers to **Eligible Buyers** — Accredited Investors who are either existing Major Investors or institutionally approved buyers — with a strict prohibition on competitors.

- **Short-term speculation.** The Board Resolution includes a **Seller Eligibility** requirement: only stockholders who have held their shares for at least a minimum period (typically 12 months, aligned with Rule 144) can sell under the Program. This prevents quick flips and ensures the Program serves genuine liquidity needs.

### Key Components of the Board Resolution

| Component | Purpose |
|-----------|---------|
| **Form Integrity** | Ensures only the standard SALE form is used, maintaining consistency. |
| **Per-Transaction Limit** | Caps individual transaction size (e.g., $250K). |
| **Volume Cap** | Limits total annual transfers as a % of fully diluted cap (e.g., 5%). |
| **Pricing Guardrails** | Creates a pricing band that protects the 409A valuation. |
| **Eligible Buyers** | Restricts who can purchase shares (Accredited, approved, non-competitor). |
| **Seller Eligibility** | Minimum holding period (e.g., 12 months) to prevent speculation. |
| **ROFR Compliance** | Requires Major Investor notice process before any closing. |
| **Blackout Periods** | Prohibits closings during quiet periods or active M&A negotiations. |
| **Reporting** | Requires periodic summary of all SALE transactions to the Board. |
| **Fallback to Board** | Anything outside the guidelines requires case-by-case Board approval. |

### How to Deploy the Board Resolution

1. **Customize the blanks** in the Board Resolution — the per-transaction limit, volume cap percentage, maximum discount, minimum holding period, and reporting cadence are all company-specific decisions.
2. **Attach the SALE form** as Exhibit B to the Board Resolution.
3. **Circulate for signature** by all directors. Once signed, the Authorized Officers can process SALE transactions that meet the guidelines without returning to the Board for each one.
4. **Select Option B** in the SALE's second WHEREAS clause to reference the adopted Policy.

---

## 7. Frequently Asked Questions

**Q: Who is intended to use the SALE?**

The primary users are: (a) early employees of venture-backed companies who want to sell vested shares, (b) seed-stage investors looking to exit small positions, (c) secondary buyers (individuals or funds) acquiring private company stock, and (d) company counsel facilitating routine secondary transfers.

**Q: Does the Company have to agree to use the SALE?**

Yes. The SALE requires the Company's signature. If the Company refuses to participate, the transfer cannot close using this instrument. The companion Board Resolution Template provides a form resolution that a Company's board can adopt to pre-approve SALE transactions, eliminating the need for case-by-case Board approval.

**Q: Why is the discount to the Reference Price standard?**

Discounts in secondary transactions reflect the illiquidity of private company stock — the buyer cannot freely resell the shares on a public market. Typical discounts range from 10% to 30%, depending on the company's stage, the likelihood of a near-term liquidity event, and market conditions. The SALE's structure of anchoring to an objective Reference Price (409A or last preferred round price) and applying a negotiated discount is designed to produce a defensible, arm's-length price that auditors and tax authorities will accept.

**Q: Can the SALE be used for Preferred Stock?**

Yes. Set the Class/Series field to the relevant series (e.g., "Series A Preferred Stock") and use the last preferred round price as the Reference Price. Note that preferred stock transfers may involve additional complexities (e.g., anti-dilution adjustments, liquidation preference calculations) that the SALE does not address. Consult counsel for preferred stock transactions.

**Q: Can the $2,500 administrative fee be changed?**

The SALE is a standardized form, and the $2,500 fee is part of the standard. If parties wish to use a different fee amount, they should note that the form integrity language in the preamble ("none of them has modified the form, except to fill in blanks and bracketed terms") would no longer apply, which may affect the Company's willingness to accept the instrument.

**Q: What if the Company doesn't have an IRA, ROFR Agreement, or Voting Agreement?**

If the Company has not entered into one or more of the Company Agreements referenced in the SALE, the Joinder provision in Section 3(b) simply has no operative effect with respect to the missing agreement(s). The SALE still functions as a purchase agreement and waiver for whatever agreements do exist.

**Q: What securities law exemption does the SALE rely on?**

The SALE is structured to rely primarily on Section 4(a)(7) of the Securities Act, which provides an exemption for resales of restricted securities to Accredited Investors. If Section 4(a)(7) is unavailable, the SALE falls back to Rule 144 or another applicable exemption. The Buyer's representations in Section 4(c) are designed to establish the factual predicates for these exemptions.

**Q: How does the tax withholding provision work?**

If the Seller is a current or former employee, the Company may have an obligation to withhold income or employment taxes on the transaction. Section 6(a) authorizes the Company to deduct any required withholding from the Purchase Price before remitting the balance to the Seller. This is most commonly relevant for shares acquired through option exercises or RSU vesting.

**Q: Can the SALE be used without a Board Resolution?**

Yes. The SALE functions as a standalone instrument — a Company can sign a SALE on a one-off basis with specific Board approval for that transaction. However, if the Company anticipates multiple secondary transfers, adopting the Board Resolution and establishing a Secondary Liquidity Program is strongly recommended. It transforms secondary processing from an ad hoc, Board-level decision into a routine administrative function.

---

## Disclaimer

This User Guide is provided for informational and educational purposes only. It does not constitute legal advice and does not create an attorney-client relationship. Consult your own counsel before executing any binding agreement.

Originally authored by Evan J. Lonergan, 2026. Dedicated to the public domain under CC0 1.0 Universal.
