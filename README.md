```markdown
# cardio-cpt-updates

**Tracking 2015 CPT code revisions for subcutaneous ICD programming and interrogation in cardiology billing workflows.**

---

## Table of Contents

- [Overview](#overview)  
- [Background](#background)  
- [Case Narrative](#case-narrative)  
- [Repository Structure](#repository-structure)  
- [Usage](#usage)  
- [Contributing](#contributing)  
- [References](#references)  

---

## Overview

This repository collects reference materials, sample audit scripts, and a real-world case narrative illustrating the impact of the American Medical Association’s 2015 CPT code revisions on subcutaneous implantable cardioverter-defibrillator (S-ICD) billing. It is intended for medical coders, practice administrators, and health‐IT developers who need to align their cardiology billing workflows with updated device‐management codes.

## Background

In late 2014, the AMA published new, more granular CPT descriptors for S-ICD programming and interrogation to better reflect advanced electrophysiology procedures (defibrillation threshold testing, sensing vector optimization, lead impedance measurements, etc.). Key replacements include:

- **93260**  
  Programming device evaluation (in person) with iterative adjustment of the implantable subcutaneous lead defibrillator system; analysis, review, and report by a physician or qualified health care professional. (Work RVU 0.85)

- **93261**  
  Interrogation device evaluation (in person) with analysis, review, and report; includes connection, recording and disconnection per patient encounter; implantable subcutaneous lead defibrillator. (Work RVU 0.74)

These changes were previewed by the American College of Cardiology in their “2015 Cardiology Coding Changes Preview” [1].

## Case Narrative

_In 2015, while cross-training to cover hospital intake authorizations—despite my primary role being limited to patient facesheet entry and scheduling—I discovered a cluster of denials for patients with subcutaneous implantable cardioverter-defibrillators (S-ICDs). My colleague, who lacked formal coding credentials, was still using a static 2014 cheat sheet of CPT codes supplied by our external billing company. When I processed a denied authorization describing iterative defibrillation threshold testing, sensing vector optimization, and lead impedance measurements, it became clear that the clinical services performed no longer matched the obsolete codes on file. The repeated rejections over seven months signaled a systemic mismatch between documented electrophysiology work and the practice’s CPT assignments._

_According to the 2015 cardiology coding changes previewed by the American College of Cardiology, the AMA replaced the older device-management codes with more granular, updated codes: 93260 and 93261 [1]. I confirmed these descriptors via AAPC resources and then spoke with the insurer’s nurse reviewer, providing left ventricular ejection fraction data and device telemetry findings to validate the correct codes._

_With that confirmation, I alerted our billing coordinator and led a retrospective audit of six months of S-ICD encounters. We corrected the CPT assignments, resubmitted the claims, and successfully recovered a significant portion of previously denied revenue. This episode underscores two imperatives: first, even experienced staff can perpetuate coding errors without ongoing education on annual CPT revisions; second, although AI–driven coding tools promise automated cross-referencing of code updates, they still require vigilant human oversight to interpret nuanced electrophysiology documentation._

## Repository Structure

  ├── docs/  
  │   └── 2015_cpt_changes_ACC_preview.pdf   # Downloaded ACC article  
  ├── examples/  
  │   └── claim_audit_template.xlsx         # Sample audit spreadsheet  
  ├── README.md  
  └── LICENSE

## Usage

1. Review the ACC preview (in `docs/`) to understand the 2015 code changes.  
2. Use the `examples/claim_audit_template.xlsx` to map old vs. new CPT codes in your own practice.  
3. Adapt the case narrative for training materials or peer-review submissions.  

## Contributing

Contributions are welcome! Please submit pull requests for:

- Additional code‐mapping examples  
- Scripts or macros to automate claim audits  
- Expanded case studies or workflows  

## References

[1] American College of Cardiology. “2015 Cardiology Coding Changes Preview.” November 21, 2014.  
    https://www.acc.org/latest-in-cardiology/articles/2014/11/21/15/13/2015-cardiology-coding-changes-preview  
```
