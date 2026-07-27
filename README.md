# scoop-bucket

[Scoop](https://scoop.sh) bucket for [rom-weaver](https://github.com/rom-weaver/rom-weaver),
a local-first offline toolkit for ROMs and ROM hack patches.

## Install

```powershell
scoop bucket add rom-weaver https://github.com/rom-weaver/scoop-bucket
scoop install rom-weaver
```

## Contents

| Manifest | Upstream |
| --- | --- |
| `bucket/rom-weaver.json` | [rom-weaver/rom-weaver](https://github.com/rom-weaver/rom-weaver) |

Manifests here are generated, not hand-edited. Each stable rom-weaver release
runs `scripts/generate-scoop-manifest.mjs` in the upstream repository and pushes
the result here; prereleases are skipped so this bucket always points at a
stable version. Open issues against the upstream repository.

## License

Manifests are released under the same license as rom-weaver, AGPL-3.0-or-later.
