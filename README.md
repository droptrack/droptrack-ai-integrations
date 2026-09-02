# DropTrack AI integrations

Official plugins and connection metadata for using [DropTrack](https://www.droptrack.com/) with AI assistants and developer tools.

Connect your DropTrack account to analyze tracks, understand audio and metadata insights in plain language, find relevant music-industry opportunities, and work with your promotion data from supported AI clients.

## What you can do

- Analyze an uploaded track, an existing DropTrack track, or a supported music link.
- Explain track analysis, tags, and recommendations in plain language.
- Find submission opportunities that fit a track.
- Review playlists, contacts, lists, campaigns, and audience engagement.
- Prepare campaign drafts and organize promotion assets.
- Review Grow advertising and promotion performance.
- Create customer-facing materials such as press releases, artist bios, and artwork.
- Work across an authorized label roster when your account has access.

Every action is scoped to the companies, data, and permissions available to the signed-in DropTrack account. Actions that create or change data remain subject to confirmation in the AI client.

## Start with track analysis

Try:

> Analyze my newest track and explain the results in plain language.

You can also ask:

- Find submission opportunities that fit my newest track.
- Compare engagement across my recent campaigns.
- Draft a promotion campaign for my latest release.

## Connect

### ChatGPT and Codex

Install the official [DropTrack plugin](https://chatgpt.com/plugins/plugin_asdk_app_6a717dd3f15c819195cf3288aec0207f), sign in to DropTrack when prompted, and start with one of the prompts above.

### Claude Code

Add the official DropTrack marketplace and install the plugin:

```text
/plugin marketplace add droptrack/droptrack-ai-integrations
/plugin install droptrack@droptrack
```

### Cursor

This repository is an [Agent Plugins 1.0](https://agent-plugins.org/) package. It can be installed from the public repository and is also prepared for the Cursor Marketplace.

### Gemini CLI

```sh
gemini extensions install https://github.com/droptrack/droptrack-ai-integrations
```

### Other MCP clients

Use the Streamable HTTP endpoint:

```text
https://mcp.droptrack.com/mcp
```

The server uses OAuth. Your client should open DropTrack sign-in automatically when it first connects.

## Documentation and support

- [Setup guide](https://droptrack.freshdesk.com/support/solutions/articles/9000276586)
- [Example workflows](https://droptrack.freshdesk.com/support/solutions/articles/9000276587)
- [DropTrack AI Assistant](https://www.droptrack.com/mcp-ai-assistant/)
- [Privacy Policy](https://www.droptrack.com/privacy-policy/)
- [Terms of Service](https://www.droptrack.com/terms-of-service/)
- [Support](https://droptrack.freshdesk.com/support/home)

## Repository layout

- `plugin.json` and `mcp.json`: portable Agent Plugins package
- `.codex-plugin/`: Codex plugin metadata
- `.claude-plugin/`: Claude Code plugin and marketplace metadata
- `gemini-extension.json`: Gemini CLI extension metadata
- `server.json`: official MCP Registry metadata
- `plugins/droptrack/`: self-contained marketplace package

## Security

Do not include tokens, passwords, customer exports, or production data in issues. See [SECURITY.md](SECURITY.md) for responsible reporting.

## License

The integration metadata in this repository is available under the [MIT License](LICENSE). DropTrack names, logos, and trademarks remain the property of DropTrack, Inc.
