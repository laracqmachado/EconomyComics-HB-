# EconomyComics-HB-
# MALHA
### Supply Chain Intelligence for Brazil

**Understand what your supply chain depends on — and what happens when a critical link fails.**

MALHA is a supply chain intelligence platform that reveals direct and indirect production dependencies across Brazilian states and economic sectors.

By combining input-output economics, network analysis, and geographic visualization, MALHA transforms complex interregional economic data into an accessible tool for investigating supply chain vulnerabilities.

## The Problem

Supply chains are interconnected systems. A company's exposure to disruption does not depend only on its direct suppliers, but also on the suppliers behind them.

These indirect dependencies can hide critical concentration points and make it difficult to understand how disruptions in one region or economic sector may affect production elsewhere.

Traditional economic tables contain valuable information, but extracting and interpreting these relationships requires specialized knowledge and considerable effort.

## The Solution

MALHA makes these relationships explorable.

Users can investigate the production dependencies of a selected economic sector and state, identify important upstream connections, examine indirect dependency paths, and explore hypothetical production disruption scenarios.

The goal is to turn complex economic relationships into understandable evidence for supply chain planning.

## Core Features

Features listed here should correspond to working functionality in the submitted version.

- **Dependency Analysis:** Explore direct and indirect relationships between Brazilian states and economic activities.
- **Supplier Concentration:** Identify where relevant production inputs are geographically and economically concentrated.
- **Dependency Paths:** Understand how indirect production relationships connect regions and sectors.
- **Hypothetical Shock Simulation:** Explore how a modeled reduction in production may propagate through the interregional production network.
- **Geographic Visualization:** Investigate economic dependencies through an interactive map.
- **Risk Briefing:** Generate a concise summary of calculated results, including assumptions and limitations, if implemented.

## Data

MALHA uses the Brazilian interregional input-output database developed by IPEA and the Receita Federal.

- Geographic coverage: 27 Brazilian federative units.
- Economic coverage: 68 activities.
- Reference year: 2018.

The database represents the economic structure of Brazil in 2018. It should not be interpreted as a real-time representation of current supply chains.

## Methodology

MALHA combines complementary approaches from input-output economics and network analysis.

### Leontief Input-Output Model

The Leontief model represents how changes in final demand propagate through the production system, accounting for direct and indirect input requirements.

It helps identify upstream production dependencies.

### Hypothetical Extraction Method

The hypothetical extraction approach investigates the structural importance of a region or sector by examining how the modeled production system changes when its economic contribution is hypothetically removed.

It provides a framework for analyzing structural dependence and potential vulnerability to supply-side disruptions.

### Network Analysis

The production system is represented as an interregional network connecting economic activities and Brazilian states.

Network analysis supports the identification and explanation of important direct and indirect dependency relationships.

## Limitations

- The underlying economic database has 2018 as its reference year.
- Results represent structural relationships captured by the database, not current supplier contracts or real-time production.
- Simulations are hypothetical scenarios, not forecasts.
- The model relies on simplifying economic assumptions and does not automatically account for inventory buffers, substitution between suppliers, price adjustments, or changes in production capacity.
- A modeled reduction in production should not be interpreted as an exact estimate of the real-world consequences of a specific disaster.

## Technology Stack

- Python
- NumPy
- pandas
- SciPy
- FastAPI
- MapLibre GL JS
- D3.js or Sigma.js
- pytest
- pandera

## Running Locally

Installation and execution instructions will be provided for the final working version.

## Project Status

MALHA is being developed as a prototype for the Hack Brasil hackathon.

Only implemented and tested functionality is included in the submitted demonstration.

## License



## Acknowledgments

Data source: IPEA and Receita Federal.

MALHA is an independent project and is not affiliated with or endorsed by these institutions.
