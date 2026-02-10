# Onboarding Workflow (HR SaaS–Mapped)

This document defines the onboarding workflow using a SaaS product mindset.  
The workflow is designed to be **system-aware but tool-agnostic**, making it easily executable within common HRIS platforms while remaining clear for manual execution if required.

---

## Workflow Objective

To deliver a standardized, compliant, and predictable onboarding experience that:
- Reduces HR dependency on individual judgment
- Ensures mandatory compliance steps are not missed
- Aligns HR actions with system status changes
- Minimizes cognitive load for HR users

---

## Workflow Overview

**Trigger → Action → Outcome**

Offer Accepted → Employee Record Created → Documents Verified → Approvals Completed → Employee Activated

---

## Step 1: Onboarding Trigger

**Trigger Event**
- Offer acceptance received via ATS or email confirmation

**Owner**
- HR

**Outcome**
- Onboarding workflow formally initiated

---

## Step 2: Employee Record Creation

**HRIS Action**
- Create employee profile with status: `Draft / Pending`

**Owner**
- HR

**Inputs**
- Employee personal details
- Job role, department, reporting manager
- Start date

**Outputs**
- Employee record available for onboarding actions

**System Notes**
- No payroll or access enabled at this stage

---

## Step 3: Mandatory Document Collection

**HRIS Action**
- Assign document upload tasks to employee

**Owner**
- Employee (submission)
- HR (tracking)

**Required Documents**
- Government ID
- Employment contract
- Visa / work authorization (if applicable)
- Any role-specific documents

**Compliance Checkpoint**
- All mandatory documents uploaded before proceeding

---

## Step 4: Document Verification & Approval

**HRIS Action**
- Review and approve uploaded documents

**Owner**
- HR
- Manager (if applicable)

**Decision Point**
- If documents approved → proceed to next step
- If documents rejected → request re-upload

**Outcome**
- Verified employee documentation stored in system

---

## Step 5: Policy Acknowledgements

**HRIS Action**
- Assign policy acknowledgement tasks

**Owner**
- Employee (acknowledgement)
- HR (verification)

**Policies**
- Company policies
- Code of conduct
- Compliance-related policies

**Compliance Checkpoint**
- Acknowledgements recorded and timestamped

---

## Step 6: First-Day Enablement

**Actions**
- Orientation session conducted
- Internal introductions completed
- System access requests initiated (if applicable)

**Owner**
- HR
- Manager

**System Touchpoints**
- Task completion tracking
- Notes or comments logged

---

## Step 7: Status Activation

**HRIS Action**
- Update employee status from `Onboarding In Progress` → `Active`

**Owner**
- HR

**Outcome**
- Employee fully active in HRIS
- Payroll and lifecycle tracking enabled

---

## Success Criteria

- All mandatory documents verified
- Policy acknowledgements completed
- Employee status accurately reflects lifecycle stage
- Workflow completed without manual follow-ups

---

## SaaS Enablement Perspective

From a product enablement standpoint, this workflow:
- Reduces ambiguity through clear triggers and ownership
- Converts compliance requirements into executable system steps
- Enables HR teams to follow a predictable, repeatable process
- Mirrors how modern HR SaaS platforms guide users through onboarding

This workflow can be directly translated into:
- System-driven task lists
- Automated validations
- In-app guidance and checklists
