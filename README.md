# Codefast Day 09 · Datadog RUM Instrumentation

## Mission
- Instrument a Next.js app with Datadog RUM, user journey tagging, and session replay coverage.
- Standardize telemetry naming, sampling, and privacy controls.

## Implementation Checklist
1. Configure Datadog RUM SDK with service, version, and session sampling tuned per environment.
2. Add custom actions for key flows (pagination, uploads, localization) and attach user traits.
3. Mask PII fields, configure privacy rules, and document consent requirements.
4. Export dashboards summarizing Core Web Vitals, API errors, and user frustration signals.

## Telemetry & QA
- Validate instrumentation in lower environments before rolling to production.
- Add automated checks ensuring init script and environment variables are present in deploys.

## Deliverables
- README with instrumentation steps, dashboard links, and maintenance cadence.
- Runbook for triaging RUM alerts and correlating with backend traces.
