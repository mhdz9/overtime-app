## Overtime App

## Key requirement: Company needs documentation that salaried employees did or did not get overtime each week.

## Models

Post -> date:date rationale:text
User -> Devise
AdminUser -> STI

## Features:
- Approval workflow.
- SMS sending -> Link to approval or overtime input.
- Administrate admin dashboard.
- Email summary to managers for approval.
- Needs to be documented if employee did not log overtime.

## UI:
Bootstrap -> formatting