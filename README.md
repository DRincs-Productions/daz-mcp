# DAZ MCP Extensions & Skills

An independent collection of **Model Context Protocol (MCP) extensions and agent skills for DAZ Studio**, maintained by DRincs-Productions.

## Relationship to the upstream project

This project **extends and complements** [bluemoonfoundry/daz-mcp-server](https://github.com/bluemoonfoundry/daz-mcp-server). It is **not a fork or replacement** of that server. The upstream project provides the existing MCP integration with DAZ Studio; this repository will add higher-level tools, local automation and specialized agent workflows while keeping upstream code independent.

Integration details and compatibility will be verified during implementation. No additional MCP tools are implemented yet.

## Scope

The project is not limited to posing. Planned areas include:

- Character posing, pose analysis and refinement, including Genesis 9.
- Camera and viewport inspection and preview workflows.
- Scene operations and asset/library workflows.
- Batch operations and local automation designed to reduce agent tool calls and token usage.
- Reusable agent **skills** containing DAZ-specific instructions, procedures, constraints and verified examples.

These are planned capabilities, not claims of current functionality.

## Technology

- **Python** for the MCP server and local computation.
- **DAZ Script (JavaScript)** for DAZ Studio-side operations where needed.
- DAZ Studio **4.24** as the initial development target.

## Project integration

This repository is intended to be included as a **Git submodule** in [DRincs-Productions/daz-assert-ABFD-all-in-one](https://github.com/DRincs-Productions/daz-assert-ABFD-all-in-one), alongside its existing `mcp-server` submodule. Project-wide `AGENTS.md` instructions and the relevant procedures in `docs/` must be followed when integrating or operating within that workspace.

## Development status

**Planning / initial setup.** The repository currently contains documentation only. Implementation, skill format, MCP tool contracts, installation instructions and tests will be added incrementally after the architecture is agreed.

## Credits

The upstream DAZ MCP server is developed by [bluemoonfoundry](https://github.com/bluemoonfoundry/daz-mcp-server). This extension project is maintained independently by DRincs-Productions.
