# Portfolio Case Study — TestWise

## Project Title

**TestWise: Client-Side A/B Testing Decision App**

## Problem

Many beginners, analysts, and product teams need a simple way to evaluate A/B test results without relying on complex analytics platforms or backend systems.

The problem is not just calculating conversion rates. The real need is to convert raw experiment data into a clear decision.

## Objective

Build a browser-based A/B testing app that allows users to:

- Enter Variant A and Variant B data
- Validate inputs
- Calculate experiment metrics
- Identify the better-performing variant
- Generate a simple decision recommendation
- Save and export results

## Target Users

- Data analysts
- Product managers
- Marketing analysts
- Healthcare analysts
- Students learning experimentation

## Product Scope

The app was intentionally kept focused on the core workflow:

**Input → Validation → Calculation → Output → Save/Export**

Excluded features:
- Scenario simulation
- Power analysis
- Multi-variant testing
- AI recommendations
- Multi-page dashboards

This reduced complexity and improved stability.

## Core Inputs

- Experiment name
- Visitors A
- Conversions A
- Visitors B
- Conversions B

## Core Outputs

- Conversion rate A
- Conversion rate B
- Uplift
- Z-score
- P-value
- Winner
- Decision label
- Native chart
- CSV/JSON export

## Decision Logic

| Result Condition | Decision |
|---|---|
| Statistically significant and meaningful uplift | Adopt |
| Positive but not strong enough | Continue |
| No clear improvement | Reject |

## Technical Approach

The app was built as a single self-contained `index.html` file using:

- HTML for structure
- CSS for responsive UI
- JavaScript for calculations and interactivity
- LocalStorage for saved history
- Native Canvas for charting

No external dependencies were used.

## Stability Controls

- Input validation before calculation
- No backend dependency
- No external library dependency
- Simple DOM structure
- Small calculation functions
- Local state only

## Result

TestWise provides a simple, reliable A/B testing workflow that can be used as a portfolio project or teaching tool.

## Portfolio Value

This project demonstrates:

- Data analysis logic
- Statistical reasoning
- Front-end development
- Product thinking
- Practical decision-support design
