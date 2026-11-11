# Career Intelligence Platform

Responsive single-page career workspace for civil-engineering job discovery and application tracking.

## Deploy on Vercel
This is a static website in `index.html`.
- Framework preset: **Other**
- Root directory: `./`
- Build command: leave empty
- Output directory: leave empty
- Install command: leave empty

## Included
- Dashboard and vacancy summaries
- Vacancy records with official source and direct application URLs
- Pending/verified status for manual source review
- Company target directory
- Resume metadata record and editable skills profile
- Basic keyword matching
- Application pipeline
- Editable recruitment checklist
- Industry-news links
- Analytics and JSON/CSV export/import
- Browser localStorage persistence

## Current limitations
This is a functional frontend starter, not a production full-stack system:
- Data stays in this browser and is not synced to Supabase.
- Resume selection stores metadata only; file bytes are not uploaded or parsed.
- Verification is manual. The app does not independently validate vacancies or employers.
- No live job crawling, Gmail, LinkedIn, WhatsApp, AI matching, or monitoring is enabled.

## Production milestones
1. Configure Supabase Auth, PostgreSQL, Storage and row-level security.
2. Add secure server-side integrations and secrets through deployment environment variables.
3. Implement source-backed vacancy ingestion and verification history.
4. Add private resume upload/parsing and explainable matching.
5. Add authorised email/notification workflows with explicit approval.
6. Add tests, audit logging, monitoring and security review.

Never commit service-role keys, OAuth secrets, access tokens or passwords.
