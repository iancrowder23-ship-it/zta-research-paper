# Sources List

Add each source here as you find it. Use this to build your `.bib` file later.

---

## SOURCE 1 — NIST SP 800-207

**Cite key:** `nist2020`

**Full citation (APA):**
Rose, S., Borchert, O., Mitchell, S., & Connelly, S. (2020). *Zero trust architecture* (NIST Special Publication 800-207). National Institute of Standards and Technology. https://doi.org/10.6028/NIST.SP.800-207

**`.bib` entry:**
```bibtex
@techreport{nist2020,
  author      = {Rose, Scott and Borchert, Oliver and Mitchell, Stu and Connelly, Sean},
  title       = {Zero Trust Architecture},
  institution = {National Institute of Standards and Technology},
  year        = {2020},
  month       = {August},
  number      = {SP 800-207},
  doi         = {10.6028/NIST.SP.800-207},
  url         = {https://doi.org/10.6028/NIST.SP.800-207}
}
```

**Where to use:** Sections III, IV (primary technical source)

**Key content in your own words:**
- [YOUR NOTES HERE]

**Useful direct quotes / facts to paraphrase:**
- NIST defines ZT as: "a cybersecurity paradigm focused on resource protection and the premise that trust is never granted implicitly but must be continually evaluated" (p. 4)
- NIST's formal definition of ZTA: "an enterprise's cybersecurity plan that utilizes zero trust concepts and encompasses component relationships, workflow planning, and access policies" (p. 4)
- NIST identifies the core problem with perimeter-based security: "once attackers breach the perimeter, further lateral movement is unhindered" (p. 1)
- ZT is "not a single architecture but a set of guiding principles for workflow, system design and operations" (p. 1)
- The three core logical components: **Policy Engine (PE)** makes the access decision; **Policy Administrator (PA)** establishes/shuts down communication paths; **Policy Enforcement Point (PEP)** enables, monitors, and terminates connections (pp. 9–10)
- The 7 tenets of Zero Trust (pp. 6–7):
  1. All data sources and computing services are considered resources
  2. All communication is secured regardless of network location
  3. Access to individual resources is granted on a per-session basis
  4. Access is determined by dynamic policy including observable state of client identity, application, and device
  5. Enterprise monitors and measures integrity and security posture of all assets
  6. All resource authentication and authorization are dynamic and strictly enforced before access is allowed
  7. Enterprise collects as much information as possible about current state of assets and uses it to improve security posture
- On the perimeter model failure: "unauthorized lateral movement within the environment has been one of the biggest challenges for federal agencies" (p. 4)
- "Transitioning to ZTA is a journey... and cannot simply be accomplished with a wholesale replacement of technology" (p. 1)
- Historical note: Jericho Forum (2004) publicized "de-perimeterization"; Kindervag at Forrester later coined "zero trust" (p. 2)

---

## SOURCE 2 — Zaidi & Garai (2024), *Blockchain in Healthcare Today*

**Cite key:** `zaidi2024`

**Full citation (APA):**
Zaidi, T., & Garai, S. (2024). Emerging trends in cybersecurity: A holistic view on current threats, assessing solutions, and pioneering new frontiers. *Blockchain in Healthcare Today*, *7*, 302. https://doi.org/10.30953/bhty.v7.302

**`.bib` entry:**
```bibtex
@article{zaidi2024,
  author  = {Zaidi, Taskeen and Garai, Suman},
  title   = {Emerging Trends in Cybersecurity: A Holistic View on Current Threats, Assessing Solutions, and Pioneering New Frontiers},
  journal = {Blockchain in Healthcare Today},
  year    = {2024},
  volume  = {7},
  pages   = {302},
  doi     = {10.30953/bhty.v7.302}
}
```

**Where to use:** Section II (threat landscape evidence), Section VI/VII (ZTA as part of broader security ecosystem)

**Submitted/Published:** February 24, 2024; Accepted April 19, 2024; Published April 30, 2024

**Key content in your own words:**
- [YOUR NOTES HERE]

**Useful direct quotes / facts to paraphrase:**
- On the SolarWinds attack: "Russian hackers utilized vulnerabilities in SolarWinds' update process to infiltrate thousands of organizations' networks" (p. 2) — use in Section II
- On Colonial Pipeline: "a ransomware attack disrupted fuel supplies across the eastern United States, emphasizing the critical role that cybersecurity plays in protecting essential infrastructure" (p. 3) — use in Section II
- On ZTA vs. castle-and-moat: "Traditional security approaches, akin to a 'castle-and-moat,' are becoming obsolete in today's interconnected world. Zero trust architecture (ZTA) offers a paradigm shift through micro-segmentation, access control, continuous authentication, and authorization." (p. 4)
- On ZTA implementation: "Implementing least-privilege access prevents unauthorized lateral movement within the network. Dynamic trust verification ensures that trust is continuously verified throughout a session, adapting to the evolving risk landscape." (p. 4)
- On ZTA limitations: "ZTA complexity requires specialized expertise" (p. 6) — useful for counterarguments section
- On the broader threat landscape: "The severity and quantity of cybersecurity threats have significantly increased in recent years, leading to substantial financial losses and harm to the reputation of many businesses." (p. 2) — use as opening evidence in Section II
- Other breaches covered (potential additional evidence for Section II):
  - 2016 Mirai botnet / Dyn DDoS — $110 million in damages
  - 2015 OPM breach — 21 million individuals' data compromised
  - 2017 WannaCry — 300,000 computers globally
  - 2019 Capital One — $80 million fine
  - 2018 Marriott — 500 million guests, $123 million fine

---

## SOURCES STILL NEEDED

| Key | Source | Status |
|---|---|---|
| `kindervag2010` | Kindervag — No More Chewy Centers (Forrester 2010) | [ ] Find |
| `beyondcorp2014` | Ward & Beyer — BeyondCorp (USENIX 2014) | [ ] Find |
| `eo14028` | Executive Order 14028 (May 2021) | [ ] Find |
| `cisa2023` | CISA Zero Trust Maturity Model v2.0 (2023) | [ ] Find |
| `ibm2024` | IBM Cost of a Data Breach Report | [ ] Find |
| `source7` | One more peer-reviewed ZTA article | [ ] Find |
