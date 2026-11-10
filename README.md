# pkgconf

pkgconf 2.3.0 (pkg-config): finds the compile flags of libraries from their .pc files, including the tOS library packages

A package for [tOS](https://github.com/Artfical/tOS), installed with `tpkg`:

```
sudo tpkg install pkgconf
```

| | |
|---|---|
| Version | 2.3.0 |
| Licence | ISC |
| Upstream | - |
| Needs | none |
| Needs tOS build | 619 or newer |
| Size | 142365 bytes (394144 unpacked) |
| SHA-256 of the `.tpkg` | `eb4972673d86e2bdd92ac863b4e990076e078f5bf7f5619529e0b6f178a5ad90` |

## Commands it adds

| Command | Runs |
|---|---|
| `bomtool` | `bin/bomtool` |
| `pkg-config` | `bin/pkg-config` |
| `pkgconf` | `bin/pkgconf` |

## Download

The package file (`pkgconf-2.3.0.tpkg`) and the sources it was built from are the assets of the
[v2.3.0 release](https://github.com/Artfical/tpkg-pkgconf/releases/tag/v2.3.0).
Git holds only the text: `meta.json`, the licences and `NOTICE.txt` (how it was built and what was changed).

Sources in the release:
- `pkgconf-2.3.0.tar.xz`

Check a download: `sha256sum pkgconf-2.3.0.tpkg` must give the hash above.

## Signatures

Packages are signed by Artfical's package server (Ed25519) and tOS checks the signature before it installs one.
The signature is made when the server hands a package out, so it is not kept here, and the signing key is never published.
`tpkg install` is the supported way to install; a `.tpkg` taken from here has the hash above but not the server's signature.

## Licence

The package is made of other people's software, under their licences: ISC. The licence texts are in this
repository (`LICENSE*`, `UNLICENSE`), and `NOTICE.txt` says how it was built. The sources above are the
corresponding source. `meta.json` and this README are free to copy.

Package problems (build, files, versions): open an issue here. Problems in the software itself belong upstream.
Security reports: see [SECURITY.md](https://github.com/Artfical/tOS/blob/main/SECURITY.md).
