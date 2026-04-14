# Water Meter Prioritization Decision Support Tool

This project was developed as part of a public AI/ML competition in Catalonia, where it was awarded 3rd prize.

The goal was to support a municipal water company in deciding which water meters to replace first, based on data-driven prioritization.

## Overview

Water meters degrade over time, leading to inaccurate measurements and potential water loss. Replacing all meters simultaneously is not feasible, so the challenge is to identify where replacement has the highest impact.

This project combines machine learning and a visualization dashboard to rank devices according to their expected benefit if replaced.

## Approach

A predictive model was developed to estimate priority scores for individual meters based on features such as:
  - annual water consumption
  - type of usage (e.g. domestic, commercial, industrial)
  - historical patterns and device characteristics

These predictions were then used to generate a ranked list of meters, allowing decision-makers to allocate resources more effectively.

## Application

The dashboard provides:
  - a prioritized list of water meters
  - filtering and exploration of different segments
  - visual support for decision-making

The intention is not full automation, but decision support, where domain experts can combine model output with operational knowledge.

## Outcome
- Awarded 3rd prize in a regional AI/ML competition
- Demonstrated a practical application of ML in infrastructure optimization
- Highlighted potential environmental impact through improved detection of inefficient or faulty meters

## My Contribution
contributed to model development and feature selection
participated in design of the prioritization logic
worked on data preprocessing and evaluation
contributed to dashboard integration

## Tech Stack
Python · scikit-learn · data processing pipelines · dashboard framework

## Notes
This repository contains the application and supporting components.
A separate read.me.txt describes installation and usage.
