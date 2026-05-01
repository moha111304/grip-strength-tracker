# Data Schema: Recovery Metrics

This document defines the structure for tracking hand recovery and grip strength progress.

## Entry Object (JSON)
Each recovery entry will follow this structure:

```json
{
  "id": "uuid-string",
  "date": "2026-04-30T22:45:00Z",
  "metrics": {
    "grip_strength_kg": 45.5,
    "pain_level": 2,
    "dexterity_wpm": 85
  },
  "exercises": ["finger_curls", "stress_ball"],
  "notes": "Feeling strong, 3-month milestone reached."
}