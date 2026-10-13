# BEACNLabs Tools

**Small, useful tools you can inspect, run, and make your own.**

This is the public directory of reusable open-source tools from [BEACNLabs](https://github.com/BEACNLabs). Each tool has its own source repository, installation guide, license, security notes, and validation scope.

## Available tools

| Tool | What it does | Useful for | Status |
|---|---|---|---|
| [**BEACN View**](https://github.com/BEACNLabs/beacn-view) | A screen capture host, browser viewer and optional read-only MCP bridge | Checking agent work, following renders/builds, phone check-ins, visual debugging | v0.1.0 · MIT · early release |

### BEACN View

Install a host on the computer you want to observe, then open its viewer in a browser. No viewer installation is needed for phones, tablets or computers. Agents can use an optional MCP client.

- Select a display or crop a region.
- Capture manually or refresh periodically; pause, zoom and save individual frames.
- Connect directly using trusted HTTPS or an SSH tunnel.
- Keep credentials in memory in the browser, with no cloud relay or analytics.
- Return screen images and capture metadata to MCP-capable agents.
- Try the interface with generated demo content before sharing a desktop.

It is an observation tool: no remote input, terminal execution, recording or shutdown. Native Windows/macOS capture acceptance remains pending; the project documents exactly what has been tested.

[**Open the project and setup guide →**](https://github.com/BEACNLabs/beacn-view#readme)

## How this directory grows

Tools are added after they have standalone setup instructions, an explicit open-source license, useful tests, and a review of the files being published. A private operational script is not automatically a public release. This directory contains public project descriptions only; it is not a dump of machine configurations, personal data or an internal inventory.

The machine-readable list is [tools.json](tools.json). To suggest an improvement, open an issue in the relevant tool's repository. See each project's security policy before reporting a vulnerability.

Directory content is [MIT licensed](LICENSE). Individual tools retain their own licenses.
