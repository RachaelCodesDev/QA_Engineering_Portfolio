# BUG-LOGIN-001 — Employee Portal Login Failure
**Training Scenario:** This defect report documents a simulated login failure created for QA Engineering practice. It does not represent a verified defect in a live application.

**Defect ID:** BUG-LOGIN-001

**Defect Title:** Login Rejected with Valid Employee Credentials — "Invalid Username or Password" Error Displayed

## Defect Description

The Employee Portal rejects valid employee login credentials and displays an "Invalid Username or Password" error message. This prevents affected employees from accessing the Employee Dashboard and performing their work-related tasks.

## Defect Environment (Simulated)

- Operating System: Windows 11
- Browser: Google Chrome
- Environment: QA Testing Environment
- Application: Airline Employee Portal v2.1

## Steps to Reproduce

1. Navigate to the Employee Login page.
2. Enter valid employee login credentials.
3. Click the Log In button.

## Expected Result

The employee is successfully authenticated and the Employee Dashboard page is displayed.

## Actual Result (Simulated)

The Employee Portal rejects the valid login credentials and displays an "Invalid Username or Password" error message. The Employee Dashboard is not displayed.

## Defect Classification

**Severity:** High

**Priority:** High

**Defect Status:** New (Simulated)

## Business Impact

Affected employees cannot access the Employee Dashboard, potentially delaying work-related tasks and disrupting normal business operations.

## Test Evidence

Not available — This defect report documents a hypothetical QA training scenario. No live application testing was performed, and no screenshots or execution logs were captured.

## Requirement Traceability

**Requirement ID:** REQ-LOGIN-001

**Related Test Case:** [TC-LOGIN-001](../Test_Cases/TC-LOGIN-001.md)

## Notes

This defect report was created for QA training and portfolio demonstration purposes. The Airline Employee Portal is a hypothetical application. The reported defect is simulated and has not been observed during live application testing.
