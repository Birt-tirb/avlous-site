# avlous-site repository instructions

## Purpose

Static Avlous site and Fasting Tracker support, privacy and notification pages.

## Architecture

Root HTML files are the published pages, `assets/` holds static assets and `CNAME` sets the custom domain.

## Critical rules

Keep user-facing privacy and support claims accurate and preserve the domain and existing page URLs.

## Development and PRs

Keep edits scoped to the affected page. Plan first for domain, public URL or data collection changes. List affected pages and browser checks in the PR.

## Verification

Run `git diff --check` and preview changed pages locally, checking links and assets at desktop and mobile widths.
