# Agent Working Agreement

## Company OS precedence

Before acting, retrieve and read the Company OS rules at the immutable bootstrap
revision through authenticated GitHub access:

`https://github.com/Vesconte-project/company-os/blob/b5344f026042c53a26f723018d3e5fbf73fea905/AGENTS.md`

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

`https://github.com/Vesconte-project/company-os/blob/b5344f026042c53a26f723018d3e5fbf73fea905/docs/work-preflight-transport.md`

Proceed only after verifying the exact request issue, the `github-actions[bot]`
response, identical comment `created_at` and `updated_at`, and the canonical response
digest in the exact successful Company OS run attempt's logs. Canonicalize the parsed
comment envelope exactly as the pinned transport contract specifies and require its
SHA-256 to match the unique run-log marker. The company, continuation, workflow path,
run ID, trusted `code_sha`, status, eligibility, and `snapshot_ref` must agree across
the comment, run, and run-bound digest. On `ELIGIBLE_PROGRESS`, implement the exact
immutable `snapshot_ref`, not the mutable Notion page. Missing or inconsistent
provenance, or any other status, means stop.

Linear parent/child relations may help discover the continuation but never prove that
Acceptance covers this work. This repository contains no Company OS admission runtime
or Authority credential.
