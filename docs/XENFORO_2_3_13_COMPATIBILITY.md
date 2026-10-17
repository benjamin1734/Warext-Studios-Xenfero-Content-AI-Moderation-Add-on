# XenForo 2.3.13 compatibility checkpoint

- Minimum supported version (manifest): XenForo 2.3.7.
- Corrected the human-readable requirement label to match the numeric version gate.
- The add-on includes static/XML and regression checks in GitHub Actions.
- Runtime interoperability with a licensed XenForo 2.3.13 installation remains **unverified**; do not use CI success as evidence of a live installation pass.
- Check global `PAGE_CONTAINER` and `post_macros` modifications, post-save extension, edit workflows, and AI provider calls after upgrade.
