---
name: playwright-site-investigator
description: Analyze a public website using Playwright MCP to identify navigation structure, topic discovery paths, visible content areas, and search behavior. Use this for public website exploration and structured page analysis.
---

# Playwright Site Investigator

## Purpose
Use Playwright MCP to investigate a public website in a structured and repeatable way.

This skill is designed for:
- understanding homepage structure
- identifying navigation paths
- exploring topic-specific categories
- using on-page search where appropriate
- summarizing findings clearly

## Workflow
When this skill is used:

1. Open the target public webpage with Playwright MCP
2. Inspect the homepage or landing page before interacting
3. Identify major navigation areas, menus, search fields, and topic discovery elements
4. Look for content relevant to the requested topic
5. Use search only if it helps clarify discoverability
6. Summarize findings in a concise and structured way

## Rules
- Focus only on public, visible content
- Do not attempt login or private/account areas
- Do not dump large raw page content
- Do not scrape excessively
- Prefer concise summaries over verbose transcripts
- Explain what was found and where it was found in the UI

## Output format
Return:
1. a short summary of what the site offers related to the topic
2. where the relevant content was found
3. how a new user could discover it
4. any observations about clarity or discoverability