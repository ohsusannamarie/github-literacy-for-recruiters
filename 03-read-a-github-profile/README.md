# Read a GitHub Profile Like a Recruiter Who Understands GitHub

The goal is not to turn a GitHub profile into a secret resume.

The goal is to understand **what evidence is actually visible** and what that evidence can reasonably support.

## Start with context, not assumptions

Look at:

- bio
- location
- links
- organizations
- pinned repositories
- recent public activity
- repositories
- contribution history

Then slow down.

A GitHub profile is not a standardized professional profile. Two engineers with identical skill levels can have radically different public footprints.

## Pinned repositories

Pinned repositories are useful because the profile owner chose to surface them.

Ask:

- Did they create the repo?
- Is it a fork?
- What does the README say?
- When was it last meaningfully updated?
- Who else contributes?
- What problem does it solve?
- Is there evidence people use it?

## Repositories

Do not skim repository names and jump to conclusions.

Open the repository.

Read the README.

Look at ownership, history, contributors, issues, and pull requests when relevant.

The question is not merely:

> Which technologies appear?

The better question is:

> What evidence is there that this person actually did something meaningful with them?

## Contributions

Contribution history can help you investigate activity, but it is not a productivity score.

Public GitHub may omit much of someone's professional work. Private repositories, internal company systems, other version-control platforms, confidentiality, job function, and personal preference all affect what appears publicly.

## Organizations

Organizations can provide useful ecosystem context.

They can point you toward:

- open-source communities
- companies
- research groups
- foundations
- developer tooling ecosystems

But visible membership should not automatically be interpreted as employment.

## Stronger evidence usually has context

Compare these two observations:

**Weak:**

> Python appears on the profile.

**Stronger:**

> The person maintains a Python library focused on distributed tracing, has authored several merged changes in the last year, and participates in issue discussions about performance and instrumentation.

The second statement explains **what the evidence is**.

## Your sourcing notes should separate evidence from inference

Try this format:

| Evidence | Reasonable inference | Confidence |
| --- | --- | --- |
| Maintains repo for Kubernetes admission tooling | Likely hands-on familiarity with Kubernetes ecosystem | Medium-high |
| Starred several ML repos | May be interested in ML | Low |
| Forked Rust compiler repo | Has interacted with the project | Low |
| Multiple substantive merged PRs to compiler project | Evidence of direct contribution | High |

This simple habit dramatically improves GitHub research quality.