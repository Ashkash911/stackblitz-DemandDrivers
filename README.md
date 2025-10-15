# Demand Drivers Documentation

## Introduction

### What is Demand Drivers?
Demand Drivers is an integrated Marketing Mix Modeling platform that transforms marketing measurement from periodic consultant-driven projects into a continuous, always-on decision system. It unifies data preparation, modeling, simulation, and planning into one automated workflow.

### Why It Matters
Traditional MMM projects take months, cost hundreds of thousands, and deliver insights too late for course correction. Demand Drivers enables real-time measurement and optimization—so marketers can adjust budgets and campaigns while they run.

### Positioning & Target Audience
- Enterprises with annual media spend > $5M
- Sectors: CPG, Gaming, Telecom, E-commerce, Automotive, Healthcare
- Ideal users: Data Science teams, Marketing Analysts, CMOs & Finance planners

## Core Value Proposition

### From Reporting to Always-On Intelligence
Demand Drivers shifts MMM from retrospective reporting to continuous optimization. It lets brands forecast faster, simulate scenarios instantly, and bridge marketing strategy with execution.

### Key Benefits
- Continuous Modeling: No need to wait for quarterly studies.
- Integrated Planning: Forecast and allocate budgets in the same interface.
- Real-Time Optimization: React to market changes immediately.
- Full Transparency: Every model parameter is visible and editable.
- Cost Efficiency: 40% lower TCO vs. consultant MMM.
- Scalable Architecture: Supports global multi-brand deployments.

### Quantified Business Impact
- Models built in hours vs. weeks
- MMM frequency 3× higher
- Budget waste reduction ≈10%
- Improved marketing ROI 15–25%

## Platform Overview

### End-to-End Workflow
- Data Ingestion: Automated ETL or manual uploads with validation.
- Data Classification & Setup: Hierarchical variable grouping and currency normalization.
- Model Configuration: Auto-modeling engine runs 60+ iterations with Adstock, Gamma, S-Curve transformations.
- Insights & Visualization: Interactive dashboards and response curve analysis.
- Simulation & Planning: AI-powered budget optimization and forecasting.

### Core Modules
- Simulation Module – Strategic planning tool for scenario testing.
- Planning Module – Financial and execution tracking capabilities.
- Reporting Module – Visualization and KPI reporting for stakeholders.

### Platform Differentiators
- Automated intelligence (60+ iterations)
- Full methodology transparency
- Real-time data sync and continuous forecasting
- Flexible delivery (Self-Service / Full-Service / Hybrid)
- Cost-efficient scaling and unlimited model runs

## Platform Architecture & Workflow

### Technical Stack
- Backend: Python
- Frontend: React
- Infrastructure: Kubernetes cluster for scalability
- Deployment Modes: Private cloud, Public cloud, or SaaS

### Data-to-Insights Flow
- Data Ingestion → ETL integration, automated QC, harmonization
- Data Classification → Variable grouping and hierarchy setup
- Model Configuration → Auto-modeling with hyper-parameterization
- Model Publishing → Dashboards, Simulations, Planning modules
- API Integration → Exports to BI or planning tools

### Scalability & Performance
- Millions of rows supported
- Concurrent multi-user sessions
- Scenario response time < 30 seconds

## Cheatsheet – Quick Reference for Client Service Teams

### Elevator Pitch
“Demand Drivers is the always-on Marketing Mix Modeling platform that replaces slow, consultant-driven MMM cycles with rapid, transparent, AI-powered decision support. Build optimized models in hours, test unlimited scenarios, and continuously plan marketing investments with real-time intelligence.”

### Core Value Proposition
| Benefit            | Traditional MMM Challenge         | Demand Drivers Solution              |
|--------------------|------------------------------------|---------------------------------------|
| Speed              | 6-month MMM cycles                | Auto-modeling builds models in hours  |
| Cost Efficiency    | High consulting fees              | ≈40% lower total MMM cost            |
| Transparency       | Black-box methods                 | Full visibility into parameters & assumptions |
| Agility            | Quarterly refreshes               | Weekly updates + unlimited scenario testing |
| Integration        | Separate tools for modeling, planning | Unified workflow from data to decision |
| Scalability        | One-off projects                  | Continuous, enterprise-ready platform |

### Ideal Customer Profile (ICP)
- Annual marketing spend ≥ $5M
- Operates multiple channels (digital + offline)
- Requires cross-brand or multi-market measurement
- Has internal data science or analytics capability (or needs managed service)
- Wants to move from quarterly to continuous measurement

### Quantified Impact
- ⏱ 80% reduction in MMM delivery time
- 💰 ≈40% cost reduction vs. traditional approaches
- 📈 15–25% improvement in marketing effectiveness
- 🧩 3× increase in model refresh frequency

### Common Objections & Responses
| Objection                          | Response                                                                 |
|------------------------------------|--------------------------------------------------------------------------|
| "We already have an MMM vendor."   | How often can you update models? We enable weekly updates and unlimited scenarios with rollback ROI for cleaner measurement. |
| "We lack MMM expertise."           | Use our Managed Service for hands-off operation while gaining transparency and learning over time. |
| "Auto-modeling sounds like a black box." | Every parameter and transformation is visible. You can override settings based on business logic. |
| "Implementation sounds complex."   | 13-week delivery including ETL, setup & training. Start with Managed Service and transition to Self-Service. |

### Key Talking Points for Pitch
- Always-on MMM = Continuous Decision Support
- Auto-modeling (60+ iterations) → Faster Insights
- Transparency + Explainability → Client Trust
- Rollback Analysis & Long-Term Multipliers → Cleaner ROI
- Unified Planning Module → Bridges Analytics & Execution

## Core Modules

### 5.1 Simulation Module – Strategic Marketing Planning
- **Core Value**: Turn insights into action with AI-driven budget optimization.
- **Key Benefits**:
  - Test unlimited marketing scenarios before spend.
  - Optimize $50M+ budgets for maximum ROI.
  - Reduce risk through data-driven scenario planning.
- **Primary Users**: Marketing Strategy & Planning teams
- **Use Cases**: Budget allocation, competitive response, seasonal planning

### 5.2 Planning Module – Financial and Business Execution
- **Core Value**: Bridge marketing strategy and execution tracking.
- **Key Benefits**:
  - Real-time variance analysis and forecast tracking.
  - Distinguish model accuracy from execution failures.
  - Prevent 5–10% budget waste via course correction.
- **Primary Users**: Marketing Ops & Finance teams
- **Use Cases**: Execution tracking, budget control, post-campaign review

### 5.3 Reporting & Visualization
- Out-of-the-box dashboards for standard use cases.
- Drill-down KPI reporting across brands, regions, or channels.
- API integration with Tableau / Power BI / custom apps.

## Advanced Features

### Rollback Analysis
- Extends data 2+ years beyond model period to remove tail effects.
- Produces clean ROI by eliminating carry-over contamination.

### Long-Term Multipliers
- Captures 12–24 month brand building impact.
- Converts curved response functions to linear projections for clarity.

### Halo Effects (Multi-Dimensional Projects)
- Differentiates direct vs. indirect impact variables.
- Supports cross-brand and geographic spillover analysis.

### Priors Integration
- Embeds business expert knowledge into model constraints.
- Ensures coefficients stay within realistic ranges (e.g., TV ROI 1.5–3×).

### Bayesian Modeling
- Incorporates uncertainty and confidence intervals.
- Enables risk-aware decision-making based on probability distributions.

### Cross-Channel Interactions
- Measures synergy effects (TV × Digital boost).
- Models competitive and sequential channel relationships.

## Technical Deep Dive – Model Configuration

### Data Requirements
- Minimum History: 2 years (weekly) or 36 months (monthly)
- Granularity: Daily / Weekly / Monthly depending on business cadence
- Formats: Excel (.xlsx), CSV, database extracts, API feeds
- Variable Limit: No hard limit on marketing variables

### Data Classification & Setup
- Group variables by brand / channel / campaign hierarchy.
- Normalize spend across currencies and markets.
- EDA module supports automated trend and correlation checks.

### Model Forms
| Type           | Formula                  | When to Use                   | Benefit                  |
|----------------|--------------------------|--------------------------------|--------------------------|
| Additive       | Y = β₀ + β₁X₁ + β₂X₂ + … + ε | Linear, incremental relationships | Simple interpretation    |
| Multiplicative | Y = β₀ × X₁^β₁ × X₂^β₂ × … × ε | Interactive effects between channels | Captures synergies       |

### Transformation Options
- Adstock (Carryover): Captures lagged advertising effects.
- Gamma: Flexible adstock with peak lag.
- S-Curve / C-Curve / Hill / Power Curves: Handle saturation and threshold effects.
- Lag & Log Transforms: Account for delayed impact and diminishing returns.
- Exponential Decay: Models rapid drop in short-term campaign impact.

### Validation & Holdout Strategies
- Continuous Holdout: Last 8–12 weeks → tests future relevance.
- Random Holdout: 20–30% of periods → tests historical robustness.

### Quality Metrics
| Metric         | Good Range         | Purpose                     |
|----------------|---------------------|-----------------------------|
| R²             | > 0.8              | Model fit quality (variance explained) |
| Adjusted R²    | —                  | Penalty for overfitting     |
| MAPE           | < 10% in-sample, < 15% holdout | Prediction accuracy         |
| Durbin-Watson  | 1.5 – 2.5          | Residual autocorrelation check |

### Troubleshooting & Red Flags
- Negative coefficients for major channels → check seasonality controls.
- Flat response curves → verify spend variation and data quality.
- High holdout error → reduce variables or extend training window.
- Model won’t converge → scale variables / remove correlated inputs.


## Implementation & Deployment

### Delivery Models
| Model           | Description                        | Typical Timeline |
|-----------------|------------------------------------|------------------|
| Self-Service    | Client team builds models with training & support | 4–6 weeks        |
| Managed Service | Analytic Edge runs entire process end-to-end | 12–13 weeks      |
| Hybrid          | Shared responsibility for gradual transition | Custom           |

### Typical Implementation Flow
- Weeks 1–4: ETL setup and data classification
- Weeks 5–8: Model building and optimization
- Weeks 9–13: Validation, dashboard setup, training

### Success Factors
- High-quality and complete data
- Stakeholder alignment on KPIs
- Change-management for always-on measurement mindset
- Clear ownership for data refresh cycles

## Pricing & Commercial Model

### Component
| Component        | Investment            | Includes                       |
|------------------|-----------------------|--------------------------------|
| ETL Setup        | $15K – $20K (one-time) | Data integration and QC        |
| Platform License | $4.5K / user / year   | Access to reporting & simulation |
| Managed Service  | Custom quote          | Full implementation + expert support |

### Pricing Drivers
- Data volume, number of markets, modeling frequency, integration complexity.

### ROI Summary
- ≈40% reduction in total MMM costs
- Unlimited model runs at no extra iteration fee
- 2-week refresh turnaround vs. months previously

## Target Users & Personas

### Platform Users
- Data Science Teams: Model building, validation, technical optimization.
- Marketing Analytics Teams: Insight generation and scenario planning.

### Insight Consumers
- CMOs / Marketing Directors: Strategic budget decisions, ROI justification.
- Media Planners: Channel budget optimization and campaign design.
- Brand Managers: Campaign evaluation and competitive response.

### Organizational Fit
- Enterprise: Global brands with multi-market measurement.
- Standalone: Individual brands or units needing focused MMM solutions.

## Competitive Positioning

### vs. Traditional MMM Consulting
- Speed: Hours vs. weeks for model building.
- Cost: ≈40% lower total investment.
- Transparency: Open methodology vs. black box.
- Agility: Real-time updates and unlimited scenarios.

### vs. Attribution Platforms
- True incrementality vs. correlation.
- Long-term and cross-channel effects captured.
- Strategic planning capabilities included.

### vs. Internal MMM Development
- Auto-optimization (60+ iterations).
- Built-in forecasting and scenario planning.
- Continuous innovation and support.

## Success Metrics & ROI

### Platform KPIs
- Accuracy: MAPE < 10% in-sample, < 15% holdout.
- Update Speed: < 2 weeks for refresh.
- Scenario Volume: Unlimited tests.

### Business KPIs
- Cost Efficiency: ≈40% reduction in MMM costs.
- Decision Speed: Real-time vs. quarterly planning.
- Coverage Expansion: More brands modeled within same budget.

## Prospect Qualification Checklist
- ✅ Annual media spend > $5M
- ✅ Multi-channel marketing mix
- ✅ 2+ years historical data
- ✅ Need for faster measurement cadence
- ✅ Internal analytics capability or managed service willingness
- ✅ Stakeholder alignment on data-driven decision making

## MMM Foundation Concepts

### What is Marketing Mix Modeling?
Statistical technique quantifying incremental impact of marketing channels on business KPIs.

### Base vs. Incremental Sales
- Base: Organic sales without marketing.
- Incremental: Sales attributable to marketing stimuli.

### Adstock & Saturation
- Adstock captures carry-over effects.
- Saturation captures diminishing returns as spend rises.

### Media Interactions
Shows how channels amplify each other (TV + Search, etc.).

### MMM vs. Attribution
| MMM                  | Attribution             |
|----------------------|-------------------------|
| Holistic view (all media) | Last-touch digital only |
| Incrementality       | Correlation             |
| Privacy-compliant    | User-level tracking dependent |
| Long + short term    | Short term only         |

### When MMM Makes Sense
- ≥ $5M annual marketing budget.
- Mix of digital and traditional channels.
- Data available for 2+ years.
- Desire for data-driven investment decisions.

## Security & Compliance

### Data Protection
- End-to-end encryption for data in transit and at rest.

### Access Control
- Role-based permissions with audit trails.

### Regulatory Compliance
- SOC 2 and GDPR framework alignment.

### Backup & Disaster Recovery
- Automated daily backups with redundant storage.

## Support & Training (Placeholder)
- Planned Section: To cover user onboarding programs, knowledge-base links, and support SLA details for managed and self-service clients.

## Product Roadmap (Placeholder)
- Mean Centering Feature (Advanced statistical option)
- Full-Funnel Modeling (End-to-end customer journey integration)
- Deep-Dive Analytics Module (Rich drill-downs for advanced users)