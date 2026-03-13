================================================================================
LEAD QUALITY ANALYSIS: GROWTH DATA ANALYST CASE STUDY
================================================================================

PROJECT OVERVIEW
----------------
This project is a comprehensive analysis of marketing lead quality, evaluating
the alignment between two different scoring systems across major acquisition 
channels (Meta and Google Ads). The goal is to determine how well automated 
lead scoring correlates with actual lead performance.

THE BUSINESS QUESTIONS
----------------------
1. Coverage: What percentage of "Online Application" leads are scored by 
   both systems?
2. Alignment: How often do the two scoring systems agree on lead quality?
3. Channel Performance: Which channels produce the highest volume of 
   high-quality leads according to each system?

DATASET & METHODOLOGY
---------------------
The analysis uses the "Case Study - Growth Data Analyst" dataset, containing:
- Marketing Metadata: Channels, UTM parameters, registration methods.
- System 1 (L1-L4): Internal automated scoring hierarchy.
- System 2 (ABCDE): Qualitative scoring (A/B categorized as High Quality).
- Analysis Tool: Python (Pandas) within a Jupyter Notebook environment.

KEY FINDINGS & METRICS
----------------------
- Coverage (Online App): 27.55% of leads are scored by both systems.
- Qualitative Agreement: 73.33% of dually scored leads share the same outcome.

Channel Performance Comparison:
The analysis reveals how Google Ads and Meta (Facebook Ads) perform through 
different scoring lenses. While there is a 73% agreement rate, the absolute 
volume of high-quality leads varies between the systems, suggesting one 
methodology is more conservative than the other.

STRATEGIC RECOMMENDATIONS
-------------------------
* Investigation of Discrepancies: With a 26.67% disagreement rate, a deep 
  dive into "False Positives" is required to refine the scoring logic.
* Coverage Optimization: Since only ~28% of Online Applications are dually 
  scored, the optimization process may be biased. Expanding scoring coverage 
  is essential for accurate ROMI (Return on Marketing Investment) calculations.

HOW TO RUN THE ANALYSIS
-----------------------
1. Ensure Python 3.x and Pandas are installed.
2. Open the 'LinkGroup_LeadQuality_CaseStudy.ipynb' file.
3. Run all cells to reproduce the metrics and tables.
