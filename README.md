# VTX Silva — Preview

VTX Silva is a desktop Git client for macOS and Windows: a commit graph, staging by file, hunk or line, branches,
merges and rebases, conflicts side by side, stashes, file history and blame. **Every action can be undone** — a
discarded change too — and the Git console lists every command Silva runs. Silva runs your own git, so hooks, LFS,
commit signing, credential helpers and your SSH setup behave as they do in your terminal. Everything stays on your
computer: no account, no cloud.

**This repository holds the release files only.** Get VTX Silva from
[**Releases → the latest one**](https://github.com/tanawat011/vtx-silva-release/releases/latest):

| Your computer | The file to download |
| --- | --- |
| Mac (Apple silicon or Intel) | `VTX-Silva_<version>_free_macos-universal_portable.zip` — unzip it and move VTX Silva to Applications |
| Windows 10 / 11 (x64) | `VTX-Silva_<version>_free_windows-x64_portable.zip` — unzip and run `VTX Silva.exe`, nothing to install |

`SHA256SUMS.txt` beside them lists each file's checksum.

You need git 2.38 or newer: on a Mac `brew install git` or `xcode-select --install`, on Windows Git for Windows
(git-scm.com).

## The first time you open it

VTX Silva is not signed yet, so your computer asks once.

- **macOS 15 and later:** open it, click Done, then System Settings → Privacy & Security → Open Anyway (next to
  "VTX Silva").
- **macOS 14 and earlier:** right-click the app → Open → Open.
- **Windows:** before unzipping, right-click the zip → Properties → tick Unblock. If SmartScreen says "Windows
  protected your PC", choose More info → Run anyway.

## It is a preview

Silva changes your repositories only through your own git, and ⌘Z / Ctrl+Z takes back what it did — but try it on
a repository you have pushed or copied first.

**Found a problem?** [Open an issue](https://github.com/tanawat011/vtx-silva-release/issues/new) with the version
(About VTX Silva), your operating system, what you did and what happened. About → Check this computer… → Copy helps
with anything about git, ssh or passwords. Never include a password or a token.
