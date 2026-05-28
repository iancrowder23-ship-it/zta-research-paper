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

## SOURCE 3 — Ward & Beyer (2014), BeyondCorp

**Cite key:** `beyondcorp2014`

**Full citation (APA):**
Ward, R., & Beyer, B. (2014). BeyondCorp: A new approach to enterprise security. *;login: The USENIX Magazine*, *39*(6), 6–11. https://www.usenix.org/publications/login/dec14/ward

**`.bib` entry:**
```bibtex
@article{beyondcorp2014,
  author  = {Ward, Rory and Beyer, Betsy},
  title   = {{BeyondCorp}: A New Approach to Enterprise Security},
  journal = {{;login:} The {USENIX} Magazine},
  year    = {2014},
  volume  = {39},
  number  = {6},
  pages   = {6--11},
  url     = {https://www.usenix.org/publications/login/dec14/ward}
}
```

**File in Sources:** `login_dec14_02_ward.pdf` / `login_dec14_02_ward.txt`

**Where to use:** Section III (historical development of ZTA), Section IV (real-world implementation precedent)

**Key content:**
- Google's internal zero trust deployment — started after the 2009 Operation Aurora attack
- Eliminated the concept of a privileged corporate network entirely
- All applications treated as internet-facing; access based on device state and user credentials, not network location
- "BeyondCorp shifts access controls from the network perimeter to individual devices and users" — landmark real-world proof of concept
- Shows ZTA is practical and scalable even for large enterprises

---

## SOURCE 4 — Biden (2021), Executive Order 14028

**Cite key:** `eo14028`

**Full citation (APA):**
Biden, J. R. (2021, May 12). Executive Order 14028: Improving the nation's cybersecurity. *Federal Register*, *86*(93), 26633–26647. https://www.federalregister.gov/documents/2021/05/17/2021-10460/improving-the-nations-cybersecurity

**`.bib` entry:**
```bibtex
@misc{eo14028,
  author       = {{Biden, Joseph R.}},
  title        = {Executive Order 14028: Improving the Nation's Cybersecurity},
  year         = {2021},
  month        = {May},
  note         = {Federal Register, Vol. 86, No. 93, pp. 26633--26647},
  url          = {https://www.federalregister.gov/documents/2021/05/17/2021-10460/improving-the-nations-cybersecurity}
}
```

**File in Sources:** `EO-14028.txt`

**Where to use:** Section V (real-world/government adoption), Section VI (benefits — national security mandate)

**Key content:**
- Mandates all federal agencies adopt Zero Trust Architecture
- Section 3 defines ZTA: "a security model, a set of system design principles, and a coordinated cybersecurity and system management strategy based on an acknowledgement that threats exist both inside and outside traditional network boundaries"
- "The Federal Government needs to make bold changes and significant investments in order to defend the vital institutions that underpin the American way of life"
- Required agencies to develop ZTA plans within 60 days of signing
- Mandated multi-factor authentication and encryption within 180 days
- Triggered OMB M-22-09 as the implementation roadmap

---

## SOURCE 5 — Young (2022), OMB Memorandum M-22-09

**Cite key:** `omb2022`

**Full citation (APA):**
Young, S. D. (2022, January 26). *Moving the U.S. Government toward zero trust cybersecurity principles* (OMB Memorandum M-22-09). Executive Office of the President, Office of Management and Budget. https://www.whitehouse.gov/wp-content/uploads/2022/01/M-22-09.pdf

**`.bib` entry:**
```bibtex
@techreport{omb2022,
  author      = {Young, Shalanda D.},
  title       = {Moving the {U.S.} Government Toward Zero Trust Cybersecurity Principles},
  institution = {Executive Office of the President, Office of Management and Budget},
  year        = {2022},
  month       = {January},
  number      = {M-22-09},
  url         = {https://www.whitehouse.gov/wp-content/uploads/2022/01/M-22-09.pdf}
}
```

**File in Sources:** `OMB-M-22-09.txt`

**Where to use:** Section V (government adoption), Section VI (benefits — policy validation)

**Key content:**
- Implementation memo for EO 14028 — sets specific deadlines (end of FY 2024)
- "In the current threat environment, the Federal Government can no longer depend on conventional perimeter-based defenses to protect critical systems and data"
- DoD ZTA Reference Architecture quoted: "no actor, system, network, or service operating outside or within the security perimeter is trusted. Instead, we must verify anything and everything attempting to establish access."
- Five ZTA pillars: Identity, Devices, Networks, Applications & Workloads, Data
- Requires phishing-resistant MFA for all federal staff
- Requires agencies to treat every application as internet-accessible
- Most concrete policy proof that ZTA is being adopted at the highest levels of government

---

## SOURCE 6 — Chandramouli & Butcher (2023), NIST SP 800-207A

**Cite key:** `chandramouli2023`

**Full citation (APA):**
Chandramouli, R., & Butcher, Z. (2023). *A zero-trust architecture model for access control in cloud-native applications in multi-location environments* (NIST Special Publication 800-207A). National Institute of Standards and Technology. https://doi.org/10.6028/NIST.SP.800-207A

**`.bib` entry:**
```bibtex
@techreport{chandramouli2023,
  author      = {Chandramouli, Ramaswamy and Butcher, Zack},
  title       = {A Zero-Trust Architecture Model for Access Control in Cloud-Native Applications in Multi-Location Environments},
  institution = {National Institute of Standards and Technology},
  year        = {2023},
  month       = {September},
  number      = {SP 800-207A},
  doi         = {10.6028/NIST.SP.800-207A},
  url         = {https://doi.org/10.6028/NIST.SP.800-207A}
}
```

**File in Sources:** `NIST.SP.800-207A.txt`

**Where to use:** Section IV (technical architecture — identity-tier policies), Section VI (benefits)

**Key content:**
- Companion to NIST SP 800-207; focuses on cloud-native/microservices environments
- Key driver assumptions: "Trust can no longer be based on a network perimeter as perimeters can always be breached. Policies have to be defined based on the assumption that the attacker is already inside of the corporate network."
- Introduces multi-tier policy framework: network-tier + identity-tier policies
- Identity-tier policies are environment-agnostic ("write once, enforce everywhere")
- Five identity-based segmentation requirements (ID-SEG-REC-1 through 5): encrypted connections, service authentication, service-to-service authorization, end-user authentication, end-user-to-resource authorization
- "Policy as code" (PaC) enables automated policy deployment across cloud environments

---

## SOURCE 7 — Borchert et al. (2025), NIST SP 1800-35

**Cite key:** `borchert2025`

**Full citation (APA):**
Borchert, O., Howell, G., Kerman, A., Rose, S., Souppaya, M., Scarfone, K., & Barker, W. (2025). *Implementing a zero trust architecture* (NIST Special Publication 1800-35). National Institute of Standards and Technology, National Cybersecurity Center of Excellence. https://doi.org/10.6028/NIST.SP.1800-35

**`.bib` entry:**
```bibtex
@techreport{borchert2025,
  author      = {Borchert, Oliver and Howell, Gema and Kerman, Alper and Rose, Scott and Souppaya, Murugiah and Scarfone, Karen and Barker, William},
  title       = {Implementing a Zero Trust Architecture},
  institution = {National Institute of Standards and Technology, National Cybersecurity Center of Excellence},
  year        = {2025},
  month       = {June},
  number      = {SP 1800-35},
  doi         = {10.6028/NIST.SP.1800-35},
  url         = {https://doi.org/10.6028/NIST.SP.1800-35}
}
```

**File in Sources:** `NIST.SP.1800-35.txt`

**Where to use:** Section IV (technical architecture — implementation), Section VII (counterarguments — complexity/challenges)

**Key content:**
- NCCoE collaboration with 24 industry partners; built 19 real ZTA implementations in lab environments
- "It is no longer feasible to simply protect data and resources at the perimeter of the enterprise environment or to assume that all users, devices, applications, and services within it can be trusted."
- "There is not a single ZTA that fits all" — ZTA must be tailored to each organization's requirements, risk tolerance, and existing technology
- Key implementation challenges identified: organizational buy-in, missing asset inventory, fragmented policy environments, technology integration complexity
- ZTA is "a journey" requiring continuous improvement — not a one-time deployment
- Demonstrates ZTA works across EIG, SDP, microsegmentation, and SASE architectural approaches
- Useful for counterargument section: acknowledges real implementation challenges while concluding ZTA is achievable

---

## SOURCE 8 — Campbell (2025), Preprints.org

**Cite key:** `campbell2025`

**Full citation (APA):**
Campbell, R. E. (2025, December 25). *Operationalizing the next-generation security triad: AI security, PQC, and zero trust in federal compliance* [Preprint]. Preprints.org. https://doi.org/10.20944/preprints202512.2298.v1

**`.bib` entry:**
```bibtex
@misc{campbell2025,
  author    = {Campbell, Robert E.},
  title     = {Operationalizing the Next-Generation Security Triad: {AI} Security, {PQC}, and Zero Trust in Federal Compliance},
  year      = {2025},
  month     = {December},
  note      = {Preprint. Not peer reviewed.},
  doi       = {10.20944/preprints202512.2298.v1},
  url       = {https://doi.org/10.20944/preprints202512.2298.v1}
}
```

**File in Sources:** `preprints202512.2298.v1.pdf` / `preprints202512.2298.v1.txt`

**⚠️ Note:** This is a preprint — not yet peer-reviewed. Use with a qualifier if citing (e.g., "a recent analysis argues..."). Useful for the Future/emerging trends section.

**Where to use:** Section VIII (the future — ZTA + AI + post-quantum cryptography)

**Key content:**
- Examines convergence of three emerging security paradigms: AI-driven security, post-quantum cryptography (PQC), and zero trust
- Argues ZTA is a foundational layer for federal compliance that must evolve alongside new threats
- Discusses how ZTA must adapt as quantum computing threatens current cryptographic assumptions
- Forward-looking: ZTA is not the endpoint but a platform for integrating future security capabilities
