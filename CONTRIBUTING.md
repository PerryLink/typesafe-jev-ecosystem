# Contributing to Jev Ecosystem

A curated directory of Jev integrations, compatible models, and System One tools. We organize links to projects hosted in their own repositories; nothing is mirrored here.

## Adding a Project

### Entry Format

Add your project to the matching category in `README.md`, keeping the category sorted by stars (highest first):

```markdown
- [**Name**](https://github.com/org/repo) ★ 1.2k - One sentence on the decision Jev makes in it
```

If the project existed before Jev and added it later, mark it as an integration:

```markdown
- [**Name**](https://github.com/org/repo) ★ 1.2k `integration` - One sentence on the decision Jev makes in it
```

### Where to Add

- Place it in the category that matches the project's primary use of Jev. One category per project.
- If no existing category fits, open an issue to propose a new one.

### Requirements

Every entry must meet all four:

- **Alive** — pushed to within the last 14 days at the time of submission
- **Used** — 50 or more GitHub stars
- **Real** — calls Jev, or a documented Jev-like model, for a concrete typed decision. A generic classifier, router or LLM judge that only resembles the pattern is not accepted.
- **Open** — public repository, not archived, not a fork

In addition:

- The description must say what decision Jev makes. One sentence, no marketing copy.
- Verify the link works and the repository actually calls the Jev API before submitting.
- Brand new projects that were just created are not accepted. Give your project time to mature and gain users before submitting.

### One Project per Pull Request

One project, one PR. Bulk drops of same-day repositories that share a scaffold are closed without review. Volume is not evidence of quality.

### PR Title

`Add project: name`

## Removing a Project

Removal is as valid a contribution as addition. Open a PR titled `Remove project: name` when a listed project is archived, deleted, no longer uses Jev, or has gone quiet for more than 30 days.

## Important

- This repository curates links only. Each project lives in its own repo.
- Listing is not endorsement. We check that a project is active and describes a real Jev use; we do not audit its code or verify its published numbers.
- We review all submissions and may decline projects that do not meet the bar.

## Help

- Check existing issues and PRs first
- Open a new issue for questions
- Visit the project's own repo for project-specific help
