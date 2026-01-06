# Semi-Automated Team Onboarding & Verification Workflow

## Overview
This repository documents a semi-automated onboarding and verification system designed to streamline the intake of team data and documents for recurring corporate programs. The workflow prioritizes data integrity, predictable inputs, and scalability, while being intentionally designed to be automation-ready.

---

## Problem
Onboarding multiple teams required repeated email follow-ups, inconsistent spreadsheets, and manual folder creation. As scale increased, this led to:
- Inconsistent data formats and schema changes
- High manual effort in document handling
- Verification risks during execution
- Poor visibility into onboarding status

---

## Solution
I redesigned the workflow into a centralized system using structured data intake, standardized templates, and organized storage.

### Key components:
- **Single intake form** for all onboarding information
- **Mandatory file uploads** at submission time
- **Standardized player data template** with fixed schema
- **Centralized file collection** with enforced naming conventions
- **Repeatable folder structure** by event and sport

---

## Workflow Walkthrough
1. Teams submit onboarding details via a Google Form
2. Required documents are uploaded at submission
3. Player details are provided using a fixed template
4. All files automatically land in a central Drive folder
5. Admin routes files using naming conventions for fast verification

---

## Automation Logic (n8n-Ready Design)
The current version is semi-automated and designed for future automation.

Proposed n8n flow:
- Trigger: New form submission
- Parse company name and sport
- Create folder if not exists
- Route uploaded files automatically
- Update master onboarding status tracker

---

## Impact
- ~60–70% reduction in manual onboarding effort
- Elimination of data format inconsistencies
- Improved readiness and verification accuracy
- Scalable workflow reusable across programs

---

## AI Usage
AI tools were used to structure problem-solving, validate workflow design decisions, and improve clarity of documentation. All workflow design and execution decisions were independently driven.
