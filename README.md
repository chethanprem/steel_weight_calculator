# steel_weight_calculator
# 🔩 Steel Weight Calculator

A fast, offline-ready web app for calculating the weight of structural steel sections — built for steel traders, fabricators, and processing units.

No installation. No backend. Just open the HTML file in any browser.

---

## ⚙️ Supported Sections

| Section | Inputs |
|---|---|
| **MS Plates / Sheets** | Thickness, Width, Length (mm), Nos |
| **MS Channels (ISMC)** | Size, Length (6/12 mtr), Nos |
| **RS Joists / Beams (ISMB)** | Size, Length (6/12 mtr), Nos |
| **Purlin** | Length (mtr), Nos |
| **Roofing Sheet** | Type (CC / BGL), Length (mtr), Nos |
| **MS Equal Angles (ISA)** | Size, Thickness, Length (6/12 mtr), Nos |
| **MS Flats (ISF)** | Size, Thickness, Length (6/12 mtr), Nos |
| **Decking Sheet** | Thickness (0.8 / 0.9 / 1.0 / 1.2 mm), Length (mtr), Nos |
| **MS Pipes** | OD or NB (IS standard), Wall Thickness, Length (mtr), Nos |

---

## 📐 Formulas Used

- **MS Plates** — `THK × WIDTH × LENGTH × NOS × 7.85 ÷ 1,000,000,000`
- **Channels / Beams / Angles / Flats** — `Wt/Mtr × Length × Nos ÷ 1000`
- **Purlin** — `Length × 5.5 × Nos ÷ 1000`
- **Roofing CC** — `4.5 × Length × Nos ÷ 1000`
- **Roofing BGL** — `4.35 × Length × Nos ÷ 1000`
- **Decking** — `Factor × Length × Nos ÷ 1000` (factor by THK)
- **Pipes** — `(OD − WT) × WT × 0.02466 × Length × Nos ÷ 1000`

All results in **Metric Tons (MT)**.

---

## 📋 Bill of Materials (BOM)

- Add any calculated item to the BOM with one click
- Running grand total across all sections
- Remove individual items
- Export to **CSV** for use in Excel or any spreadsheet

---

## 📱 Mobile Friendly

- Fully responsive layout
- Floating BOM button with slide-up drawer on mobile
- Works on Android and iOS browsers — no app install needed

---

## 🚀 How to Use

### Option 1 — Direct
Download `steel_weight_calculator.html` → open in any browser. Done.

### Option 2 — Live via GitHub Pages
Visit: `https://<your-username>.github.io/<repo-name>/steel_weight_calculator.html`

---

## 🏗️ Built With

- Pure HTML, CSS, JavaScript — zero dependencies
- IS standard weight tables hardcoded (ISMC, ISMB, ISA, ISF)
- NB → OD lookup based on IS 1239 pipe standards

---

## 📌 Use Cases

- Dispatch weight estimation
- Loading/unloading planning
- Material indent preparation
- Customer quotation support
- Site material reconciliation

