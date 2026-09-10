# lima

[中文版本](./README.cn.md)

Linux virtual machines, with a focus on running containers

![lima](https://repo.x-cmd.io/lima.svg)

## Install

```sh
x install lima
```

## Source

- **Upstream**: <https://github.com/lima-vm/lima>
- **Homepage**: <https://lima-vm.io/>
- **License**: Apache-2.0

## Release

- **Latest**: `v2.3.0-beta.0` (2026-07-21)
- **Last commit**: 2026-09-10
- **Assets in release**: 15

## Release assets

| Asset | Size | Target |
|-------|-----:|--------|
| [lima-2.2.0-Darwin-arm64.tar.gz](https://github.com/lima-vm/lima/releases/download/v2.2.0/lima-2.2.0-Darwin-arm64.tar.gz) | 35.8 MiB | `native/darwin/arm64` |
| [lima-2.2.0-Darwin-x86_64.tar.gz](https://github.com/lima-vm/lima/releases/download/v2.2.0/lima-2.2.0-Darwin-x86_64.tar.gz) | 23.3 MiB | `native/darwin/x64` |
| [lima-2.2.0-go-mod-vendor.tar.gz](https://github.com/lima-vm/lima/releases/download/v2.2.0/lima-2.2.0-go-mod-vendor.tar.gz) | 8.3 MiB | `native/unknown` |
| [lima-2.2.0-Linux-aarch64.tar.gz](https://github.com/lima-vm/lima/releases/download/v2.2.0/lima-2.2.0-Linux-aarch64.tar.gz) | 20.6 MiB | `native/linux/arm64` |
| [lima-2.2.0-Linux-x86_64.tar.gz](https://github.com/lima-vm/lima/releases/download/v2.2.0/lima-2.2.0-Linux-x86_64.tar.gz) | 22.9 MiB | `native/linux/x64` |
| [lima-2.2.0-Windows-AMD64.zip](https://github.com/lima-vm/lima/releases/download/v2.2.0/lima-2.2.0-Windows-AMD64.zip) | 23.3 MiB | `native/win/x64` |
| [lima-2.2.0-Windows-ARM64.zip](https://github.com/lima-vm/lima/releases/download/v2.2.0/lima-2.2.0-Windows-ARM64.zip) | 20.9 MiB | `native/win/arm64` |
| [lima-additional-guestagents-2.2.0-Darwin-arm64.tar.gz](https://github.com/lima-vm/lima/releases/download/v2.2.0/lima-additional-guestagents-2.2.0-Darwin-arm64.tar.gz) | 36.8 MiB | `native/darwin/arm64` |
| [lima-additional-guestagents-2.2.0-Darwin-x86_64.tar.gz](https://github.com/lima-vm/lima/releases/download/v2.2.0/lima-additional-guestagents-2.2.0-Darwin-x86_64.tar.gz) | 36.0 MiB | `native/darwin/x64` |
| [lima-additional-guestagents-2.2.0-Linux-aarch64.tar.gz](https://github.com/lima-vm/lima/releases/download/v2.2.0/lima-additional-guestagents-2.2.0-Linux-aarch64.tar.gz) | 36.9 MiB | `native/linux/arm64` |
| [lima-additional-guestagents-2.2.0-Linux-x86_64.tar.gz](https://github.com/lima-vm/lima/releases/download/v2.2.0/lima-additional-guestagents-2.2.0-Linux-x86_64.tar.gz) | 36.1 MiB | `native/linux/x64` |
| [lima-additional-guestagents-2.2.0-Windows-AMD64.zip](https://github.com/lima-vm/lima/releases/download/v2.2.0/lima-additional-guestagents-2.2.0-Windows-AMD64.zip) | 36.1 MiB | `native/win/x64` |
| [lima-additional-guestagents-2.2.0-Windows-ARM64.zip](https://github.com/lima-vm/lima/releases/download/v2.2.0/lima-additional-guestagents-2.2.0-Windows-ARM64.zip) | 36.9 MiB | `native/win/arm64` |
| [SHA256SUMS](https://github.com/lima-vm/lima/releases/download/v2.2.0/SHA256SUMS) | 1.4 KiB | `other` |
| [SHA256SUMS.asc](https://github.com/lima-vm/lima/releases/download/v2.2.0/SHA256SUMS.asc) | 699 B | `other` |

## Popularity

- **Stars**: 21,858 · **Forks**: 953 · **Open issues**: 1,547 · **Contributors**: 216

## Totals (cumulative)

- **Releases**: 102 · **Merged PRs**: 2919 · **Open PRs**: 103 · **Closed issues**: 1114 · **Open issues**: 433 · **Commits**: 6594

## Recent activity

| Window | Since | Releases | Merged PRs | Open PRs | Closed issues | Open issues | Commits |
|---|---|---:|---:|---:|---:|---:|---:|
| 30d | 2026-08-11 | 1 | 44 | 15 | 6 | 13 | 47 |
| 90d | 2026-06-12 | 6 | 220 | 43 | 41 | 44 | 234 |
| 360d | 2025-09-15 | 26 | 809 | 87 | 241 | 133 | 912 |

## Code size

Total: **60,343** lines of code across **581** files in the top 5 languages.

| Language | Code | Comments | Blanks | Files |
|----------|-----:|---------:|-------:|------:|
| Go | 47,162 | 4,491 | 6,491 | 388 |
| Sh | 6,210 | 1,467 | 910 | 67 |
| Yaml | 2,200 | 1,159 | 418 | 112 |
| Json | 2,013 | 0 | 0 | 5 |
| Svg | 655 | 2 | 1 | 9 |

## OpenSSF Scorecard

Overall score: **8.9 / 10**

Lowest-scoring checks:

- **Packaging** (-1/10) — packaging workflow not detected
- **Vulnerabilities** (4/10) — 6 existing vulnerabilities detected
- **Branch-Protection** (-1/10) — internal error: error during branchesHandler.setup: internal error: some github tokens can't read classic branch protect…

## Improve this data

Install metadata for lima lives in the [x-cmd/install](https://github.com/x-cmd/install) index — a curated YAML package list that x-cmd consumes at install time. If `lima` is missing, out of date, or installs incorrectly, please open an issue or PR there:

- **Open an issue**: <https://github.com/x-cmd/install/issues/new>
- **Edit the package entry**: <https://github.com/x-cmd/install/edit/main/lima.yml> (or whichever path the index uses)

The data on this page (card / loc / scorecard / release) is auto-collected by [x-cmd-install-action](https://github.com/x-cmd-install/x-cmd-install-action) and is regenerated daily. Improvements to *install behaviour* (which version gets installed, platform-specific quirks, dependencies) belong upstream in the index.

_Snapshot: `data/card/260910.yml` · 2026-09-10T16:33:55Z._
