---
name: release-notes
description: Writes release notes from the merged Pull Requests
---
## Purpose

Create clear and useful release notes for a new software version using the merged Pull Requests (PRs).

## Input

The skill receives:

1. **Version** — the release version (for example, `v1.0`).
2. **Merged Pull Requests** — the changes that were merged into `main`.

Use the information from the merged PRs to understand what changed.

## Steps

1. Understand the changes
Read every merged PR provided for the release.
Identify:
- New features.
- Bug fixes.
- Improvements.
- Other important changes.

Do not include changes that were not merged.

2. Identify the audience
Decide who the release notes are intended for.
Consider whether the changes are most relevant to:
- End users.
- Developers.
- Project maintainers.

Use language appropriate for the audience.

3. Choose the format
Decide which sections make the most sense for this release.

Possible sections include:
- Features
- Bug Fixes
- Improvements
- Technical Changes

You do not need to include every section. Only use sections that contain relevant changes.

4. Write the release notes
For each important change:
- Write a short, clear description.
- Explain what changed.
- Focus on the benefit or impact.
- Avoid unnecessary technical details for non-technical readers.
- Do not invent features or changes.
- Avoid repeating the same information.

Each change should be described in a concise line.

5. Organize the release
Structure the notes so readers can quickly understand what is new.
Include:
- Release version.
- Release title or summary.
- Relevant sections.
- Important changes under each section.

Use consistent formatting.

6. Check the release notes
Before producing the draft, verify:
- Every described change comes from a merged PR.
- No important change is incorrectly described.
- There are no duplicate entries.
- The language is clear.
- The sections are appropriate.
- No sensitive information is exposed.

## Output

Generate a Markdown release notes draft.

Example:

# Release v1.0

## Features
- Added new functionality to improve the user experience.

## Bug Fixes
- Fixed an issue with password validation.

## Improvements
- Improved email validation.

Only include sections that are relevant to the actual merged PRs.

## Constraints

- Never invent changes.
- Only use information from merged PRs.
- Decide the format based on the changes and intended audience.
- Keep descriptions concise and understandable.
- Do not publish the release automatically.
- Produce a draft that can be reviewed and edited manually.

