# HRIS Mapping – SaaS Translation View

This document translates the onboarding and offboarding workflows into HRIS-aligned system actions.  
It demonstrates how operational SOPs can be mapped to **HR SaaS product logic**, enabling consistent execution, automation, and reporting.

The mapping is **tool-agnostic** but aligned with common HRIS platforms (e.g., Zoho People, BambooHR, Netchex-style systems).

---

## Purpose of This Mapping

- Bridge the gap between HR operations and system usage
- Ensure workflows are executable inside an HRIS
- Reduce reliance on tribal HR knowledge
- Support product enablement, customer success, and training use cases

---

## Core HRIS Objects Used

| HRIS Object | Description |
|------------|-------------|
| Employee Record | Central employee profile |
| Employee Status | Lifecycle state indicator |
| Tasks / Checklists | Workflow execution units |
| Documents | Compliance and contract records |
| Approvals | Verification and clearance |
| Audit Logs | Traceability and compliance |

---

## Onboarding Workflow – HRIS Mapping

### 1. Offer Accepted → Onboarding Trigger

| Workflow Step | HRIS Representation |
|--------------|--------------------|
| Offer acceptance | External trigger (ATS / Email) |
| Workflow start | Manual or automated task initiation |

---

### 2. Employee Record Creation

| Workflow Step | HRIS Action |
|--------------|-------------|
| Initialize employee | Create employee record |
| Lifecycle state | Status = Draft / Pending |

**Enablement Note:**  
HR admins must understand that record creation ≠ employee activation.

---

### 3. Document Collection

| Workflow Step | HRIS Action |
|--------------|-------------|
| Request documents | Assign document upload tasks |
| Submission | Employee uploads documents |
| Storage | Documents stored against employee profile |

**Compliance Control:**  
Mandatory document completion gate before proceeding.

---

### 4. Verification & Approval

| Workflow Step | HRIS Action |
|--------------|-------------|
| Document review | HR approval task |
| Rework | Reject → re-upload loop |

**Product Logic:**  
Approval status controls workflow progression.

---

### 5. Policy Acknowledgements

| Workflow Step | HRIS Action |
|--------------|-------------|
| Assign policies | Acknowledgement tasks |
| Employee action | Digital acceptance |
| Record | Timestamped audit entry |

---

### 6. Status Activation

| Workflow Step | HRIS Action |
|--------------|-------------|
| Complete onboarding | Status = Active |
| Downstream effects | Payroll, reporting enabled |

---

## Offboarding Workflow – HRIS Mapping

### 1. Exit Initiation

| Workflow Step | HRIS Action |
|--------------|-------------|
| Resignation / termination | Exit request recorded |
| Exit type | Resignation / Termination |

---

### 2. Status Update

| Workflow Step | HRIS Action |
|--------------|-------------|
| Exit initiation | Status = Exit Initiated |
| Notifications | Automated stakeholder alerts |

---

### 3. Notice Period Tracking

| Workflow Step | HRIS Action |
|--------------|-------------|
| Notice dates | Start / end dates recorded |
| Monitoring | Task reminders & status visibility |

---

### 4. Clearance & Access Revocation

| Workflow Step | HRIS Action |
|--------------|-------------|
| Asset handover | Clearance checklist tasks |
| Access removal | IT task / status confirmation |
| Approvals | Multi-owner approvals recorded |

---

### 5. Final Settlement & Closure

| Workflow Step | HRIS Action |
|--------------|-------------|
| Settlement | Payroll calculation |
| Exit docs | Generated & stored |
| Record closure | Status = Exited / Archived |

---

## Enablement & Adoption Considerations

This mapping highlights key enablement risks commonly seen in HR SaaS adoption:

- Users confusing **status updates** with **process completion**
- Approvals handled outside the system
- Compliance steps skipped due to unclear ownership
- HRIS used as storage, not workflow engine

### Enablement Mitigation
- Clear status definitions
- Mandatory task gating
- In-system guidance and checklists
- Role-based training materials

---

## Product Enablement Perspective

From a SaaS product enablement lens, this mapping supports:

- Admin onboarding and training
- Customer success playbooks
- Sales enablement demos
- In-app guidance and walkthroughs
- Reduction in support tickets

---

## Key Takeaway

This project demonstrates the ability to:
- Translate real HR operations into SaaS system logic
- Identify enablement gaps between capability and usage
- Design workflows that are both compliant and user-friendly
- Think like a product team while working in a non-software environment
