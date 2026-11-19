# renovate-config

Shared Renovate presets.

- `github>bturkis/renovate-config` — security fixes immediately (label `security`), one weekly grouped non-major PR (Monday before 06:00 Europe/Istanbul), majors as separate PRs, no automerge.
- `github>bturkis/renovate-config:automerge` — the above, plus automerge of the grouped non-major PR once every status check is green. Only for repos whose CI runs tests on pull requests.

Usage (`renovate.json` in a repo):

```json
{ "extends": ["github>bturkis/renovate-config"] }
```
