#  Case Study: Optimizing Global VoIP & Virtual Number Pricing for Margin Growth at Scale

## 📈 Objective
Design a **dynamic pricing framework** for AVOXI’s global communications portfolio — including **virtual phone numbers**, **SIP trunks**, and **VoIP calling plans** — to maximize profitability while remaining competitive across multiple geographies and carrier cost structures.

---

## 📈 Background
AVOXI provides cloud-based communications solutions to enterprises worldwide, with pricing influenced by:
- Carrier rates  
- Destination-based costs  
- Competitive market benchmarks  

**Challenges:**
- Highly variable **carrier termination costs** across 160+ countries  
- Competitors offering **aggressive discounts** in high-demand destinations  
- Promotions and bundles lacking consistent **ROI measurement**  

---

## 📈 Methodology

### 1️⃣ Data Consolidation & Cleaning
- Merged **18 months** of CDR (Call Detail Record) data, carrier invoices, and customer subscription history  
- Standardized rate sheets from multiple carrier partners to track cost volatility  
- Pulled competitor VoIP plan pricing and virtual number rental fees via market research  

### 2️⃣ Pricing Trend & Elasticity Analysis
- Used **SQL** to segment products by **destination code** and **service type** (DID rental, outbound VoIP, inbound toll-free)  
- Calculated **price elasticity** for top 50 destinations to identify markets where small price changes had outsized impact on demand  

### 3️⃣ Competitive Benchmarking
- Compared AVOXI’s **virtual phone number** and **outbound calling** rates against top 5 global competitors in each region  
- Created a **Competitor Price Index** to monitor shifts weekly  

### 4️⃣ Dynamic Pricing Model
- Developed **Python-based pricing rules** that adjusted rates based on:  
  - Carrier cost changes exceeding ±3%  
  - Competitor median rate deviations  
  - Seasonal demand spikes (e.g., holidays in target regions)  
- Integrated with **Looker** to auto-flag SKUs needing pricing review  

### 5️⃣ Scenario Simulation
- Modeled 3 strategies:  
  1. **Aggressive Price Matching** for high-churn destinations  
  2. **Value-Based Premium Pricing** for low-competition, inelastic destinations  
  3. **Bundle Optimization** — pairing inbound DIDs with outbound call credits  

---

## 📈 Key Insights
- **Elasticity split:** Outbound call rates to certain APAC countries were highly elastic — demand dropped >15% when prices rose by $0.01/min  
- **Vendor pricing volatility:** Two Tier 1 carriers accounted for 70% of high-cost fluctuations; quarterly rate locks could protect margins  
- **Promotion ROI:** “Free month DID rental” campaigns underperformed in North America but drove strong conversions in LATAM markets  

---

## 📈 Results (3-Month Pilot)
- **+9.2% gross margin** improvement on optimized destinations  
- **+11% DID activations** in competitive regions  
- **Reduced pricing decision lead time** from 5 days to <6 hours with automated Looker alerts  
- Identified **$320K annualized savings** through carrier contract renegotiations  

---

## 📈 Skills & Tools Demonstrated
- **Industry-specific analysis:** Carrier rate benchmarking, destination-based pricing, DID activation trends  
- **Technical:** SQL (data extraction from CDRs), Excel Power Query & Advanced Formulas (dynamic pricing simulation), Excel (scenario modeling), Looker (real-time dashboards)  
- **Strategic collaboration:** Worked with Carrier Relations to optimize vendor contracts and with Finance to validate revenue impact  

---

## 📈 Why This Fits AVOXI
This project mirrors AVOXI’s **real-world pricing challenges** — balancing profitability with competitive rates in a **multi-carrier, global VoIP environment**. It demonstrates readiness to contribute from day one in:
- Pricing optimization  
- Vendor trend analysis  
- Competitive benchmarking  

---
