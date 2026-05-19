# NeuroKyosei QA Testing Project

## Overview

QA testing project focused on manual and automated validation of the NeuroKyosei website using Testim and Jira.

---

# Testing Types

- Smoke Testing
- Regression Testing
- Functional Testing
- UI Testing
- Exploratory Testing

---

# Tools Used

- Testim
- Jira
- GitHub
- Google Chrome

---

# Testim Smoke Testing

## SMOKE-001 - Homepage Smoke Test

Validated components:

- Homepage hero section
- Navigation bar
- Agenda navigation
- Homepage return navigation
- WhatsApp button visibility
- Footer visibility

Assertions used:

- Validate element visibility
- Validate expected text rendering

Result:
PASS

Execution time:
13 seconds

Evidence:
screenshots/testim/smoke-test-homepage-pass.png

---

# Testim Regression Testing

## REG-001 - Navigation and Contact Flow Regression Test

Validated components:

- Homepage navigation flow
- "Servicios clínicos" section visibility
- Agenda button interaction
- Contact form visibility
- "Nombre y apellido" field visibility

Assertions used:

- Validate element visibility
- Validate element text

Result:
PASS

Evidence:
screenshots/testim/regression-navigation-contact-pass.png

---

# Jira Workflow Evidence

The project includes:

- QA validation task creation
- Regression test documentation
- Automation execution evidence
- Task lifecycle management

Evidence:

- jira/jira-regression-validation-done.png

---

# Project Structure

```text
automation/
manual-testing/
bug-reports/
checklists/
test-cases/
reports/
screenshots/
jira/
