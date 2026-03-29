# scoop-skilldex

Scoop bucket for [Skilldex](https://github.com/Pandemonium-Research/Skilldex) — a package manager and registry for Claude skill packages.

## Prerequisites

- [Scoop](https://scoop.sh) installed
- [Node.js 20+](https://nodejs.org) installed (`scoop install nodejs-lts` if you don't have it)

## Install

```powershell
scoop bucket add skilldex https://github.com/Pandemonium-Research/scoop-skilldex
scoop install skilldex-cli
```

## Usage

```powershell
skillpm --help
spm --help        # identical alias
```

## Update

```powershell
scoop update skilldex-cli
```

## Uninstall

```powershell
scoop uninstall skilldex-cli
scoop bucket rm skilldex
```

## Links

- [Skilldex on npm](https://www.npmjs.com/package/skilldex-cli)
- [Source code](https://github.com/Pandemonium-Research/Skilldex)
- [Documentation](https://github.com/Pandemonium-Research/Skilldex/tree/main/docs)
- [Homebrew tap](https://github.com/Pandemonium-Research/homebrew-skilldex) (macOS/Linux)
