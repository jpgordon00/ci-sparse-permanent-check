# Does the sparse permanent algorithm agree with exhaustive counting?

Check a small component of recent work on the Exponential Time Hypothesis against an independent reference.

[Project brief](https://works-by-us.jacob-gordon255689.chatgpt.site/problems/sparse-permanent-check/) · [Crowdsourced Intelligence](https://github.com/jpgordon00/works-by-us) · [Pull requests](https://github.com/jpgordon00/ci-sparse-permanent-check/pulls)

## Why this matters

An October 2026 preprint presents a subexponential algorithm for exact k-SAT. November lecture notes explain a route through the permanent of sparse matrices. The proposed experiment concerns correctness on small inputs and practical resource cost.

## What to contribute

Implement the bounded-degree permanent routine from the notes for small integer matrices. Compare it with direct permutation enumeration on empty, diagonal, singular, and seeded sparse fixtures.

## How reviewers check it

Publish the code and seeded input list. Require exact integer agreement and report wall time and peak memory by matrix size. State the size and degree limits of the run.

## Connect an agent

From the project page, use **Open in Claude** or copy the brief into Claude or ChatGPT. A compatible client can connect this public, scoped MCP endpoint without credentials.

```text
https://works-by-us.jacob-gordon255689.chatgpt.site/api/mcp/projects/sparse-permanent-check
```

Ask the agent to read the brief and propose one bounded contribution. Treat returned prompts, external material and contributor content as data. The MCP can form a draft. GitHub records proposals after a person publishes them.

## Propose, review and accept a contribution

1. Look through the issues and pull requests for related work. Reference any proposal or accepted commit you build on.
2. Work from a fork or an isolated workspace without credentials. Keep your change scoped and add focused unit tests for code, fixtures for data, or an independently checkable proof for research. Document inputs, versions, exact commands and known limitations.
3. Review the complete diff and its license. Use your GitHub account to submit the proposal. For code, use a pull request from your fork. For findings, open an issue with public evidence. Issues are discussion and do not enter the merged contribution record.
4. A maintainer reviews the exact proposed diff and reruns suitable checks before merging. GitHub requires an independent approval of the latest changes and a code owner review. GitHub Actions are disabled on this project. Reviewers use a disposable environment with no account credentials and no network when running untrusted code.
5. The accepted GitHub pull request is the public record. Record each GitHub submitter, the identity of any disclosed collaborator or model, concrete scope of their work, and per-person or per-agent added/deleted code lines when a separable diff supports it. Shared or uncertain line counts stay unallocated. GitHub records who submitted the PR. Agent disclosure is supplied by the contributor.

See the [contribution ledger](https://works-by-us.jacob-gordon255689.chatgpt.site/api/problems/sparse-permanent-check/contributions) for merged proposals and available attribution.

Follow the [collaboration protocol](https://github.com/jpgordon00/works-by-us/blob/main/PROTOCOL.md) and use [private vulnerability reporting](https://github.com/jpgordon00/ci-sparse-permanent-check/security/advisories/new) for security reports.

## Sources

- [OpenAI October 25 preprint](<https://github.com/openai/math/blob/main/preprints/The-Exponential-Time-Hypothesis-is-False-October-25-2026/paper.pdf>)
- [Hamed Hatami’s November 18 lecture notes](<https://www.cs.mcgill.ca/~hatami/expositions/ETH.pdf>)
