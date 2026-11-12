# Celsia - Quarantine Care Console (prototype)

Static site, no build step. Deploy on Vercel:
1. Unzip, then drag the `celsia` folder into https://vercel.com/new (or run `vercel` inside it).
2. Framework preset: **Other**. Leave build command and output directory empty.

Demo flow: Nurse records a temperature -> Doctor sees the patient in "Ready to see" and logs a visit -> Doctor confirms a discharge for a candidate -> Admin processes it, then admits a new patient into the freed bed.
