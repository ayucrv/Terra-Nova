# Terra Nova

> A data-backed, policy-aligned, impact-driven waste-to-fuel platform transforming India's municipal solid waste into clean energy.

---

## About The Project

**Terra Nova** is an integrated **Waste-to-Fuel (WtF)** ecosystem designed to address India's mounting waste crisis while generating sustainable alternative fuels. Every day, **31,449 tonnes** of urban municipal waste remain untreated — equivalent to over **11 million tonnes annually**. Terra Nova bridges this gap by converting waste into **Compressed Biogas (CBG)** and **Refuse-Derived Fuel (RDF)**, creating one of India's largest untapped circular economy opportunities.

This repository contains the **Terra Nova Operations Dashboard** — a real-time monitoring and analytics platform for waste-to-fuel operations, built for municipalities, plant operators, and stakeholders to track collection, segregation, processing, and offtake in real time.

---

## The Problem

Waste-to-Fuel solutions in India have not scaled due to execution gaps across the value chain:

| Gap Area | Key Challenges |
|---|---|
| **Feedstock** | Poor source segregation, high moisture, inconsistent quality |
| **Financial** | High CAPEX, slow fund disbursal, limited low-cost financing |
| **Infrastructure** | Inadequate collection, lack of MRFs, high logistics costs |
| **Policy** | Complex regulations, inconsistent implementation |
| **Technology** | Technology mismatch, low project IRR, limited track record |

> **The core issue is not the lack of policy or technology, but execution gaps across the value chain.**

---

## Our Solution

### Hybrid Waste-to-Fuel Ecosystem

```
Waste Sourcing → Segregation & Processing → Fuel Production → Logistics & Supply → End Customers
     ↓                ↓                        ↓                  ↓                ↓
Municipalities      MRFs & Pre-treatment   Biomethanation    Efficient Transport   Cement Plants
Bulk Generators     Quality Assurance      RDF Production    Optimized Delivery    OMCs
Institutions                                                                       City Gas Networks
```

### Two Core Fuels

| Fuel | Production | Primary Customers |
|---|---|---|
| **CBG (Compressed Biogas)** | Biomethanation of organic waste | IOCL, BPCL, HPCL, City Gas Networks |
| **RDF (Refuse-Derived Fuel)** | Drying, shredding, pelletizing of dry waste | Cement Plants, Brick Kilns, Steel Industries |

---

## Terra Nova Dashboard

The **Terra Nova Operations Dashboard** is the digital nerve center of Terra Nova's waste-to-fuel network.

🔗 **Live Demo:** [https://terra-nova-flow.lovable.app/](https://terra-nova-flow.lovable.app/)

### Dashboard Features

- **📊 Real-time Operations Metrics**
  - Network utilization percentage
  - Tonnes in pipeline
  - Landfill diversion tracking
  - Average segregation score
  - CO₂e avoided
  - Plant throughput (TPD)
  - Contracted demand (TPD)

- **🗺️ Live Operations Map**
  - Interactive map showing plant locations and offtaker networks across states

- **♻️ The Waste Journey Tracker**
  - End-to-end batch tracking from collection to combustion:
    1. **Collected** — Doorstep + bulk pickup
    2. **Segregated** — Wet / dry / inert split
    3. **Hauled** — Optimized routing
    4. **Processed** — RDF · Bio-CNG · Syngas
    5. **Matched** — Offtaker contracts
    6. **Combusted** — Kilns replace coal

- **🏛️ Municipality View**
  - Dedicated dashboard view for Urban Local Bodies (ULBs) to monitor collection coverage, segregation quality, and landfill diversion

---

## System Architecture

```
┌─────────────────────────────────────────────────────────────────┐
│                     TERRA NOVA DASHBOARD                        │
│  ┌─────────────┐  ┌─────────────┐  ┌─────────────────────────┐ │
│  │  Operations │  │    Live     │  │    Waste Journey        │ │
│  │   Metrics   │  │    Map      │  │      Tracker            │ │
│  └─────────────┘  └─────────────┘  └─────────────────────────┘ │
└─────────────────────────────────────────────────────────────────┘
                              │
┌─────────────────────────────────────────────────────────────────┐
│                      API / Backend Layer                        │
│         (Real-time data ingestion from plant IoT sensors,       │
│          GPS trackers, weighbridges, and ERP systems)           │
└─────────────────────────────────────────────────────────────────┘
                              │
        ┌─────────────────────┼─────────────────────┐
        ▼                     ▼                     ▼
┌──────────────┐    ┌────────────────┐    ┌────────────────┐
│   Plants     │    │   Logistics    │    │   Offtakers    │
│  (CBG + RDF) │    │   (Fleet GPS)  │    │ (Cement/OMCs)  │
└──────────────┘    └────────────────┘    └────────────────┘
```

---

## Market Opportunity

| Metric | Value |
|---|---|
| Urban MSW Generated Daily | **161,157 TPD** |
| Unprocessed Daily | **~31,449 TPD** |
| SBM-U 2.0 Project Value | **₹23,549 Cr** |
| CBG Plants Target (SATAT) | **5,000 by 2023** |
| CBG Plants Commissioned | **217 (as of July 2026)** |
| RDF Share in Cement Kilns | **<1%** (Target: 20-25% by 2030) |

---

## Revenue Model

| Stream | Share | Description |
|---|---|---|
| **Fuel Sales** (CBG + RDF + Pyrolysis Oil) | 40% | Sale to OMCs, cement plants, industries |
| **Municipal Tipping Fees** | 20% | Paid by ULBs for scientific waste processing |
| **Carbon Credits** | 15% | Verified emission reductions |
| **Organic Fertilizer (FOM)** | 10% | Sale to farmers & agri companies |
| **ESG Platform Subscription** | 10% | SaaS revenue from ESG reporting |
| **Plastic Recovery Certificates** | 5% | Extended producer responsibility credits |

---

## Implementation Roadmap

| Phase | Timeline | Focus |
|---|---|---|
| **Pilot & Foundation** | 0-6 Months | Test · Learn · Validate |
| **Infrastructure Build-Up** | 6-18 Months | Strengthen · Expand · Integrate |
| **Market Expansion** | 18-36 Months | Scale · Partner · Monetize |
| **Scale & Optimization** | 36-60 Months | Optimize · Standardize · Excel |
| **National Scale** | 60+ Months | Lead · Impact · Transform |

---

## Impact That Matters

### Environmental
- **~1.25 Mn tCO₂e** emissions avoided annually
- **~2.10 Lakh tonnes** of methane emissions prevented annually
- **~3.65 Lakh tonnes** of waste diverted from landfills every year
- **~90-110 Mn liters** of fossil fuel equivalent energy produced annually

### Economic
- **₹60-65 Cr** annual revenue potential (at stabilized operations)
- **28-32%** EBITDA margin
- **200+** direct & indirect jobs created per 100 TPD plant
- **18-22%** IRR | **4.5-5.5 years** payback

### Social
- Improved public health through cleaner air & water
- Livelihood generation across collection, processing & operations
- Capacity building & awareness on waste segregation
- Inclusive growth through ULB, SHG, and local entrepreneur partnerships

---

## Tech Stack
| Layer | Technology |
|---|---|
| Framework | React + TypeScript (Vite) |
| Styling | Tailwind CSS + shadcn/ui |
| Animation | Framer Motion |
| Icons | Lucide React |
| Charts | Recharts |
| Map | Custom SVG (India outline, animated markers/routes) |
| Backend / DB | Supabase (PostgreSQL) |
| Data Fetching | TanStack React Query |
---


## References & Policy Alignment

- **SATAT Scheme** — Sustainable Alternative Towards Affordable Transportation
- **SWM Rules 2026** — Mandatory segregation, RDF usage & reduced landfilling
- **SBM-U 2.0** — Swachh Bharat Mission Urban 2.0 (Scientific Waste Management)
- **MNRE Guidelines** — Capital subsidy & priority sector lending for CBG projects
- **NITI Aayog 2026 Roadmap** — 20-25% Thermal Substitution Rate (TSR) by 2030
- **Net Zero 2070** — India's commitment driving circular economy & alternative fuels

---

## 👥 Team

**Team Aivelle** 

> *"Can Garbage Become India's Fuel?"*

---


<p align="center">
  <em>Terra Nova — Powering Tomorrow</em>
</p>
