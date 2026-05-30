# FDA Adverse Events - A Deep Dive into Supplements

## Overview
Analysis of adverse event reports from the FDA's Human Foods Complaint
System (HFCS) spanning 1999 to 2025, focused on dietary supplement safety.
The dataset was cleaned from 231,897 rows down to 113,081 rows across 17
columns after removing cosmetic products, concomitant product rows, and
duplicate rows.

**Type:** Capstone Project (Individual)   
**Tools:** Python, Power BI   

## Problem Statement
Between 1999 and 2025, the FDA recorded over 90,000 adverse event reports
linked to food and dietary supplements. Unlike pharmaceuticals, supplements
do not require FDA approval before reaching consumers, making post-market
reporting the only safety net.

## Objectives
- How have adverse event reports changed from 1999 to 2025?
- Which product categories generate the most reports?
- Does gender and age influence supplement reporting?
- What symptoms do supplement users most commonly report?
- Which supplements are linked to the most deaths?

## Key Findings
- Reports surged after the December 2007 mandatory reporting law, with a
  second peak in 2022 driven by the post-COVID supplement surge
- Supplements account for 51% of all adverse event reports, far exceeding
  any other food category
- Females and Seniors (65+) are the most affected demographic across all
  age groups
- The most commonly reported symptoms are choking, nausea, vomiting,
  diarrhea, dizziness, and headache
- Kratom is associated with the most reported deaths (178), followed by
  PreserVision (99 — likely reflecting its elderly user demographic rather
  than product toxicity) and 5-Hour Energy (28)

## Recommendations
- Screen patients for herbal supplement use, particularly those on
  prescription medications
- Prioritize supplement safety discussions with patients aged 65+
- Address choking risk with elderly patients — recommend smaller tablet
  formats or powder alternatives
- Use the HFCS as a clinical reference for emerging supplement safety signals

## Limitations
- Reports are self-reported and not confirmed proof that the product caused
  the adverse event
- Side effects may be linked to pre-existing health conditions
- Report quality varies. Some entries are incomplete or missing key details
- Nearly 40% of reports did not disclose patient age

## Data Source
FDA Human Foods Complaint System (HFCS)  
https://www.fda.gov/food/compliance-enforcement-food/human-foods-complaint-system-hfcs
