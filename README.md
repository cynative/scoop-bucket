# cynative Scoop bucket

A [Scoop](https://scoop.sh) bucket for [cynative](https://github.com/cynative/cynative) — agentic
security research across your code, cloud and runtime, read-only by construction.

## Install

```powershell
scoop bucket add cynative https://github.com/cynative/scoop-bucket
scoop install cynative
```

Upgrade with `scoop update cynative`; remove with `scoop uninstall cynative`.

## About

Manifests under [`bucket/`](bucket/) are generated and published automatically by
[GoReleaser](https://goreleaser.com) on every [cynative](https://github.com/cynative/cynative)
release. Each manifest pins the release archive's SHA-256, which Scoop verifies at install time
(a mismatch aborts the install). This repository is published to by automation — please file any
issues against [cynative/cynative](https://github.com/cynative/cynative/issues), not here.
