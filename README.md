# scoop-bucket

[Scoop](https://scoop.sh) bucket for [rom-weaver](https://github.com/brandonocasey/rom-weaver),
a local-first offline toolkit for ROMs and ROM hack patches.

## Install

```powershell
scoop bucket add brandonocasey https://github.com/brandonocasey/scoop-bucket
scoop install rom-weaver
```

## Contents

| Manifest | Upstream |
| --- | --- |
| `bucket/rom-weaver.json` | [brandonocasey/rom-weaver](https://github.com/brandonocasey/rom-weaver) |

Manifests here are generated, not hand-edited. Each stable rom-weaver release
runs `scripts/generate-scoop-manifest.mjs` in the upstream repository and pushes
the result here; prereleases are skipped so this bucket always points at a
stable version. Open issues against the upstream repository.

## License

Manifests are released under the same license as rom-weaver, AGPL-3.0-or-later.
