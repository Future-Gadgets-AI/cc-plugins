# cc-plugins

> Claude Code plugin marketplace by Future Gadgets AI.

This repository is a [Claude Code marketplace](https://docs.claude.com/en/docs/claude-code/plugins) — a thin index that points to the org's plugins. The plugins themselves live in their own repositories.

## Installation

In a Claude Code session:

```
/plugin marketplace add Future-Gadgets-AI/cc-plugins
/plugin install <plugin-name>@cc-plugins
```

The first command runs once per machine; subsequent installs from this marketplace skip it.

## Plugins

| Plugin | Description | Source |
|---|---|---|
| `agentic-dev` | Turn "fix this" / "ship that" into a well-formed issue, a verified change, and a review-ready PR through a gated issue/branch/PR flow. | [`Future-Gadgets-AI/agentic-dev`](https://github.com/Future-Gadgets-AI/agentic-dev) |

## Updating

```
/plugin update <plugin-name>@cc-plugins
```

## License

This index has no implied license. Each plugin retains its own license — see the linked plugin repositories.
