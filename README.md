# PluginMesh

This repository is a retired scaffold. It does not contain a supported
PluginMesh implementation, package, or public API.

The maintained implementation lives in
[`szl-holdings/platform`](https://github.com/szl-holdings/platform):

- [PluginMesh orchestrator skill](https://github.com/szl-holdings/platform/tree/main/skills/pluginmesh-orchestrator)
- [plugin catalog](https://github.com/szl-holdings/platform/blob/main/data/plugins.json)
- [MCP server](https://github.com/szl-holdings/platform/blob/main/scripts/mcp-server.mjs)
- [catalog validator](https://github.com/szl-holdings/platform/blob/main/scripts/validate.mjs)

Run the canonical validation from the root of `szl-holdings/platform`:

```bash
node scripts/validate.mjs
```

The placeholder workflow was removed because this scaffold has no source or
test target. Keep this repository archived after the retirement change is
merged so users are directed to the maintained source.
