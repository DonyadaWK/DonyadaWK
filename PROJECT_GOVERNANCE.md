# GitHub Project Governance

## Repository roles
- **DonyadaWK/DonyadaWK:** Public professional profile and selected case studies.
- **DonyadaWK/luitogether:** Public sports platform overview, requirements and roadmap.
- **DonyadaWK/dolchata-education:** Public EdTech overview, requirements and roadmap.
- **DOLCHATA:** Separate repository recommended; production source remains private unless explicitly approved.

## Standard workflow
1. Create an Issue: problem, user, expected outcome, priority and acceptance criteria.
2. Create a feature branch (`feature/short-description` or `fix/short-description`).
3. Make small commits and add tests or manual validation notes.
4. Open a Pull Request referencing the Issue.
5. Review security, accessibility, data privacy, impact and rollback.
6. Merge after checks; deploy using an explicitly configured environment.
7. Record release notes and verify production behavior.

## Issue priorities
- **P0:** Safety, privacy, security or service outage.
- **P1:** Broken critical user journey or incorrect core data.
- **P2:** Important improvement or noncritical bug.
- **P3:** Enhancement or future research.

## Definition of Done
- Acceptance criteria verified
- No secrets or personal data committed
- Relevant tests pass
- Documentation and user-facing copy updated
- Release/rollback plan considered for production changes

## Security rules
- Keep `.env`, API keys, service-role keys, customer data and private business records out of Git.
- Use secrets management for deployment and least-privilege access.
- Separate development, staging and production.
- Never assume public README features are live.
- Review licenses and third-party dependencies before distributing code.

## Suggested milestones
1. **Foundation:** Repository structure, docs, issues and environment inventory.
2. **Quality:** CI, linting, tests, dependency review and accessibility.
3. **Delivery:** Staging deploy, production verification and rollback.
4. **Growth:** Analytics, user feedback, support and product improvements.

## Source code inventory needed
For each website: hosting provider, source location, framework, build command, deployment trigger, environment variable names (not values), database/storage services and owners.
