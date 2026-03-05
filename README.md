# data-migration-validator

Backend API that validates CSV/JSON imports using configurable rules and stores validation results for audit and debugging.

## Goals
- Validate files deterministically and produce actionable error reports
- Store validation runs and allow querying results
- Be safe by default (limits, file type checks, clear errors)

## Tech
Java + Spring Boot, PostgreSQL, Docker, GitHub Actions

## Status
Scaffolding

## Roadmap
See docs/roadmap.md
