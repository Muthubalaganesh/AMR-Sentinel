# AMR Sentinel – Agentic Antimicrobial Resistance Intelligence

## Overview
AMR Sentinel is an agentic analytics solution built on Tableau Next that proactively detects emerging antimicrobial resistance (AMR) threats, assesses their impact on pharmaceutical drug pipelines, and recommends actionable mitigation strategies. The platform transforms phenotypic surveillance data into early warnings and prescriptive insights, enabling pharmaceutical R&D, clinical operations, and stewardship teams to make faster, safer decisions.

## Problem Statement
Antimicrobial resistance is a major risk to pharmaceutical innovation. Late-stage clinical trials and recently launched antibiotics frequently fail due to unexpected resistance patterns, resulting in multi-billion-dollar losses and delayed patient access. Existing AMR surveillance systems are largely reactive, relying on static reports and delayed intelligence, which limits their usefulness for proactive pipeline protection.

## Solution
AMR Sentinel addresses this challenge by delivering a proactive, agentic analytics workflow using Tableau Next. The solution continuously monitors resistance trends, translates scientific risk into business impact, and provides clear, prescriptive recommendations—all within a unified Tableau dashboard experience.

The system follows a **Detect → Explain → Act** paradigm:
- **Detect** emerging resistance spikes relevant to Phase III trials
- **Explain** the scientific and financial implications of these risks
- **Act** by recommending immediate mitigation strategies

## Key Features
- Early warning detection of resistance spikes using time-series analysis  
- Regional AMR risk prioritization optimized for executive decision-making  
- Pipeline impact vs resistance assessment for asset-level risk visibility  
- Executive KPI metrics with historical trend context  
- Agentic recommended actions embedded directly within dashboards  
- Designed for integration with Inspector, Concierge, and Agentforce workflows  

## Dashboard Structure
The AMR Sentinel dashboard is organized into three logical zones:

### Zone 1 – Early Warning
- Regional AMR heatbars for rapid geographic risk prioritization
- Resistance spike detection based on historical trend deviations

### Zone 2 – Impact Assessment
- Pipeline impact vs resistance scatter analysis
- Pathogen and drug class threat rankings
- KPI metrics summarizing exposure and trend direction

### Zone 3 – Prescriptive Action
- Recommended action tables driven by risk severity
- Identification of low-risk regions for trial reallocation

## Technology Stack
- **Platform:** Tableau Next (Salesforce Platform)
- **Visualization & Analytics:** Tableau Dashboards and Calculated Fields
- **Data Modeling:** Semantic Models
- **Agentic Concepts:** Inspector, Concierge, Agentforce (conceptual integration)
- **Dataset:** Fully synthetic phenotypic surveillance data modeled on real-world standards (e.g., WHO GLASS)

## Dataset
The dataset used in this project is fully synthetic and created solely for hackathon purposes. It simulates phenotypic antimicrobial resistance surveillance data across:
- Regions
- Clinical trial sites
- Pathogens
- Drug classes
- Time periods
- Resistance percentages
- Pipeline impact scores

No proprietary, confidential, or personal data is included.

## Setup & Access
This project runs entirely within a provisioned Salesforce org using Tableau Next.

To evaluate the project:
1. Access the Tableau dashboards via the provided Salesforce org credentials (included in the Devpost submission).
2. Navigate to the AMR Sentinel dashboard.
3. Interact with filters, metrics, and recommended action views to explore the agentic workflow.

No local setup or external dependencies are required.

## APIs & Developer Tools Used
- Tableau Next
- Tableau Semantic Models
- Tableau Calculated Fields
- Tableau Dashboards & Filters
- Salesforce Platform (Org-based deployment)

No external APIs or third-party SDKs were used.

## Future Improvements
With additional time, the following enhancements could be implemented:
- Integration of live public AMR surveillance datasets
- Automated Agentforce workflows for escalation and task creation
- Predictive modeling of resistance trajectories
- Role-based dashboard views for R&D, clinical, and regulatory teams

## Hackathon Information
This project was created exclusively for the Tableau Hackathon and complies with all submission requirements, including originality, platform usage, and intellectual property guidelines.

## One-Line Pitch
AMR Sentinel uses Tableau Next’s agentic analytics to detect emerging antimicrobial resistance threats early and guide pharmaceutical teams toward faster, safer, and smarter decisions.
