# vigilant-happiness
POC Data analysis challenge

Run the main matching script on the sample data:

python Matching_Script.py \
  --input presales_data_sample.csv \
  --output presales_match_results.csv

This will:

Normalize and fuzzy-match each supplier

Apply country/region bonuses

Export presales_entity_match_results.csv with one row per input_row_key

Generate detailed context (triggered automatically):

presales_duplicate_veridion_ids.csv  summarize duplicate mappings for audit

raw_sample_duplicate_veridion_ids.csv: flags any raw catalog conflicts (expected to be empty)


📊 Reports

POC Report.pdf: Detailed narrative on data exploration, methodology, challenges, key findings, and next steps.

Presales POC Presentation Plan.pdf: Professional slide deck with executive summary, visual charts (match status, score distribution, case studies), and business impact.

Both reports leverage the CSV outputs for charts and tables.




