<div align="center">

# 🇮🇳 India GST & Income Tax Calculator

### GST (add/remove, CGST·SGST·IGST split) + Income Tax new regime, FY 2025-26 — two calculators in one

[![View Live Demo](https://img.shields.io/badge/▶_Try_It_Live-c2410c?style=for-the-badge&logoColor=white)](https://jithinjolly2000-maker.github.io/india-tax-calculator/)

![Built with](https://img.shields.io/badge/Built_with-Vanilla_JS-f7df1e?style=flat-square&logo=javascript&logoColor=black)
![No dependencies](https://img.shields.io/badge/Dependencies-none-0a7a52?style=flat-square)
![Privacy](https://img.shields.io/badge/Privacy-100%25_in--browser-17854a?style=flat-square)
![Rates](https://img.shields.io/badge/FY-2025--26_·_GST_2.0-c2410c?style=flat-square)

</div>

---

Two Indian tax calculators in one page.

## 🧾 GST Calculator

- **GST 2.0 slabs** — 0% / 5% / 18% / 40% (effective 22 Sep 2025), plus a custom rate
- **Add GST** (exclusive → inclusive) or **Remove GST** (inclusive → net)
- **CGST + SGST** split for intra-state, or **IGST** for inter-state
- Net / GST / invoice-value breakdown

## 💸 Income Tax Calculator — configurable & future-proof

Ships with the **New Regime (FY 2025-26)** and **Old Regime** slabs, but the whole engine is
**data-driven and editable** — so when a budget changes the rates, you update the numbers in
seconds, no code change:

- **Editable slab grid** — add / remove / change any slab, standard deduction, §87A rebate (max + income limit), and cess, right in the page; recalculates live
- **Save / load regimes** — export your setup as a JSON file and re-import it later, or save multiple named regimes and switch between them
- **Old vs New comparison** — enter income once, see both side by side with how much the better choice saves
- Full **slab-wise breakdown** + take-home

Ships pre-loaded with: nil up to ₹4L … 30% above ₹24L, ₹75,000 standard deduction, §87A rebate
up to ₹60,000 (income up to ₹12L taxable effectively tax-free), 4% cess.

> **Why not auto-fetch the latest rates?** There's no official government rates API, and a static
> site can't reliably pull live data — a tool that *claimed* to would silently break. Instead the
> rates are **editable data you control**, which stays accurate with a 30-second edit.

## ✅ Verified

The income-tax engine was checked against the published reference points — e.g. ₹12.75 L
salaried → **₹0**, ₹16 L → **₹1,24,800**, ₹25 L → **₹3,43,200**. The GST add/remove math
round-trips exactly.

## ⚠️ For planning, not filing advice

Rates and rules change each budget and have exceptions (surcharge on high incomes, special-rate
incomes, old-regime deductions). **Confirm with a CA or the Income Tax portal before filing.**
This tool does the arithmetic reliably; it isn't tax advice.

## 🧰 Tech

- **Vanilla HTML / CSS / JavaScript** — no frameworks, no dependencies, one `index.html`
- Hosted free on **GitHub Pages**; nothing is uploaded

## ▶️ Run locally

```bash
start index.html      # Windows — no build step
```

<div align="center">

---

**Built by Jithin J** · [GitHub](https://github.com/jithinjolly2000-maker) · [LinkedIn](https://www.linkedin.com/in/jithin2k)

</div>
