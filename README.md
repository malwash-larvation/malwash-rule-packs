# Malwash EDR Core v1 rule pack

This repository is the owner-controlled publication source for the immutable
OCI artifact `ghcr.io/malwash-larvation/malwash-rule-packs`.

The checked-in bundle is deterministic. The workflow publishes the exact OCI
manifest by digest and signs that digest with Cosign keyless signing through
GitHub Actions OIDC. The verifier must consume the digest and signed receipt;
tags are only human-readable release selectors.

The current bundle is held at the internal rollout stage until the backend
verifier receipt is independently accepted.
