# Web-to-Markdown Service - Project Tracker

## Sprint 0 - Project Kickoff (2 d)
- [ ] PRD sign-off (PM, Tech Lead)
- [ ] Set up GitHub repo `web2md` with `infra`, `service`, `web` dirs.

## Sprint 1 - API Skeleton (5 d)
- [ ] Set up Serverless framework scaffold (Alice)
- [ ] Implement basic handler with input validation (Bob)
- [ ] Unit tests (Jest) (Bob)

## Sprint 2 - HTML Fetch & Parse (5 d)
- [ ] Integrate `node-fetch`, timeout, retries.
- [ ] Add `@mozilla/readability` parse.
- [ ] Implement `turndown` conversion with config.

## Sprint 3 - Redis Cache & Rate Limit (4 d)
- [ ] Terraform Redis.
- [ ] Redis client pooled.
- [ ] API Gateway usage plan.

## Sprint 4 - JS Fallback (5 d)
- [ ] Package Playwright in Lambda layer via EFS.
- [ ] Write `isJsHeavy` heuristic.
- [ ] Add metrics around fallback usage.

## Sprint 5 - Frontend & Observability (5 d)
- [ ] Build SPA with Tailwind.
- [ ] S3 + CloudFront deploy.
- [ ] CloudWatch dashboard.

## Sprint 6 - QA, Hardening, Launch (5 d)
- [ ] Load test, bug fixes.
- [ ] Update README, runbooks.
- [ ] Marketing site update.