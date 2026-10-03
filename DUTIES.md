# Duties and Responsibilities for Portfolio Conditional VaR Optimizer Agent

## Dual-Control Architecture
Maker:
convex-portfolio-solver

Checker:
risk-budget-checker

## Operational Workflow
1. The Maker (convex-portfolio-solver) analyzes incoming telemetry, context, and requirements.
2. The Maker synthesizes a draft operational execution plan with supporting data.
3. The Checker (risk-budget-checker) independently verifies all assumptions and constraints.
4. If validation passes, the plan is signed, logged, and committed.
5. All actions are appended to the immutable governance audit trail.
