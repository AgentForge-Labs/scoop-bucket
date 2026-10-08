# AgentForge Labs Scoop bucket

This public bucket contains official Scoop manifests maintained by AgentForge Labs.

## Install SnapForge CLI

```powershell
scoop bucket add agentforge-labs https://github.com/AgentForge-Labs/scoop-bucket
scoop install agentforge-labs/snapforge
snapforge --version
```

The `snapforge` manifest installs the immutable Windows x64 CLI release and verifies its SHA256 digest.
