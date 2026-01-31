# Trust Signals – TrustOS

Trust signals are behavioral indicators derived from user activities.

## Initial Trust Signals

### 1. Activity Spike Signal
Detects sudden increases in activity compared to historical behavior.

Risk Impact: Medium  
Weight: 0.2

---

### 2. Location Change Signal
Triggered when actions occur from a new or unusual geographic location.

Risk Impact: Medium  
Weight: 0.2

---

### 3. Account Age vs Activity Signal
Flags new accounts performing high-risk or high-frequency actions.

Risk Impact: High  
Weight: 0.3

---

### 4. Repeated Failure Signal
Triggered by multiple failed attempts (login, transactions, verification).

Risk Impact: High  
Weight: 0.2

---

### 5. KYC Status Signal
Considers verification completeness and mismatches.

Risk Impact: High  
Weight: 0.3
