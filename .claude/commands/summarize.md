# Summarize

Create an executive-quality summary of the current context.

## Objectives

* Minimize token usage.
* Preserve all critical information.
* Remove repetition.
* Focus on actionable knowledge.
* Produce a summary that another AI agent can continue working from immediately.

## Instructions

Analyze the current conversation, codebase context, files, decisions, plans, errors, and discoveries.

Extract only information that would matter if the entire conversation were deleted and a new session needed to continue the work.

### Include

#### Project Overview

* Current objective.
* Business purpose.
* Relevant domain assumptions.

#### Work Completed

* Features implemented.
* Files modified.
* Migrations created.
* Infrastructure changes.
* API changes.
* Database changes.

#### Current State

* What is working.
* What is partially complete.
* What is blocked.

#### Technical Decisions

Document decisions already made.

For each decision include:

* Decision.
* Reason.
* Impact.

#### Database

Include:

* Models added.
* Models modified.
* Migrations applied.
* Pending migrations.

#### API

Include:

* Endpoints added.
* Endpoints modified.
* Contracts changed.

#### Frontend

Include:

* Pages created.
* Components created.
* Components modified.

#### Bugs

Include:

* Open bugs.
* Root causes discovered.
* Fixes attempted.

#### Risks

Include:

* Technical risks.
* Product risks.
* Data integrity risks.
* Security concerns.

#### Next Actions

List the exact next tasks in execution order.

Use numbered steps.

#### Important Context

Capture any assumptions, constraints, business rules, stakeholder requirements, deployment requirements, environment variables, credentials placeholders, or architectural patterns required for future work.

### Exclude

* Greetings.
* Explanations.
* Thought process.
* Repeated information.
* Low-value discussion.
* Speculation.

## Output Format

# Project Summary

## Objective

...

## Current Status

...

## Technical Decisions

...

## Database

...

## API

...

## Frontend

...

## Bugs

...

## Risks

...

## Next Actions

1.
2.
3.

## Handoff Notes

...

### Compression Rule

Aim for maximum information density.

Use bullets instead of paragraphs whenever possible.

The summary should be usable as a direct handoff document for another Claude Code session.
