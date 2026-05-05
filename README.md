
# Financial Data Extraction Pipeline

Process 5000+ financial transactions with extraction, cleaning, validation, and GAAP categorization.

## Features
- Extract 5000+ transactions
- Clean & normalize data
- Validate with 95%+ accuracy
- Detect anomalies (volume spikes/drops)
- Apply GAAP accounting codes
- Generate quality reports

## Usage
```python
from extract import generate_sample_emails
from categorize import categorize_transactions

# Generate 5000 records
transactions = generate_sample_emails(5000)

# Extract & clean
extracted = extract_batch(transactions)

# Categorize with GAAP
categorized = categorize_transactions(extracted)

# Save
df.to_csv('categorized_5000.csv', index=False)
```

## Output
## GAAP Codes Applied
- 6310: Software - Cloud
- 6320: Software - SaaS
- 1520: Hardware - Equipment
- 6400: Travel - Airfare
- 6500: Meals & Entertainment
## Skills Demonstrated
✅ Regex extraction
✅ Data cleaning
✅ Quality validation
✅ Anomaly detection
✅ GAAP categorization
✅ Batch processing
✅ Reporting
✅ Scale (5000+ records)
