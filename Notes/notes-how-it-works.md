# Notes — Section IV: How ZTA Works — Technical Architecture (~1.5 pages / ~375 words)

**Job:** Explain the actual technical machinery. This is the most detailed section.
**Tone:** Technical but clear. Assume a reader who is smart but not a security professional.
**Sources:** NIST SP 800-207 (primary), CISA Maturity Model, BeyondCorp whitepapers

---

## My Raw Notes



---

## Checklist

### A. The NIST Logical Architecture
- [ ] Three core components from NIST SP 800-207:
      - **Policy Engine (PE):** makes the trust/access decision
      - **Policy Administrator (PA):** communicates the decision to enforcement points
      - **Policy Enforcement Point (PEP):** executes the allow/deny/limit decision
- [ ] Walk through a single access request flowing through all three
      (user requests a file → PE evaluates → PA sends decision → PEP enforces)

### B. Identity as the New Perimeter
- [ ] IAM replaces the network as the primary trust boundary
- [ ] MFA: why passwords alone fail; what second factors look like
- [ ] SSO / Identity Providers: Okta, Azure AD, Google Workspace — centralized identity

### C. Device Trust
- [ ] Posture assessment: OS patch level, encryption, EDR, enrollment status
- [ ] Non-compliant device = denied or sandboxed
- [ ] Device trust is continuous, not just checked at login

### D. Micro-Segmentation
- [ ] Flat network vs. segmented network — why flat is dangerous
- [ ] East-west (lateral) traffic is the primary attack path after initial entry
- [ ] Software-defined perimeters: each zone requires separate authorization

### E. Continuous Monitoring and Adaptive Policy
- [ ] Every action generates telemetry (logs, API calls, file access)
- [ ] Behavioral analytics / SIEM — anomalies flagged automatically
- [ ] Risk scores update in real time; access can be revoked mid-session
- [ ] Machine learning accelerates detection

### F. Data Protection
- [ ] mTLS: mutual authentication on every connection (not just the client proving identity)
- [ ] Encryption at rest + in transit
- [ ] DLP: even authorized users can't exfiltrate data

## Technical Terms to Define When You Use Them
- mTLS (mutual Transport Layer Security)
- SIEM (Security Information and Event Management)
- EDR (Endpoint Detection and Response)
- IAM (Identity and Access Management)
- PEP / PA / PE (NIST model components)
