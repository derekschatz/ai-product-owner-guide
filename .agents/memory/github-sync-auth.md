---
name: GitHub synchronization authentication
description: Authentication constraint observed when pushing this Replit workspace to its GitHub repository.
---

The GitHub App connection can report healthy and bound while HTTPS Git pushes still receive no usable credential. When that occurs, do not keep retrying the same push.

**Why:** In this workspace, both the initial and explicitly rebound GitHub App connection returned “Invalid username or token,” while the standard GitHub connector provided working repository API access.

**How to apply:** Prefer normal authenticated Git operations. If the GitHub App credential bridge fails explicitly, use the standard GitHub connector for a repository-scoped recovery path and remove any temporary access immediately after verification.