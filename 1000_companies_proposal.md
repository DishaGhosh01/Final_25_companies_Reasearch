#  The 1000-Company Proposal

## Goal

Build a verified list of **1,000 ICP-qualified companies within one month** by combining structured data sources, AI-assisted research, and manual quality checks. The focus is on quality over quantity, ensuring every shortlisted company meets the eligibility criteria and is backed by reliable evidence.

# Sourcing Methods (Beyond Google Search)

To find companies matching the Federer profile across India, I would combine structured databases, government records, industry-specific sources, and AI-assisted research instead of relying only on Google searches.

## 1. MCA Databases & Business Intelligence Platforms

**Sources:** MCA filings, Zauba Corp, Tofler, Probe42, Tracxn, VCCEdge

**Why it works:**
These platforms provide verified information on company registration, directors, financials, and ownership. They help identify promoter-led businesses, estimate revenue bands, and filter companies that match the desired size and maturity.

**Limitations:**
Financial filings may have reporting delays, and operational details such as ERP adoption or manufacturing sophistication are not always visible.

---

## 2. Government & Regulatory Sources

**Sources:** ICEGATE, Startup India, GeM, EPFO records

**Why it works:**
Export records indicate companies with specialized products and global reach. Startup India highlights innovation-driven businesses, while EPFO data can signal workforce scale and growth.

**Limitations:**
Some datasets require additional filtering or paid access and may not cover every target company.

---

## 3. Industry Associations & Trade Shows

**Sources:** CII, FICCI, EEPC India, ACMA, BioAsia, CPHI India, India Lab Expo, Analytica Anacon India

**Why it works:**
Exhibitors and association members are often genuine manufacturers investing in R&D, product development, and expansion, making them strong ICP candidates.

**Limitations:**
Directories may require scraping or manual extraction and often contain duplicate records.

---

## 4. B2B Directories

**Sources:** IndiaMART, TradeIndia, ExportersIndia

**Why it works:**
These platforms make it easy to discover manufacturers in specialty biotech, diagnostics, chemicals, and industrial sectors.

**Limitations:**
Many listings belong to traders or distributors, so producer status must be verified manually.

---

## 5. LinkedIn & Job Portals

**Sources:** LinkedIn, LinkedIn Sales Navigator, Naukri

**Why it works:**
Hiring for ERP, SAP, R&D, quality, or production roles often indicates operational maturity and business growth. Leadership profiles also help evaluate decision-makers and succession planning.

**Limitations:**
Company pages may be incomplete or outdated.

---

## 6. Patent & Certification Databases

**Why it works:**
Patents, DSIR recognition, GMP approvals, and other certifications indicate technical differentiation and innovation.

**Limitations:**
Not every capable company publicly highlights these achievements.

---

## 7. AI-Assisted Research

AI tools can summarize websites, classify companies, and organize large datasets quickly. However, every AI-generated insight should be validated using official or authoritative public sources before final inclusion.

## Step 1: Build the Initial Universe

Collect approximately **8,000–10,000 companies** from multiple sources:

* MCA and Zauba databases
* Tofler and Probe42
* Startup India
* IndiaMART and TradeIndia
* Industry association directories
* Trade expo exhibitor lists
* LinkedIn company pages
* Official company websites

After collection, remove duplicates and standardize company information.

---

## Step 2: Automated Qualification Pipeline

The workflow would be:

```text
Raw Company List
        ↓
Website & LinkedIn Discovery
        ↓
Website Scraping (About, Products, Careers)
        ↓
AI-based Information Extraction
        ↓
Apply E1 & E2 Eligibility Gates
        ↓
Evaluate C3–C8 Criteria
        ↓
Qualified / Borderline / Rejected
```

Automation would extract:

* Company location
* Product specialization
* Manufacturing capability
* Leadership information
* Revenue estimates
* Hiring activity
* Certifications
* Growth indicators

---

## Step 3: Quality Control

To minimize false positives:

* Cross-check data across multiple public sources.
* Prioritize official company websites and government records.
* Flag conflicting information for manual review.
* Manually review borderline companies.
* Perform random audits on high-confidence results.

---

## Step 4: Weekly Execution Plan

### Week 1 – Data Collection

* Gather 8,000–10,000 companies.
* Remove duplicates and standardize records.

**Expected output:** ~8,500 unique companies.

### Week 2 – Automated Filtering

* Apply E1 and E2 eligibility filters.
* Scrape websites and enrich company profiles.
* Run AI-assisted evaluation.

**Expected output:** ~3,500 candidate companies.

### Week 3 – Scoring & Enrichment

* Evaluate C3–C8.
* Add decision-maker information and growth signals.
* Review uncertain cases.

**Expected output:** ~1,500 shortlisted companies.

### Week 4 – Manual Validation

* Audit borderline records.
* Verify supporting evidence.
* Finalize the top 1,000 qualified companies.

---

## Expected Funnel

| Stage                     |         Approximate Count |
| ------------------------- | ------------------------: |
| Initial sourcing          |                    10,000 |
| After deduplication       |                     8,500 |
| After E1/E2 filtering     |                     3,500 |
| After AI-assisted scoring |                     1,500 |
| After manual validation   | **1,000 final companies** |

---

## Tools

* Python for scraping and data processing
* AI assistants (Claude, Gemini, ChatGPT)
* GitHub Copilot
* LinkedIn and business intelligence platforms
* Government databases
* Official company websites

---

## Final Deliverables

* Verified spreadsheet of 1,000 ICP-qualified companies
* Evidence-backed qualification notes and scores
* Decision-maker information
* Methodology documentation
* Automation scripts and supporting code where applicable

## Conclusion

By combining automation with careful manual verification, it is possible to build a scalable yet reliable pipeline that produces a high-quality list of 1,000 ICP-qualified companies within one month while maintaining strong evidence standards and minimizing false positives.
