# Midwest Corn – Weather & USDA Crop Data (Sample)

This repository contains a small sample of cleaned, QA-validated agricultural data
combining weather and USDA crop statistics.

## What’s included
This sample covers:
- **State**: Iowa (IA)
- **Crop**: Corn
- **Years**: 2018–2022

Datasets:
1. **Daily weather**
   - Sources: NOAA, ACIS, NLDAS
   - Metrics: temperature, precipitation, soil moisture, evapotranspiration

2. **Weekly USDA crop progress**
   - % planted, emerged, harvested
   - condition (good + excellent)

3. **Annual crop fundamentals**
   - planted area
   - harvested area
   - yield
   - production

## QA
Before export, the data passes automated checks for:
- schema consistency
- uniqueness of business keys
- basic physical plausibility

This is an early sample. No guarantees on completeness or update frequency yet.

## Why this exists
I’m trying to understand whether this kind of cleaned, aligned agricultural data
is useful to anyone working with ag, weather, or commodity data.

**Question:**  
Would this be useful to you, and what would you need to make it usable?

