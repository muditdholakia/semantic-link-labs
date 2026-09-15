# Curated learning fork

Source: https://github.com/microsoft/semantic-link-labs
Purpose: curated fabric learning reference for muditdholakia. This is a fork, not original authorship.
Upstream license: MIT. Preserve LICENSE, file-level notices, attribution, and any asset-specific terms.
Setup: follow the upstream README and the prerequisites of the selected sample. Use synthetic data and a development tenant.
Upstream snapshot: cab11db71ce002ee2bfece608ecf9a2519d61c2a

## Synchronization

```sh
git fetch --unshallow upstream  # once, if this clone is shallow
git fetch upstream
git switch main
git merge upstream/main
git push origin main
```

Review conflicts and dependency/runtime changes before executing upstream code.
Curator documentation is additive; upstream copyright and README are retained.
Security: see CURATOR_SECURITY.md. Fork Actions remain disabled until manually reviewed.
Troubleshooting: shallow merge errors require fetching full history; authentication errors require `gh auth status`.
