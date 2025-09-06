# Retail Prompt Project – Fresh Green Market

## Purpose
Design an AI prompt to analyze retail inventory and sales data, identify high-spoilage vegetable categories, compute financial losses, and propose actionable strategies to reduce waste.

---

## Prompt Template

You are an AI retail assistant. Using the provided inventory and sales data:

1. Calculate spoilage for each vegetable category: Spoilage = Total Stocked − Total Sold
2. Compute financial loss per category using average cost per item: Spoilage Loss ($) = Spoilage × Weighted Average Cost per Item
3. Rank categories by highest spoilage loss
4. Propose three actionable strategies for the top categories in 10 words or less
5. Estimate potential financial savings assuming a 30% reduction in spoilage

---

## Guidelines for AI Output
- Present results in a clear table format
- Include category names and numeric values
- Provide concise, actionable recommendations for each high-loss category

---

## References
1. Dataset: spoilagedata.csv (fabricated Q2 data aggregated at category level)
2. Source: FDA Program Information Manual on Retail Food Protection, Temperature Control of Cut Leafy Greens. This ensures recommendations are aligned with authentic government guidelines. Link: https://www.fda.gov/food/retail-food-industryregulatory-assistance-training/program-information-manual-retail-food-protection-recommendations-temperature-control-cut-leafy

---

## Notes
- Dataset is fabricated for portfolio purposes
- Demonstrates structured reasoning, RAG-style data organization, and actionable output generation
