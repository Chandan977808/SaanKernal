# SUSFS kernel patches

Vendored from `susfs4ksu` branch `gki-android14-6.1` (SUSFS v2.3.0).
Only the kernel side is kept. `10_enable_susfs_for_ksu.patch` is not used: BakaSU has SUSFS inline hook support built in.

Applied by the "Integrate SUSFS" step in `.github/workflows/main.yml`.
To update: replace the files here with a newer release and re-check against the pinned BakaSU ref (`KSU_REF`).
