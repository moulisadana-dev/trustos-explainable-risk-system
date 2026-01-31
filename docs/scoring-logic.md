# Trust Scoring Logic – TrustOS

- Each user starts with a trust score of 100.
- Trust signals increase or decrease the score based on severity and weight.
- Scores are recalculated whenever new activity is ingested.
- Trust scores evolve over time and are stored as a timeline.

## Thresholds

- 70–100: Low Risk
- 40–69: Medium Risk (Review Required)
- Below 40: High Risk

## Key Principle

TrustOS does not automatically block users.
All high-risk cases require human analyst review.
