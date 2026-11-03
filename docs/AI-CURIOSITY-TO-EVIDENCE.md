# From AI Curiosity to Working Projects

*A practical guide for learning with AI, using GitHub as a workbench, and turning experiments into evidence.*

## Why this guide exists

A conversation on the *AI Rabbit Holes* podcast explored a simple challenge: when tools change, curiosity gives people a way to learn what they can do. The speakers discussed solo operators and small businesses using AI to attempt work that once required a larger budget, the risks of refusing to learn because a tool feels unfamiliar, and GitHub as a useful first doorway into building with AI.

This guide turns those ideas into a grounded Palm92 practice. It does not promise that AI will replace expertise, guarantee a job, or make every project cheaper. It treats curiosity as the first step, followed by learning, testing, judgement and proof.

**Core principle:** AI can help us investigate, design, draft and build. People remain responsible for checking the result and deciding what happens next.

## The useful ideas from the conversation

1. **Start with a question.** Try asking an AI assistant whether it can help with a specific task. A clear, small question is more useful than waiting until you understand every technical term.
2. **Treat GitHub as a workbench.** A repository can hold a project's files, history, notes, issues and evidence in one place. You can learn by reading and improving a project before attempting a large build.
3. **Look for practical opportunities.** A solo operator can use AI to explore a website, workflow or prototype that might otherwise have needed a larger team or budget. Check quality, ongoing costs and suitability before relying on it.
4. **Adapt with judgement.** New tools can change work. Learning them can create options, while blindly accepting outputs can create new risks.
5. **Keep learning visible.** A clear README, meaningful commits, documented decisions and honest limitations make progress easier to understand and review.

## What GitHub does for a learner

- **Stores work:** files and documentation live together in a repository.
- **Tracks changes:** commits record what changed and when.
- **Creates safe experiments:** branches let you try changes separately before merging them.
- **Makes work reviewable:** issues, pull requests and project notes help organise questions and decisions.
- **Builds a portfolio:** public repositories can show how you think, test and improve a solution.

You do not need to become an expert programmer before using these features. Start by reading a README, exploring the files, and making one small, understandable change.

## Palm92 project map

These existing repositories are practical examples of turning curiosity into documented work. Open each README to check its current scope and status.

| Project | What it demonstrates |
| --- | --- |
| [Palm92 AI Test Copilot](https://github.com/faithfulord1/Palm92-ai-test-copilot) | AI-assisted testing, evidence capture, traceability and human review |
| [Palm92 Lead Recovery OS](https://github.com/faithfulord1/palm92-lead-recovery-os) | A governed workflow for recovering missed service-business leads |
| [SafeVoice Intelligence](https://github.com/faithfulord1/safevoice-intelligence) | Safety-oriented information support with evidence and escalation |
| [Vendor Due Diligence Agent](https://github.com/faithfulord1/Vendor-Due--Diligence-Agent) | Third-party risk analysis and documented due diligence |
| [PropertyPilot AI](https://github.com/faithfulord1/PropertyPilot-AI-) | Property analysis and decision support |
| [Palm92 GRC Evidence Vault](https://github.com/faithfulord1/palm92-grc-evidence-vault) | Control evidence, validation and assurance |

A repository is a record of work in progress. Read its README and code before assuming that a feature is complete or ready for real-world use.

## A repeatable build loop

Use this loop for a new idea or an existing repository:

1. **Name the problem.** Who has it, what do they need to do, and what would a useful result look like?
2. **Choose a small first outcome.** Prefer one useful page, form, report or workflow over a large platform.
3. **Inspect before changing.** Read the README, project structure, license, recent commits and open issues. Identify data, cost and security constraints.
4. **Ask AI to explain and plan.** Ask for a plain-language summary, proposed files, assumptions, risks and a short implementation plan.
5. **Build one change at a time.** Ask for the smallest useful change and review each affected file.
6. **Verify the result.** Try normal, missing and invalid inputs. Check calculations, links, accessibility, privacy and failure behaviour.
7. **Record what happened.** Update the README or project notes with the change, verification performed, known limits and next step.
8. **Keep a human decision point.** Do not let an agent publish, spend money, contact people, change live data or make a consequential decision without an authorised person reviewing that action.

### Prompt to understand a repository

> Explain this repository to me as a beginner. Start with what problem it solves, how to run or preview it, and which files matter most. Separate what you can confirm from what you are inferring. Do not change files yet. Identify security, privacy, cost, licensing or deployment concerns that I should understand.

### Prompt to make one safe improvement

> Help me make this small change: [describe the user problem and desired outcome]. First inspect the relevant files and propose the smallest change. State assumptions, files to change, risks and how I can verify it. Wait for my review before changing files. Do not add credentials, send data to external services, publish, deploy or modify live records.

### Prompt to review the result

> Review the change against the requested outcome. Give me: what changed, what you checked, what passed, what remains uncertain, and any security, privacy, accessibility or cost concerns. Do not claim a check passed unless you actually performed it.

## Reusable repository skeleton

For a new learning or prototype project, start with a small structure and add complexity only when the project needs it:

```text
project-name/
├── README.md                 # Purpose, status, setup, usage and limitations
├── LICENSE                   # Only after choosing an appropriate licence
├── .gitignore                # Excludes local files, secrets and generated output
├── docs/
│   ├── purpose-and-scope.md  # User, problem, boundaries and non-goals
│   ├── decisions.md          # Important choices and reasons
│   └── verification.md       # Checks performed and known limitations
├── src/                      # Application or workflow source
├── tests/                    # Checks for expected behaviour
└── .github/
    └── ISSUE_TEMPLATE/       # Optional structured requests and bug reports
```

Do not publish private information, access tokens, API keys, personal records or confidential training material. Use example data when demonstrating a workflow. A public repository can be copied, so review every file before sharing it.

## A seven-day starter path

This is a flexible sequence, not a deadline.

| Day | Small action | Evidence to leave in GitHub |
| --- | --- | --- |
| 1 | Open your profile README and one project repository | Note what each repository is for |
| 2 | Read a project's files and ask AI to explain them | Add a question or learning note |
| 3 | Choose one small improvement | Open an issue describing the user need |
| 4 | Make or request a small change in a branch | Review the file diff before merging |
| 5 | Try normal, missing and invalid inputs | Record what you checked and the result |
| 6 | Improve the README with setup, screenshots or limitations | Make the project easier for another person to understand |
| 7 | Reflect on what you learned and choose the next experiment | Add a concise progress note or close the issue |

## How we will measure progress

Progress is not measured by how many AI tools are connected or how impressive a demo looks. For each project, ask:

- Can another person understand the problem and intended user?
- Can I explain what the AI does and what it cannot verify?
- Is there a visible trail from request to change to review?
- Did I test more than the happy path?
- Are privacy, security, cost and licensing considered?
- Is a person clearly responsible for consequential decisions?
- Have you documented what is unfinished?

## Source note

The inspiration was a transcript supplied by Faith of an *AI Rabbit Holes* discussion featuring Ryan Doer and Aaron McCulkey, shared on 3 November 2026. This document paraphrases the themes and applies them to Faith's existing Palm92 GitHub work. It does not reproduce the full conversation or independently verify claims made by the speakers.

---

**Last updated:** 3 November 2026
