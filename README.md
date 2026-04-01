# Project Dunstall Mirror
## Ezone Global / HopeTex / Net Fusion update

**Release target:** `v2026.04.01-ezone-hopetex-update`  
**Repository:** `RE3CON/Project-Dunstall-Mirror`  
**Prepared for manual upload**

This update packages a conservative, source-led case study on the bridge between:

- the **HopeTex / Hopetexx** formation-and-payments offer stack,
- **Net Fusion Tech Services Limited** at **Office 372, 85 Dunstall Hill**,
- **Ezone Global** complaint data, and
- the repeated **FedEx-linked delivery-evidence disputes** described in public buyer reports.

## What is new in this update

- A fresh PDF case study: `Project_Dunstall_Mirror_Ezone_HopeTex_Bridge_Report_2026-04-01.pdf`
- A relationship matrix CSV: `ezone_hopetex_bridge_relationship_matrix_2026-04-01.csv`
- An enriched cluster CSV:
  `85_Dunstall_Hill_COMPLETE_OSINT_merged_UPDATED_2026-04-01_ezone_manual_upload.csv`
- Three new visual assets for the repo README:
  - `assets/hopetex_package_stack.png`
  - `assets/ezone_customer_flow.png`
  - `assets/wolverhampton_hub_map.png`

---

## Key findings

### 1) HopeTex / Hopetexx publicly markets entity + onboarding infrastructure
The public package pages show two linked tracks:

- **US LLC packages** on `hopetexx.com/packages`, including:
  - registered agent
  - mailing address
  - EIN
  - business bank account consultation
  - business payment merchant consultation
  - PayPal business account consultation

- **UK LTD packages** on `hopetex.co.uk/product-category/packages/`, including:
  - Companies House fee included
  - registered office + director service address
  - company authentication code + UTR
  - UK mobile number
  - claimed PayPal / Stripe / Wise approvals
  - merchant-use guidance
  - in higher tiers, proxy / anti-detect tooling

### 2) Net Fusion is the clearest verified UK-LTD bridge
Public records place **Net Fusion Tech Services Limited** at:

> Office 372, 85 Dunstall Hill, Wolverhampton, England, WV6 0SR

That address appears both in Companies House and on the company's public contact page.

### 3) The cleanest Ezone payment bridge is complaint-based, but concrete
A BBB Scam Tracker report for **Ezone Global** states that the buyer paid through **PayPal** and that **Net Fusion Tech Services Limited** appeared on the payment confirmation.

This is the strongest current public bridge between:
- a consumer-facing Ezone storefront, and
- a real UK limited company inside the Dunstall Hill cluster.

### 4) FedEx appears repeatedly in the dispute phase
Trustpilot and BBB complaint material describes a recurring pattern where buyers say they received:
- someone else's tracking number,
- delivery to another address,
- a proof-of-delivery image that did not match the expected item,
- or a package weight that looked implausible for the product ordered.

That supports a narrow, evidence-led statement:
**delivery evidence is repeatedly disputed and appears central to the refund / chargeback stage.**

---

## Visuals

### HopeTex package stack
![HopeTex package stack](assets/hopetex_package_stack.png)

### Ezone customer flow
![Ezone customer flow](assets/ezone_customer_flow.png)

### Wolverhampton hub map
![Wolverhampton hub map](assets/wolverhampton_hub_map.png)

---

## Evidence ladder

### Verified public facts
- HopeTex / Hopetexx package pages advertise UK LTD and US LLC formation products with payment-related consultation and onboarding language.
- Hopetexx publicly lists a UK presence at **85 Dunstall Hill, Wolverhampton WV6 0SR**.
- Net Fusion Tech Services Limited is a real UK company at **Office 372, 85 Dunstall Hill**.
- Trustpilot hosts a current `ezoneglobal.us` page with 30 reviews and a 1.5 / 5 TrustScore.
- BBB complaint **1199897** states that **Net Fusion Tech Services Limited** appeared on an Ezone Global payment confirmation.
- BBB complaint **1236472** describes a wrong-address / wrong-weight / wrong-parcel FedEx pattern.

### Complaint-based findings
- PayPal payment reportedly confirmed to **"Muhammed Shafig"** in one Trustpilot complaint.
- Buyers repeatedly describe:
  - fake or mismatched FedEx tracking,
  - different delivery addresses,
  - unresponsive support.

### Low-confidence / watchlist findings
- `Ezone Supply Partners Limited` appears in the cluster CSV by name, but no direct public bridge to `ezonesglobal` was verified in this pass.
- The broader thesis of a single centrally managed fraud stack remains an analytic hypothesis unless reinforced by processor, carrier, court, or law-enforcement records.

---

## Files in this update

| File | Purpose |
|---|---|
| `Project_Dunstall_Mirror_Ezone_HopeTex_Bridge_Report_2026-04-01.pdf` | Case study PDF |
| `ezone_hopetex_bridge_relationship_matrix_2026-04-01.csv` | Focused evidence matrix |
| `85_Dunstall_Hill_COMPLETE_OSINT_merged_UPDATED_2026-04-01_ezone_manual_upload.csv` | Enriched cluster CSV |
| `RELEASE_NOTES_v2026.04.01-ezone-hopetex-update.md` | Release text |
| `assets/*.png` | README visual assets |

---

## Suggested upload order

1. Upload `assets/`
2. Replace `README.md`
3. Upload the PDF
4. Upload the relationship matrix CSV
5. Upload the enriched cluster CSV
6. Add the release notes text to the GitHub release body

---

## Working note

This update intentionally separates:
- **open-web facts**
- **user / victim complaint evidence**
- **analytic inference**

That keeps the repo useful for OSINT while reducing the risk of presenting complaint narratives as fully adjudicated fact.
