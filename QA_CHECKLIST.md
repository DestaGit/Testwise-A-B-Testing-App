# PRD — TestWise

## Product Name

TestWise

## Objective

Build a simple client-side A/B testing application that converts experiment data into decision-ready outputs.

## Core Pipeline

Input → Validation → Calculation → Output → Save/Export

## In Scope

- Manual A/B inputs
- Conversion rate
- Uplift
- Z-score
- P-value
- Decision label
- Native chart
- Save history
- Export CSV/JSON

## Out of Scope

- Backend
- Authentication
- APIs
- External libraries
- Scenario simulation
- Power analysis
- Multi-variant testing
- Dashboards

## Inputs

- Experiment name
- Visitors A
- Conversions A
- Visitors B
- Conversions B

## Validation Rules

- Visitors must be greater than 0
- Conversions cannot be negative
- Conversions cannot exceed visitors

## Outputs

- Conversion A
- Conversion B
- Uplift
- Z-score
- P-value
- Winner
- Decision
- Recommendation
- Chart

## Decision Labels

- Adopt
- Continue
- Reject

## File Structure

index.html

## Definition of Done

The app is complete when users can enter A/B data, run the test, view a decision, save the result, and export it.
