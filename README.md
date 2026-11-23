# Haymon AI plugins for Claude Code and Codex

Plugins by [Haymon AI](https://github.com/haymon-ai). Each plugin lives in its own repository; this repository only lists them.

## Add the marketplace

```text
# Claude Code
/plugin marketplace add haymon-ai/marketplace

# Codex
codex plugin marketplace add haymon-ai/marketplace
```

## Plugins

| Plugin | Description | Install | Source |
|---|---|---|---|
| `dbmcp` | The privacy first MCP server for SQL databases, with `explore`, `setup`, and `privacy` skills | `dbmcp@haymon-ai` | [`haymon-ai/dbmcp` › `plugins/dbmcp`](https://github.com/haymon-ai/dbmcp/tree/released/plugins/dbmcp) |

Install with `/plugin install dbmcp@haymon-ai` (Claude Code) or `codex plugin add dbmcp@haymon-ai` (Codex).

Each entry tracks its plugin repository's `released` branch, which moves only when a release is published, so you get released versions only.

## License

[MIT](LICENSE)
