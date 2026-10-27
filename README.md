# Healthcare Fabric V2 synthetic learning dataset (1000+ rows)

Main CSVs:
- patients.csv: 1,200 rows
- providers.csv: 80 rows (master data table; smaller by design)
- encounters.csv: 5,000 rows
- diagnosis_catalog.csv: 15 rows (lookup table; smaller by design)
- diagnoses.csv: 7,800 rows

Additional files:
- source/json/encounter_orders_nested.json: 1,200 nested order records
- incremental_batches/batch_001..batch_003: each has 100 new patients, 100 new encounters, and provider snapshots/changes
- reference/schema_and_relationships.json: schema and relationship definitions
- reference/DATA_QUALITY_ISSUES_AND_EXERCISES.md: seeded data-quality exercise guide

All data is synthetic. Provider PR030 changes department across batches for SCD Type 1/Type 2 exercises. Never publish real patient or confidential data.
