# Agent Working Agreement

## Company OS precedence

Before acting, retrieve and read the Company OS rules at the immutable bootstrap
revision through authenticated GitHub access:

`https://github.com/Vesconte-project/company-os/blob/d3f34bb4c885b409659f8a6bf261ed9234aee41e/AGENTS.md`

This is a remote repository reference, not a path inside this checkout. Use the
GitHub API or an authenticated GitHub tool to read that exact file and revision. If it
cannot be retrieved, stop and report the access blocker. Company-level operating rules
there govern this repository. If this repository conflicts with Company OS, stop and
report the conflict rather than guessing or silently choosing the local rule.

Truth boundaries:

- Notion = Narrative / specs / rationale.
- Airtable V1 = governance, Snapshots, and authoritative AcceptanceEvents.
- Linear = work coordination only.
- GitHub = implementation, code, PRs, CI, and immutable technical evidence.

GitHub state, a merge, CI, deployment, or Linear status never creates or proves
Acceptance.

## Governed work admission

Before implementation discovered through Linear, resolve the exact canonical
continuation-root UUID and open the canonical `work-preflight-request/v1` issue in
`Vesconte-project/company-os`. Retrieve the exact remote transport contract through authenticated GitHub access
from:

`https://github.com/Vesconte-project/company-os/blob/d3f34bb4c885b409659f8a6bf261ed9234aee41e/docs/work-preflight-transport.md`

Proceed only after verifying the exact request issue, the `github-actions[bot]`
response, the successful matching Company OS workflow run, and the semantically
identical `response.json` artifact from that run. The company, continuation, workflow
path, run ID, code SHA, status, eligibility, and `snapshot_ref` must agree across those
surfaces. On `ELIGIBLE_PROGRESS`, implement the exact immutable `snapshot_ref`, not the
mutable Notion page. Missing or inconsistent provenance, or any other status, means
stop.

Linear parent/child relations may help discover the continuation but never prove that
Acceptance covers this work. This repository contains no Company OS admission runtime
or Authority credential.
