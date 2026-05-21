# Feature Plan — <Project> — <Feature>

## 1. Acceptance target

What must be true for Slava, client, or user to accept the feature?

Source:
- client message;
- screenshot/Figma;
- API contract;
- bug report;
- demo expectation;
- business requirement.

## 2. User-visible result

Screens/routes:

Expected behavior:

Empty/loading/error states:

## 3. Backward plan: acceptance -> UI -> API -> domain -> data

### Acceptance
Expected outcome:
Proof needed:

### UI
Screens:
Routes:
Fields:
Actions:
States:

### API
Endpoint:
Request:
Response:
Errors:
Auth/permissions:

### Domain/application logic
Commands:
Queries:
Services:
Validations:
Workflows:

### Data/database
Entities:
Fields:
Migrations:
Indexes:
Seed/test data:
Backward compatibility:

## 4. Forward validation: data -> domain -> API -> UI -> acceptance

Data supports domain: YES/NO
Gaps:

Domain supports API: YES/NO
Gaps:

API supports UI: YES/NO
Gaps:

UI satisfies acceptance: YES/NO
Gaps:

## 5. Implementation slices

Slice 1:
- goal:
- files:
- verification:
- risk:

Slice 2:
- goal:
- files:
- verification:
- risk:

## 6. Verification plan

- backend build:
- backend tests:
- frontend typecheck/build:
- runtime smoke:
- screenshots:
- manual review:
- security scan:

## 7. Risks

BLOCKER:

NON-BLOCKER:

DEFERRED:

## 8. Status

DRAFT / READY_FOR_IMPLEMENTATION / IN_PROGRESS / NEEDS_REWORK / READY_FOR_REVIEW / ACCEPTED / DEFERRED

## 9. Next gate

