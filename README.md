# EffortlessMetrics Scoop bucket

Scoop bucket for EffortlessMetrics tools.

## Install shiplog

```powershell
scoop bucket add effortlessmetrics https://github.com/EffortlessMetrics/scoop-bucket
scoop install effortlessmetrics/shiplog
```

The `shiplog` manifest tracks GitHub releases, verifies the published SHA-256
asset hash, and exposes the executable as `shiplog`. It currently supports
Windows x86_64, matching the published release asset.

Verify the installation:

```powershell
shiplog --version
```
