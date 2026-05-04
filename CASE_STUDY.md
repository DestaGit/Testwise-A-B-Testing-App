# TestWise — A/B Testing App

TestWise is a simple client-side A/B testing application that helps users compare two variants and make a decision using conversion rate, uplift, z-score, p-value, and decision labels.

## Purpose

The app follows one clear pipeline:

**Input → Validate → Calculate → Output → Save/Export**

## Features

- Manual A/B test input
- Conversion rate calculation
- Uplift calculation
- Z-score and p-value
- Decision output: Adopt / Continue / Reject
- Native canvas chart
- Local browser history
- CSV and JSON export
- Fully client-side
- No backend
- No external libraries

## How to Use

1. Open `index.html` in a browser.
2. Enter visitors and conversions for Variant A and Variant B.
3. Click **Run Test**.
4. Review the result and decision.
5. Save or export the result.

## Sample Input

| Variant | Visitors | Conversions |
|---|---:|---:|
| A | 1000 | 80 |
| B | 1000 | 110 |

## Deployment

This app can be deployed directly to GitHub Pages.

## Tech Stack

- HTML
- CSS
- Vanilla JavaScript
- LocalStorage
- Native Canvas

## Constraints

- No backend
- No API
- No frameworks
- No external chart library
