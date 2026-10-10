# Phishing Pot — Dataset Card

## Overview

**Phishing Pot** is a public research dataset containing real-world phishing email samples collected for defensive security research, threat intelligence, phishing analysis, detection engineering, education, and related non-commercial purposes.

Repository:

https://github.com/rf-peixoto/phishing_pot

Maintainer:

https://www.linkedin.com/in/rf-peixoto

---

## Dataset provenance

The samples in Phishing Pot are collected from real email addresses that I have maintained for many years. Some of these addresses are intentionally old and have been exposed through data leaks and other publicly or illicitly redistributed datasets over a long period of time.

Because these addresses have been circulating for years, they naturally receive phishing, spam, fraud, malware-delivery attempts, credential-harvesting messages, and other unsolicited email.

I also deliberately seed controlled email addresses into historical leaked-data collections before those collections are further redistributed by threat actors or passed through underground ecosystems. This provides a way to observe how exposed addresses are later targeted and helps capture real-world malicious email activity over time.

The purpose of this process is defensive research and dataset collection. The repository contains messages received by these controlled or long-observed addresses; it is not intended to provide access to third-party mailboxes or private communications.

---

## What the dataset contains

Depending on the sample, messages may include:

- Original `.eml` content
- SMTP and mail-routing headers
- Sender and recipient metadata
- SPF, DKIM, and DMARC-related information
- URLs and domains
- Phishing infrastructure indicators
- Social-engineering content
- Attachment metadata
- Campaign-related artifacts
- Timestamps and delivery-path information

Because these are real-world samples, completeness varies from message to message.

---

## Intended uses

Phishing Pot is intended for:

- Threat-intelligence research
- Phishing detection research
- Defensive security tooling
- SOC and DFIR training
- Academic research
- Detection engineering
- Email-authentication research
- IOC extraction and enrichment
- Malware and phishing campaign analysis
- Non-commercial machine-learning experiments
- Security education

Researchers should record the repository commit, release, or dataset version used in their work so experiments can be reproduced.

---

## License — Non-commercial use only

**This dataset is licensed under the Creative Commons Attribution-NonCommercial 4.0 International license (CC BY-NC 4.0).**

Commercial use is **not permitted** under this license.

This includes, without limitation, use of the dataset as training, evaluation, enrichment, ingestion, or source material for commercial products, commercial AI/ML systems, paid services, commercial datasets, or other revenue-generating activities unless separate permission is granted by the maintainer.

Attribution is required.

When using the dataset, please link to:

https://github.com/rf-peixoto/phishing_pot

and:

https://www.linkedin.com/in/rf-peixoto

License text:

https://creativecommons.org/licenses/by-nc/4.0/

**Important:** the repository's top-level `LICENSE` file should match this license. If the repository currently uses a different license, update it before relying on the non-commercial restriction for future distributions.

---

## Dataset limitations

This dataset is not a statistically representative sample of all phishing activity.

Collection is influenced by factors including:

- The age and exposure history of the monitored email addresses
- The data leaks and underground datasets in which those addresses appeared
- Geography and language
- Threat-actor targeting preferences
- Spam-filtering and email-provider behavior
- Time period
- Campaign repetition
- Infrastructure reuse

Researchers should therefore avoid treating the corpus as a complete representation of the global phishing ecosystem.

The dataset is continuously evolving unless a particular tagged release or commit is referenced.

---

## Privacy and handling

The dataset is intended for security research.

Researchers should avoid unnecessarily republishing personal information that may appear inside real-world messages, and should follow applicable laws, institutional policies, and ethical-research practices when processing or redistributing samples.

Where practical, sensitive information unrelated to the security value of the sample should be minimized or redacted.

---

## Reproducibility

Because the main repository may change over time, research should identify the exact version used.

Prefer citing one of the following:

- Git commit hash
- Tagged release
- Dataset release version
- Download date

Future versioned releases may provide stronger reproducibility guarantees.

---

## Attribution

If you use Phishing Pot, please credit the project by linking to both:

- https://github.com/rf-peixoto/phishing_pot
- https://www.linkedin.com/in/rf-peixoto

No additional citation format is required.

---

## Donations

If this dataset is useful to your research or defensive work, donations are welcome.

**Bitcoin:** `bc1qflkwmca89fzw9gfpg6dkf0es9ctnm2ktcq03dp`

---

## Contact

GitHub:

https://github.com/rf-peixoto/phishing_pot

LinkedIn:

https://www.linkedin.com/in/rf-peixoto
