# Data Quality Issues and Exercises

Synthetic learning data includes seeded examples:
- patients.csv: invalid date of birth, blank gender, duplicate patient_id.
- providers.csv: blank provider name and department_id D99 (department master is outside initial scope).
- encounters.csv: unmatched patient_id, unmatched provider_id, negative charge, invalid admission timestamp.
- diagnoses.csv: unmatched encounter_id, unknown diagnosis_code, duplicate diagnosis_record_id.

Exercises: validate required values, primary-key uniqueness, foreign-key relationships, date/timestamp parsing, non-negative charges, and record audit results by batch. Verify actual findings by running checks; this file is a guide, not a substitute for validation.
