# Core Data Model – TrustOS

## 1. User
Represents an individual or entity using the platform.

Attributes:
- User ID
- Basic profile information
- KYC status
- Account creation date

---

## 2. Activity
Represents actions performed by users.

Attributes:
- Activity ID
- User ID
- Activity type (login, transaction, update)
- Metadata (location, device, context)
- Timestamp

---

## 3. Trust Signal
Derived indicators based on user behavior.

Attributes:
- Signal ID
- User ID
- Signal type
- Signal value
- Signal weight
- Detection time

---

## 4. Trust Score
Represents the calculated trust level of a user over time.

Attributes:
- Score ID
- User ID
- Trust score (0–100)
- Calculation time
- Reason summary

---

## 5. Alert
Generated when trust scores cross risk thresholds.

Attributes:
- Alert ID
- User ID
- Risk level
- Explanation
- Alert status

---

## 6. Analyst Review
Human decision layer for alerts.

Attributes:
- Review ID
- Alert ID
- Analyst decision
- Review notes
- Feedback timestamp
