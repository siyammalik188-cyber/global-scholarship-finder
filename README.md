# Scholarship data contribution guide

This directory is intended to become the source of truth for scholarship listings. Accuracy matters more than quantity.

## Required verification workflow

1. Find the provider's official scholarship page. Do not use aggregators as the primary source.
2. Record the exact official application URL and the page where the requirements were checked.
3. Check degree level, eligible nationalities, study field, funding, deadline, and required documents.
4. Set `verificationStatus` to `needs-review` until a second contributor or maintainer confirms the record.
5. Add the reviewer's GitHub handle and an ISO date in `lastVerified`.
6. Mark expired opportunities as `expired`; do not silently change their deadline.
7. Submit a pull request explaining what changed and linking to the official source.

## Status values

- `needs-review`: collected but not independently confirmed
- `verified`: confirmed against the official source
- `expired`: deadline passed or programme closed
- `rejected`: source could not be confirmed or listing is unsafe

Never collect passports, transcripts, financial records, or other sensitive student documents in this repository.
