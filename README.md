# txnlab/scoop-bucket

[Scoop](https://scoop.sh) bucket for the
[zerosignal](https://github.com/txnlab/zs-proxy) CLI tools (Windows) — drop-in,
private, OpenAI-compatible inference.

## Install

```powershell
scoop bucket add txnlab https://github.com/txnlab/scoop-bucket
scoop install zs-proxy
```

## Update

```powershell
scoop update zs-proxy
```

## Uninstall

```powershell
scoop uninstall zs-proxy
scoop bucket rm txnlab
```

---

Manifests in this bucket are generated automatically by
[goreleaser](https://goreleaser.com) on each tagged release — do not edit the
`*.json` files by hand.
