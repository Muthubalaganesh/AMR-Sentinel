# AMR Sentinel – Semantic Model Description

## Purpose
The semantic model in AMR Sentinel provides a trusted, business-ready representation of antimicrobial resistance (AMR) surveillance data. It bridges raw phenotypic resistance measurements with pharmaceutical decision-making by standardizing definitions, aggregations, and risk classifications used across dashboards and agentic workflows.

## Core Entities

### Region
Represents the geographic area associated with clinical trial sites and resistance reporting.
- Examples: South Asia, North America, Europe

### Clinical Trial Site
Individual sites participating in pharmaceutical clinical trials.
- Linked to Region and Trial Phase

### Pathogen
Bacterial species monitored for antimicrobial resistance.
- Examples: *E. coli*, *K. pneumoniae*

### Drug Class
Class of antimicrobial agents used in clinical trials.
- Examples: Beta-lactams, Carbapenems

### Time Period
Yearly reporting periods used for trend analysis and anomaly detection.

## Measures

### Resistance Percentage (`resistance_percentage`)
- Definition: Percentage of isolates resistant to a given drug class for a specific pathogen and region.
- Aggregation: Average
- Usage: Core indicator for resistance severity and spike detection.

### Pipeline Impact Score (`pipeline_impact_score`)
- Definition: Composite score representing the business and clinical importance of a trial asset.
- Aggregation: Average
- Usage: Quantifies potential financial and strategic impact of resistance trends.

## Derived Intelligence

### Trial Risk Level
A semantic classification that combines scientific risk and business impact.

Logic:
- **Critical**: High resistance and high pipeline impact
- **Elevated**: Moderate resistance or moderate pipeline impact
- **Stable**: Low resistance and low pipeline impact

This classification is used consistently across all dashboards for color encoding, filtering, and recommended actions.

## Temporal Modeling
Historical data (2018–2025) is retained to establish baselines for trend analysis. The operational dashboard view focuses on the current year (2025), while historical periods support anomaly detection and contextual explanations.

## Agentic Alignment

The semantic model is designed to support agentic analytics concepts:
- **Concierge** relies on semantic definitions to explain risk drivers in natural language.
- **Agentforce** consumes standardized risk levels and recommended actions to enable workflow automation.

## Data Governance
All data used in this project is synthetic and created solely for hackathon purposes. The semantic model enforces consistent definitions to ensure clarity, trust, and repeatability across analytical workflows.

## Design Principles
- Business-first terminology
- Consistent aggregations across views
- Clear separation between raw measures and derived intelligence
- Agent-ready semantics enabling explainability and action


