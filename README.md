# claude-setup

A Windows installer, `Claude Setup.exe`, that sets up the author's Claude (Claude Code) environment on a Windows PC. The repository exists to distribute that single binary; it contains no source code or build scripts.

The installer is about 193 MB and is stored with [Git LFS](https://git-lfs.com/), so a plain `git clone` without LFS only gives you a small pointer file, not the executable.

## Download

**Option A: GitHub release (recommended)**

Grab `Claude.Setup.exe` from the [v1.0 release](https://github.com/kos2001/claude-setup/releases/tag/v1.0). No Git or LFS tooling needed.

**Option B: Git LFS**

```bash
git lfs install
git clone https://github.com/kos2001/claude-setup.git
cd claude-setup
git lfs pull          # downloads the real 193 MB binary
```

## Install

1. Download `Claude Setup.exe` (see above).
2. Double-click it on Windows and follow the installer prompts.

## Repository layout

| File | Purpose |
|------|---------|
| `Claude Setup.exe` | The installer (Git LFS object, SHA-256 `1ffb0e08...831ed`) |
| `.gitattributes` | Routes `*.exe` through Git LFS |
| `LICENSE` | MIT |

## License

MIT, see [LICENSE](LICENSE).
