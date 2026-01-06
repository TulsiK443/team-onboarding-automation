# Team Onboarding & Verification Automation

## Problem
During large corporate sports events, onboarding participating teams was highly manual and error-prone.
Once teams confirmed participation, the operations team had to:
- Send invitation emails
- Follow up for HR approvals
- Collect player ID cards, HR letters, company logos
- Share and validate Excel sheets with player details
- Manually create folders per company and sport in Google Drive

This led to delays, missing data, repetitive follow-ups, and high operational overhead.

---

## Solution Overview
I designed a **semi-automated, automation-ready onboarding workflow** using Google Forms, standardized templates, and structured file handling.

The goal was to:
- Reduce back-and-forth communication
- Enforce data consistency
- Centralize all verification data
- Prepare the system for full automation (n8n-ready)

---

## Workflow
1. Teams receive a single onboarding link (Google Form)
2. Team Admin submits:
   - Team & sport selection
   - Player details via a standardized Excel template
   - Player ID cards
   - HR approval letter
   - Payment proof
3. All uploads land in a centralized Google Drive folder
4. Admin performs quick validation and sorting
5. Folder structure follows:

(See workflow diagram in this repo)

---

## Why This Matters
- Eliminated multiple email threads per team
- Reduced onboarding time per team significantly
- Standardized data for match-day verification
- Designed with future automation in mind (n8n / Drive API)

---

## Future Scope (Automation-Ready)
- n8n workflow to:
- Auto-create folders per submission
- Validate file naming conventions
- Flag missing or incorrect documents
- Send automated confirmation emails
- Auto-sync player data into a master operations dashboard

---

## Tools Used
- Google Forms
- Google Drive
- Excel (standardized templates)
- Process design & workflow thinking
- AI used to structure workflow and identify automation opportunities

---

## Outcome
This workflow transformed a chaotic, manual process into a scalable and structured onboarding system, reducing errors and improving coordination across multiple teams and stakeholders.
