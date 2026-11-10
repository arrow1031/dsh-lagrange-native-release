# LcHost build artifacts

Thin host over **stock** [Lagrange.Core](https://www.nuget.org/packages/Lagrange.Core) (official NuGet, unmodified), linux-x64 self-contained single file.

Each release contains only:

- `LcHost-linux-x64-<version>.tar.gz` (contains exactly one file: `LcHost`)
- `LcHost-linux-x64-<version>.tar.gz.sha256`

No credentials, no tokens, no keystore, no signing material. Signing endpoint/token and QQ account are configured at runtime via environment (`LC_SIGN_BASE`/`LC_SIGN_TOKEN`/`LC_UIN`) and have **empty defaults**.
