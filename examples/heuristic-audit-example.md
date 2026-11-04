# Example: heuristic audit of a form

> Didactic example. The scenario is hypothetical and does not represent research with real users.

## Context

A registration form asks for name, email, phone, tax ID, address and password on a single screen. Errors appear only after submission. The primary button uses the label "Continue".

## Findings

### 1. Errors shown only after submission

- **Observation:** The person must submit the form to discover invalid fields.
- **Concepts:** Error prevention; visibility of system status.
- **What:** The interface does not help avoid or correct errors at the appropriate moment.
- **Why:** Late errors increase rework and uncertainty.
- **Who:** Everyone, especially people with low digital familiarity or assistive technologies.
- **Where:** Fields and validation summary.
- **When:** Whenever validation can safely occur during entry.
- **How:** Validate at the appropriate moment, associate the message with the field, preserve values and announce errors accessibly.
- **Confidence:** Problem confirmed by inspection; impact needs validation.

### 2. Data collection without explanation

- **Observation:** Tax ID and phone are requested without explaining purpose.
- **Concepts:** Match with the real world, trust and autonomy.
- **Recommendation:** Explain why each piece of data is necessary, distinguish required and optional fields, and avoid collection without purpose.

### 3. Generic button label

- **Observation:** "Continue" does not explain the immediate result.
- **Recommendation:** Use a label that anticipates the action, such as "Create account", if that is indeed the next step.

## How to validate

- Test with representative participants.
- Measure completion, errors, time and help requests.
- Verify keyboard, screen reader, focus, messages and data preservation.
- Compare before and after results without assuming the change will cause improvement.
