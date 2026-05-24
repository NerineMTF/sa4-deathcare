# Game of Death — Complete Content & Logic Audit

**Purpose:** A fine-toothed-comb inventory of every piece of text, game mechanic, financial figure, legal reference, and preparedness logic in the game, structured for factual review against NZ research findings.

---

## 1. Title Screen Text

| Element | Exact text |
|---|---|
| Title | GAME OF DEATH |
| Subtitle | THE AFTERLIFE ISN'T AUTOMATIC. |
| Tagline line 1 | A board game about everything you didn't sort out. |
| Tagline line 2 | Navigate the chaos you left behind. |
| Tagline line 3 | The most organised corpse wins. |
| Footer | 1–4 players · Ages 18+ · ~30 minutes |

---

## 2. Personas (6 total)

Each persona is randomly assigned at game start. Starting chaos and estate values are set by the persona; the preparedness declaration then reduces starting chaos based on which documents the player ticks.

### 2.1 The Busy Parent
- **Tagline:** Always meant to sort it out
- **Starting chaos:** 4 | **Starting estate:** $185,000
- **Description:** Two kids, a joint mortgage in Tauranga, and a will that was 'almost finished' in 2019. Your KiwiSaver has no nominated beneficiary. Your life insurance lapsed when you switched jobs and forgot to reinstate it. Your family is about to discover what 'almost' means.
- **Traits listed:** No will · KiwiSaver unclaimed · Lapsed insurance · 2 dependants
- **Chronicle opening:** The Busy Parent left behind two children, a half-finished will, and a KiwiSaver nobody knew how to claim.

### 2.2 The Solo Entrepreneur
- **Tagline:** The business was the plan
- **Starting chaos:** 5 | **Starting estate:** $310,000
- **Description:** You built a small trades business from nothing — three staff, an IRD number, and a ute. Unfortunately, your personal and business bank accounts are the same account, there's no shareholder agreement, and your staff have no idea what happens now. The business was the plan. There was no other plan.
- **Traits listed:** No shareholder agreement · Mixed finances · 3 employees · GST outstanding
- **Chronicle opening:** The Solo Entrepreneur's business had three staff, no succession plan, and one bank account that was also a personal account.

### 2.3 The Bach Owner
- **Tagline:** The family will sort it out
- **Starting chaos:** 5 | **Starting estate:** $1,100,000
- **Description:** You owned a bach at the Coromandel — bought in 1987 for $45,000, now worth $1.1 million. It's not in a trust. There's no will specifying who gets it. Four siblings. Three opinions. One bach. The Burial and Cremation Act 1964 will govern your funeral. Nobody has read it.
- **Traits listed:** High-value asset · No trust · 4 siblings · No will
- **Chronicle opening:** The Bach Owner left behind a $1.1M Coromandel property, no will, and four siblings who haven't spoken since Christmas 2021.

### 2.4 The Digital Native
- **Tagline:** Passwords not included
- **Starting chaos:** 3 | **Starting estate:** $42,000
- **Description:** Online banking across three banks, a Sharesies portfolio, KiwiSaver with a provider nobody can name, and a password manager only you knew how to open. Your Spotify is still playing. Your flatmates are getting the notifications. Your parents are in Christchurch and don't know your IRD number.
- **Traits listed:** Sharesies portfolio · No passwords · KiwiSaver unknown provider · Parents overseas
- **Chronicle opening:** The Digital Native had a Sharesies portfolio, three bank accounts, and a password manager nobody could open.

### 2.5 The Retiree
- **Tagline:** Next week, definitely
- **Starting chaos:** 3 | **Starting estate:** $720,000
- **Description:** NZ Super, a paid-off house in Palmerston North, four grandchildren, and a phrase you said every Sunday for 15 years: 'I'll sort the will next week.' You had a solicitor's number on the fridge. You never called it. The estate is large. The instructions are absent.
- **Traits listed:** Large estate · No will · 4 grandkids · Multiple assets
- **Chronicle opening:** The Retiree owned a paid-off house, had four grandchildren, and a solicitor's number on the fridge they never called.

### 2.6 The Young Professional
- **Tagline:** Too young to think about it
- **Starting chaos:** 3 | **Starting estate:** $8,400
- **Description:** Student loan, rented flat in Wellington, parents in Samoa, no next-of-kin listed at work or the hospital. Your KiwiSaver has $8,400 in it. Nobody knows. You were 27. Nobody saw it coming. Least of all you.
- **Traits listed:** Student loan · KiwiSaver unclaimed · No next-of-kin listed · Parents overseas
- **Chronicle opening:** The Young Professional had $8,400 in KiwiSaver, a student loan, and parents in Samoa who didn't know their IRD number.

---

## 3. Preparedness Declaration Screen

**Header text:** "Before You Died" / "What Did You Sort Out?" / "Each player declares which documents they had in order. Be honest. The game knows."

**Preparedness score labels (shown live as documents are ticked):**

| Score | Label | Colour |
|---|---|---|
| 0 | Total Chaos | Crimson |
| 1–2 | Dangerously Unprepared | Crimson |
| 3–4 | Partially Organised | Gold |
| 5–6 | Reasonably Prepared | Gold |
| 7–8 | Well Organised | Slate blue |
| 9 | Exceptionally Prepared | Green |

---

## 4. Preparedness Documents (9 total)

Each document reduces starting chaos immediately and then compounds as a section-specific modifier throughout the game. The chaos reduction shown in the declaration screen is the **starting chaos reduction only**; in-game modifiers are additional.

| # | Document | Short label | Description shown to player | Starting chaos reduction | Relevant board sections |
|---|---|---|---|---|---|
| 1 | Will | Will | A legal document directing how your estate is distributed, who looks after your children, and who carries out your wishes (executor). | −3 | Paperwork, Family, The End |
| 2 | Enduring Power of Attorney — Property | EPA Property | Authorises someone to manage your money and property if you become incapacitated. Without it, a Family Court application is required and accounts are inaccessible. | −2 | Paperwork, Digital |
| 3 | Enduring Power of Attorney — Personal Care & Welfare | EPA Welfare | Authorises someone to make health and welfare decisions for you if you become incapacitated. A separate document from the Property EPA. | −2 | Deathbed, Paperwork |
| 4 | Advance Care Plan | Advance Care Plan | Records your wishes for medical treatment. Not legally binding, but guides clinicians and reduces moral distress for your family. | −1 | Deathbed |
| 5 | Funeral & Burial Wishes | Funeral Plan | Documents your wishes for burial vs cremation, tangihanga, service preferences. Without it, your family must decide within 72 hours under the Burial & Cremation Act 1964. | −2 | Final Send-Off |
| 6 | KiwiSaver Nominated Beneficiary | KiwiSaver Nominee | Names who receives your KiwiSaver funds directly, bypassing the estate entirely. Without it, your KiwiSaver is frozen pending probate — potentially for 12–18 months. | −2 | Paperwork, Digital |
| 7 | Digital Estate Plan | Digital Plan | A record of your passwords, accounts, subscriptions, Sharesies portfolio, and any crypto. Without it, accounts are locked and subscriptions keep billing the estate. | −2 | Digital |
| 8 | Guardianship Nomination | Guardianship | Names a guardian for your minor children in your will. Without it, Oranga Tamariki may become involved and the Family Court decides. | −2 | Family |
| 9 | Life Insurance (Current) | Insurance | Current life insurance or income protection policy. Provides liquidity for dependants. Lapsed policies pay nothing. | −2 | Family, Business |

**Maximum starting chaos reduction if all 9 documents ticked:** −18 tokens.

---

## 5. In-Game Preparedness Compounding Logic

When a player lands on a space with a positive chaos effect, the following modifiers reduce the chaos penalty **before it is applied**. Each modifier reduces chaos by 1 (or 2 for Funeral Plan and Digital Plan in their sections), floored at 0.

| Document held | Reduces chaos on spaces in these sections | Reduction amount |
|---|---|---|
| Will | Paperwork, Family, The End | −1 per space |
| EPA Property | Paperwork, Digital | −1 per space |
| EPA Welfare | Deathbed, Paperwork | −1 per space |
| Advance Care Plan | Deathbed | −1 per space |
| Funeral Plan | Final Send-Off | −2 per space |
| KiwiSaver Nominee | Paperwork, Digital | −1 per space |
| Digital Plan | Digital | −2 per space |
| Guardianship | Family | −2 per space |
| Insurance | Family, Business | −1 per space |

When preparedness absorbs chaos, the Chronicle logs: *"Your preparation absorbed N chaos token(s) here."*

**Card-level modifiers (applied when a card is drawn):**

| Document held | Applies to | Reduction |
|---|---|---|
| Will | Crisis and Regret cards | −1 chaos |
| EPA Property | Crisis cards | −1 chaos |
| Insurance | Crisis cards whose title contains "insur" | −2 chaos |

When a card is softened, the Chronicle logs: *"Your documents softened this blow — N chaos token(s) absorbed."*

---

## 6. Board Spaces (48 total, spaces 0–47)

### Section 1: The Deathbed (Spaces 0–5)

| Space | Type | Label | Sublabel | Effect | Message text |
|---|---|---|---|---|---|
| 0 | Start | The Deathbed | It begins here | None | — |
| 1 | Normal | Death Certificate | Who's handling this? | +1 Chaos | Someone has to register the death with Births, Deaths and Marriages. That someone is now very stressed. |
| 2 | Crisis | Next of Kin Unknown | Draw a Crisis Card | Draw Crisis | — |
| 3 | Normal | Ambulance Bill | Pay $1,100 | −$1,100 estate | The hospital was free. The ambulance wasn't. St John sent an invoice for $1,100. There is always a final invoice. |
| 4 | Relief | Advance Care Directive | Draw a Relief Card | Draw Relief | — |
| 5 | Normal | Funeral Home Called | +1 Chaos | +1 Chaos | Someone had to choose a funeral home. They chose the first one they found on Google. |

### Section 2: Paperwork Purgatory (Spaces 6–14)

| Space | Type | Label | Sublabel | Effect | Message text |
|---|---|---|---|---|---|
| 6 | Normal | Probate Court | Lose 2 turns | Skip 2 turns + 1 Chaos | Probate takes 6–12 months in New Zealand. In game terms: 2 turns. |
| 7 | Crisis | No Will Found | Draw a Crisis Card | Draw Crisis | — |
| 8 | Normal | Solicitor Fees | Pay $9,500 | −$9,500 estate | You didn't write a will. The lawyers are delighted. |
| 9 | Fork | Will or No Will? | Fork in the road | +3 Chaos + −$14,000 | No will means the Administration Act decides. The family does not agree with the Administration Act. |
| 10 | Normal | Estate Valuation | Pay $1,400 | −$1,400 estate | Everything you owned, priced and catalogued by a stranger. |
| 11 | Relief | KiwiSaver Claimed | Collect $28,000 | +$28,000 estate + −1 Chaos | The KiwiSaver had a nominated beneficiary. One thing went right. |
| 12 | Normal | IRD Notification | +1 Chaos | +1 Chaos + −$2,800 estate | The IRD doesn't do condolences. Final tax return required. |
| 13 | Crisis | Disputed Executor | Draw a Crisis Card | Draw Crisis | — |
| 14 | Normal | NZ Super Stopped | Admin resolved | +1 Chaos | MSD required notification. The overpayment was recovered from the estate. |

> **Note on Space 9 (Fork):** The fork label reads *"A will saves $14,000 in legal fees and 2 Chaos. No will adds 3 Chaos and costs $14,000."* However, the fork currently applies the penalty to **all players** regardless of their `hasWill` flag. This is a known gap — the preparedness flag check is not yet wired into the fork space specifically. The general Will modifier (−1 chaos in paperwork section) does apply, but the fork does not branch.

### Section 3: The Digital Graveyard (Spaces 15–22)

| Space | Type | Label | Sublabel | Effect | Message text |
|---|---|---|---|---|---|
| 15 | Crisis | Online Banking Locked | Draw a Crisis Card | Draw Crisis | — |
| 16 | Normal | Password Manager | Lose 1 turn | Skip 1 turn | The master password died with you. Lose a turn while family tries 'password123' and the dog's name. |
| 17 | Normal | Sharesies Portfolio | +2 Chaos | +2 Chaos | The Sharesies portfolio exists. Nobody knows the login. The shares are still trading. |
| 18 | Relief | Password Notebook | Draw a Relief Card | Draw Relief | — |
| 19 | Normal | Subscription Billing | Pay $1,140 | −$1,140 estate | Netflix, Spotify, Adobe, Xero, and 11 others continue billing the estate for three months. |
| 20 | Normal | Social Media Accounts | +2 Chaos | +2 Chaos | Three platforms. None have a simple 'deceased' process. Facebook wants a death certificate. Instagram wants a notarised letter. |
| 21 | Normal | KiwiSaver Provider | +1 Chaos | +1 Chaos | Which provider? Nobody knows. There are 20 in New Zealand. |
| 22 | Relief | Digital Will Found | Draw a Relief Card | Draw Relief | — |

### Section 4: The Family Fallout (Spaces 23–31)

| Space | Type | Label | Sublabel | Effect | Message text |
|---|---|---|---|---|---|
| 23 | Crisis | Intestacy Surprise | Draw a Crisis Card | Draw Crisis | — |
| 24 | Normal | Contested Estate | Pay $16,000 | −$16,000 estate + +2 Chaos | A family member has retained a solicitor. The estate is paying for both sides. |
| 25 | Normal | Family Meeting | +2 Chaos | +2 Chaos | Everyone in the same room. Nothing resolved. Two new feuds started. The bach is still undecided. |
| 26 | Relief | Mediation Succeeds | Draw a Relief Card | Draw Relief | — |
| 27 | Normal | Guardianship Dispute | +3 Chaos | +3 Chaos | Nobody agreed on who gets the children. Nobody wrote it down. Oranga Tamariki is now involved. |
| 28 | Regret | Regret Tile | Take a Regret Tile | Draw Regret | — |
| 29 | Normal | Heirlooms Divided | +1 Chaos | +1 Chaos | The pounamu. The watch. The painting. Three items. Four opinions. One family meeting that nobody left happy. |
| 30 | Normal | The Bach Decision | +2 Chaos or −2 Chaos | +2 Chaos | Sell or keep the bach? The family cannot agree. The bach sits empty while the rates bill arrives. |
| 31 | Crisis | Whānau Claim | Draw a Crisis Card | Draw Crisis | — |

### Section 5: The Business Burial (Spaces 32–38)

| Space | Type | Label | Sublabel | Effect | Message text |
|---|---|---|---|---|---|
| 32 | Normal | Staff Left Hanging | +2 Chaos | +2 Chaos | Three employees. No payroll instructions. No one knows the business bank login. PAYE is due Friday. |
| 33 | Crisis | No Shareholder Agreement | Draw a Crisis Card | Draw Crisis | — |
| 34 | Normal | Business Debt Called In | Pay $28,000 | −$28,000 estate | The bank doesn't do condolences. The overdraft is due. |
| 35 | Relief | Key Person Insurance | Collect $50,000 | +$50,000 estate + −1 Chaos | The accountant had insisted on key person insurance. You'd forgotten about it. Lucky you. |
| 36 | Normal | Client Contracts Voided | Pay $14,000 | −$14,000 estate | Without a succession clause, the contracts died too. The clients have moved on. |
| 37 | Normal | GST Return Outstanding | +1 Chaos | +1 Chaos + −$3,200 estate | IRD requires a final GST return. The accountant charges $3,200 to file it. |
| 38 | Normal | Business Sold | Collect $55,000 | +$55,000 estate | Fire sale. Worth $180k. Sold for $55k. Someone got a bargain. |

### Section 6: The Final Send-Off (Spaces 39–46)

| Space | Type | Label | Sublabel | Effect | Message text |
|---|---|---|---|---|---|
| 39 | Normal | Funeral Costs | Pay $10,500 | −$10,500 estate | Average NZ funeral: $10,500. Nobody told you. You didn't ask. The Burial and Cremation Act 1964 governs all of this. |
| 40 | Crisis | No Funeral Instructions | Draw a Crisis Card | Draw Crisis | — |
| 41 | Normal | Burial vs Cremation | +2 Chaos | +2 Chaos | Half the family wants burial. Half wants cremation. You had no preference on file. The funeral home is waiting. |
| 42 | Relief | Pre-Written Eulogy | Draw a Relief Card | Draw Relief | — |
| 43 | Normal | Tangihanga Costs | Pay $4,200 | −$4,200 estate | The tangihanga was three days. The marae costs, the food, the travel — the estate covered it. |
| 44 | Normal | Headstone & Plot | Pay $5,800 | −$5,800 estate | The headstone. The plot. The inscription nobody could agree on. |
| 45 | Regret | Final Regret Tile | Take a Regret Tile | Draw Regret | — |
| 46 | Relief | Memorial Donation | −1 Chaos | −1 Chaos + −$500 estate | Donations to a charity in your name. A small, good thing among the chaos. |

### Section 7: The End (Space 47)

| Space | Type | Label | Effect |
|---|---|---|---|
| 47 | End | The End | Game over — chaos tallied, winner is lowest chaos score |

---

## 7. Crisis Cards (8 cards)

| Card | Title | Flavour text | Effect |
|---|---|---|---|
| C1 | The Locked KiwiSaver | No nominated beneficiary. The KiwiSaver provider requires a court order to release the funds. The estate waits. The lawyers bill by the hour. | +3 Chaos + −$12,000 |
| C2 | The 2003 Will | A will has been found. It's from 2003. You left everything to an ex-partner. Under the Wills Act 2007, this may still be valid. The ex-partner has been located. | +4 Chaos + −$35,000 |
| C3 | The Bach Dispute | Three siblings want to sell the bach. One sibling wants to keep it. Under the Property Law Act 2007, any co-owner can apply to the court for a sale. They have. | +4 Chaos + −$22,000 |
| C4 | Administration Act Intestacy | No will means the Administration Act 1969 applies. Your de facto partner of 8 years gets nothing automatically. Your estranged parents inherit first. They are, to put it mildly, surprised. | +5 Chaos + −$45,000 |
| C5 | The IRD Audit | The IRD has flagged the estate for an audit. Three years of returns are under review. The accountant is unavailable until Tuesday. | +2 Chaos + −$19,000 |
| C6 | Oranga Tamariki Involvement | No guardian was named for the children. Oranga Tamariki has opened a file. The family is in dispute. The children are in temporary care. | +5 Chaos + Skip 2 turns |
| C7 | Sole Account Locked | The accounts in your name alone were frozen by the bank pending estate administration. The joint account was fine — but the savings account only you could access held $34,000. It's locked until probate resolves. | +2 Chaos + Skip 1 turn + −$4,500 |
| C8 | The Forgotten Trust | A family trust was set up in 2011. Nobody can find the trust deed. The trustee has moved to Australia. The assets in the trust are in limbo. | +3 Chaos + −$18,000 |

---

## 8. Relief Cards (6 cards)

| Card | Title | Flavour text | Effect |
|---|---|---|---|
| R1 | The Organised Folder | In the filing cabinet, behind the takeaway menus: a folder labelled 'WHEN I DIE'. Will. Insurance. KiwiSaver provider. Funeral wishes. IRD number. You legend. | −3 Chaos |
| R2 | Life Insurance Pays Out | You kept the premiums current. The policy is valid. The payout is real. The family can breathe. One thing went right. | +$80,000 estate + −1 Chaos |
| R3 | Trusted Executor Named | You named an executor. They're calm, organised, and already on the phone to the solicitor. They have the will. They have the folder. Bless them. | −2 Chaos + +$6,000 estate |
| R4 | Pre-paid Funeral | The funeral home has your instructions and your payment on file. Burial at Waikumete. No flowers. Donations to the SPCA. The family just has to show up. | −2 Chaos + +$9,000 estate |
| R5 | KiwiSaver Nominated | You nominated a beneficiary on your KiwiSaver. The provider paid out directly, bypassing the estate entirely. Fast, clean, no lawyers. | −2 Chaos + +$24,000 estate |
| R6 | Digital Estate Plan | A sealed envelope with every login, every account, every subscription, the Sharesies login, and the KiwiSaver provider name. Dated last month. You were ready. | (chaos/estate values in code) |

---

## 9. Regret Tiles (5 cards)

Regret tiles add to the chaos score **and** increment a separate regret counter. The chaos from regret cards is applied twice in the current code (once via the card effect, once via the regret type handler) — this is a potential bug worth checking.

| Tile | Title | Flavour text | Effect |
|---|---|---|---|
| RT1 | The Unwritten Will | You meant to write it. You really did. The solicitor's number was on the fridge for four years. | +2 Chaos |
| RT2 | The Unsent Letter | There was someone you needed to speak to before the end. You didn't. They found out through a solicitor's letter. | +1 Chaos |
| RT3 | The KiwiSaver Nobody Claimed | You had $41,000 in KiwiSaver. No nominated beneficiary. It took 18 months and two court appearances to release it. | +2 Chaos + −$8,000 |
| RT4 | The Unnamed Guardian | Your children needed a plan. There wasn't one. You always thought you had more time. | +3 Chaos |
| RT5 | The Cancelled Policy | You cancelled the life insurance to save $52 a month. The family needed $120,000. The maths did not work out. | +2 Chaos + −$28,000 |

---

## 10. Win Condition & Scoring

- **Winner:** The player with the **lowest chaos score** at the end. "The most organised corpse wins."
- **Chaos rating labels** shown at game over:

| Chaos score | Label |
|---|---|
| 0–3 | Orderly Departure |
| 4–7 | Mild Disorder |
| 8–12 | Significant Chaos |
| 13+ | Absolute Catastrophe |

- **Estate value** is tracked throughout but does not affect the win condition — it is narrative context only.
- **Regret tiles** are counted separately and shown in the final results but do not add to the chaos score beyond the chaos effect of the card itself.

---

## 11. Known Issues & Flags for Review

The following items were identified during the audit as warranting factual or mechanical review:

| # | Item | Issue | Suggested action |
|---|---|---|---|
| 1 | Space 3 — Ambulance Bill ($1,100) | St John callout fee is ~$98–$110 for a standard emergency response. $1,100 is closer to an air ambulance or extended transport. | Replace with Westpac Rescue Helicopter scenario (~$4,500 without membership) or correct to ~$98 with membership angle |
| 2 | Space 9 — Will or No Will Fork | Fork label promises branching outcomes but currently applies the penalty to all players regardless of `hasWill` flag. The preparedness modifier reduces chaos by 1 in the paperwork section, but the fork itself does not branch. | Wire `hasWill` flag into fork space to skip penalty for prepared players |
| 3 | C2 — The 2003 Will (Wills Act 2007) | The card states an old will "may still be valid" under the Wills Act 2007. This is broadly correct — the Act allows courts to admit informal documents — but the specific claim that an ex-partner named in a pre-2007 will retains entitlement needs checking against the Family Protection Act 1955 and the Property (Relationships) Act 1976. | Verify whether marriage/de facto relationship dissolution automatically revokes a will under NZ law (it does not automatically in NZ, unlike some jurisdictions) |
| 4 | C4 — Administration Act Intestacy (de facto partner) | The card states a de facto partner of 8 years "gets nothing automatically." Under the Administration Act 1969, a de facto partner of 3+ years does have a claim, but must apply to the court — it is not automatic. The card's flavour is directionally correct but slightly imprecise. | Clarify: "gets nothing automatically — they must apply to the court under the Administration Act 1969" |
| 5 | KiwiSaver "frozen pending probate" (Document 6 description) | KiwiSaver funds without a nominated beneficiary do not go through probate in the traditional sense — they are paid to the estate, but the provider requires a grant of administration before releasing them. The 12–18 month figure is plausible but depends on estate complexity. | Verify with Inland Revenue / KiwiSaver provider guidance; consider softening to "months of delay" rather than a specific figure |
| 6 | Regret tile double-chaos bug | In `resolveCard`, regret cards apply `card.effect.chaos` once via the standard chaos handler, then a second time via the `card.type === "regret"` branch. This means regret card chaos is applied twice. | Fix: remove the duplicate chaos application in the regret branch |
| 7 | Space 14 — NZ Super Stopped | The card says MSD recovered an overpayment from the estate. NZ Super ceases on the date of death; any payments made after that date are technically recoverable. This is accurate. | No change needed — factually correct |
| 8 | Space 30 — The Bach Decision | The sublabel says "+2 Chaos or −2 Chaos" but the effect always applies +2 Chaos. The −2 option is not implemented. | Either implement a player choice (sell vs keep) or change the sublabel to "+2 Chaos" |
| 9 | Oranga Tamariki (C6, Space 27) | The game implies OT involvement is automatic when no guardian is named. In practice, OT becomes involved only if there is no family member able and willing to care for the children. The scenario is plausible but not universal. | Consider softening to "Oranga Tamariki may become involved" rather than "is now involved" |
| 10 | Burial at Waikumete (R4) | Waikumete Cemetery is in Auckland (Henderson). This is a real, well-known NZ cemetery — a nice specific detail. | No change needed — good NZ grounding |
| 11 | Tangihanga costs ($4,200, Space 43) | Tangihanga costs vary enormously depending on iwi, location, duration, and whether the marae charges. $4,200 is plausible for a three-day tangihanga but may be low for some contexts. | Consider adding a note that costs vary, or making this a card draw rather than a fixed cost |
| 12 | Average NZ funeral cost ($10,500, Space 39) | The Funeral Directors Association of NZ cites average costs of $8,000–$15,000 depending on type. $10,500 is within range. | Broadly accurate — no change needed |
| 13 | Property Law Act 2007 (C3) | The card correctly cites the Property Law Act 2007 as the mechanism for forcing a sale of co-owned property. This is accurate. | No change needed |
| 14 | "No next-of-kin listed" (Space 2, Young Professional persona) | The game treats this as a crisis. In NZ hospitals, if no next-of-kin is listed, staff attempt to locate family through other means. The scenario is realistic but the consequence could be more specific. | Consider specifying: "The hospital contacted the police to locate next of kin" |

---

## 12. Legal References Used in the Game

| Reference | Where used | Accuracy note |
|---|---|---|
| Administration Act 1969 | Space 7, C4, Space 23 chronicle | Correct — governs intestate estates in NZ |
| Wills Act 2007 | C2 | Correct — governs validity of wills; informal documents may be admitted |
| Property Law Act 2007 | C3 | Correct — s.339 allows co-owner to apply for court-ordered sale |
| Burial and Cremation Act 1964 | Space 39, Bach Owner persona, Funeral Plan description | Correct — and the note about it being unchanged since 1964 aligns with known regulatory inertia |
| Family Protection Act 1955 | Not explicitly cited but implied in intestacy scenarios | Not cited — consider adding where relevant |
| Property (Relationships) Act 1976 | Not cited | Relevant to de facto partner claims — consider citing in C4 |
| Companies Act | Space 33 chronicle | Correct — Companies Act governs what happens to a company on director/shareholder death |
| Oranga Tamariki Act 1989 | Implied in C6, Space 27 | Not cited by name — could strengthen the scenario |

---

*This document was generated from a full read of `gameData.ts`, `useGameState.ts`, `PreparednessDeclare.tsx`, and `GameScreen.tsx` on 22 May 2026.*
