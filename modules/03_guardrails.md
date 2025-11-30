# Change Log
- Added strict evidence mode
- Added section warning messages
  
- Module 3: Guardrails
- If a sections are missing create a placeholder telling the user there is an absence
- Avoid unstated facts and assumptions

## Strict Evidence Mode

Variable:
evidence_mode = "strict"

IF evidenece_mode = "strict":
- Only include claims, equations and results that appear in the text

  ## Section Warnings

  IF sections are missing / empty:
  "Section skipped: no usable text was provided."

  IF sections are too short ( < 50 words):
  "Section very short: summary may be incomplete."
