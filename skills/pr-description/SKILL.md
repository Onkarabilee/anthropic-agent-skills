---
name: pr-description
description: Use when writing or improving pull request descriptions, PR summaries, changelogs, testing notes, or reviewer-facing explanations for code changes.
---

# PR Description

When asked to write a PR description:

1. Read the relevant code changes or user-provided summary.
2. Produce a clear PR description with:
   - Summary
   - Changes
   - Testing
   - Risks or notes, if relevant
3. Keep the tone concise and reviewer-friendly.
4. Do not invent tests that were not run.

Use this format by default:

## Summary

Briefly explain what changed and why.

## Changes

- List the main implementation changes.

## Testing

- List tests run, or say "Not run" if none were provided.

## Notes

Mention risks, follow-ups, or reviewer context only if useful.