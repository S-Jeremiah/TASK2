# Mars — Manual Test Cases (Education & Certification Module)

## Overview
A structured collection of manual test cases for the Education and
Certification modules of the Mars web application. This repository
documents the test design, coverage approach, and validation scenarios
used during functional and regression testing of these modules.

## About the Application
Mars is a web-based portal. This repository specifically covers the
**Education** and **Certification** profile management modules, which
allow users to add, edit, and delete their education history and
professional certifications from their profile.

## Test Coverage
| Module | Scenarios Covered |
|--------|------------------|
| Education | Add new education, edit existing education, |
|           | delete education, add duplicate education, |
|           | empty field validation, invalid date entry, |
|           | cancel action |
| Certification | Add new certification, edit existing certification, |
|               | delete certification, add duplicate certification, |
|               | empty field validation, invalid date/year entry, |
|               | cancel action |

## Test Case Structure
Each test case follows this format:

| Field | Description |
|-------|-------------|
| Test Case ID | Unique identifier (e.g. TC_EDU_001) |
| Test Title | Short description of what is being tested |
| Preconditions | Setup required before execution |
| Test Steps | Step-by-step actions to perform |
| Expected Result | What should happen if working correctly |
| Actual Result | What actually happened during execution |
| Status | Pass / Fail / Blocked |
| Priority | High / Medium / Low |

## Sample Test Scenarios

### Education Module
TC_EDU_001 — Add a new education record successfully

TC_EDU_002 — Add education with all empty fields

TC_EDU_003 — Add a duplicate education record

TC_EDU_004 — Edit an existing education record

TC_EDU_005 — Delete an existing education record

TC_EDU_006 — Add education with invalid date range

TC_EDU_007 — Cancel adding an education record

### Certification Module
TC_CERT_001 — Add a new certification successfully

TC_CERT_002 — Add certification with all empty fields

TC_CERT_003 — Add a duplicate certification

TC_CERT_004 — Edit an existing certification

TC_CERT_005 — Delete an existing certification

TC_CERT_006 — Add certification with invalid year

TC_CERT_007 — Cancel adding a certification

## Test Design Approach
- **Positive Testing** — verifying features work correctly
  with valid inputs (add, edit, delete successfully)
- **Negative Testing** — validating system behaviour with
  invalid or missing inputs (empty fields, duplicate entries,
  invalid dates)
- **Boundary Value Analysis** — testing character limits on
  input fields such as institution name, degree title,
  certification name, and year fields
- **Equivalence Partitioning** — grouping valid and invalid
  inputs to ensure efficient and thorough test coverage
- **Date Validation Testing** — specific focus on date and
  year field validation (past dates, future dates, invalid
  formats, graduation year before start year)
- **Exploratory Testing** — unscripted testing to discover
  defects outside documented scenarios

## Files in This Repository
| File | Description |
|------|-------------|
| Education_TestCases.xlsx / .md | Test cases for Education module |
| Certification_TestCases.xlsx / .md | Test cases for Certification module |



## Skills Demonstrated
- Manual test case design and documentation
- Functional and regression test coverage
- Positive and negative testing techniques
- Date and field validation testing
- Boundary value analysis and equivalence partitioning
- Requirements-to-test traceability
- Structured defect identification and reporting
