# Changelog

## [v0.2.0](https://github.com/runapi-ai/infinitetalk-mcp/releases/tag/v0.2.0) - 2026-09-30

### Changed
- Send tool arguments to the service without local model, enum, range, required-field, or cross-field validation. Tool descriptions still list declared types and known values.
  Migration: Invalid arguments now return the service's error, including its message, instead of a local tool-input rejection.
- Document the 480p output_resolution default on audio_to_video.
- Depend on @runapi.ai/mcp-core 0.4.5 and send task creation and lookup to each tool's published route.


## [v0.1.7](https://github.com/runapi-ai/infinitetalk-mcp/releases/tag/v0.1.7) - 2026-07-31

### Changed
- Resolve MCP prices from the RunAPI Price Schedule API instead of embedded package data.


## [v0.1.6](https://github.com/runapi-ai/infinitetalk-mcp/releases/tag/v0.1.6) - 2026-07-08

### Fixed
- Publish corrected MCP runtime metadata for the login release.

## [v0.1.5](https://github.com/runapi-ai/infinitetalk-mcp/releases/tag/v0.1.5) - 2026-07-08

### Changed
- Publish MCP login onboarding, optional API key metadata, and the updated core dependency.

## [v0.1.4](https://github.com/runapi-ai/infinitetalk-mcp/releases/tag/v0.1.4) - 2026-06-24

### Changed
- Publish MCP server v0.1.4.
- Pin the package to @runapi.ai/mcp-core v0.1.3.
- Refresh package and MCP Registry metadata for this release.

## [v0.1.3](https://github.com/runapi-ai/infinitetalk-mcp/releases/tag/v0.1.3) - 2026-06-24

### Changed
- Refresh public README metadata for the focused Infinitetalk MCP package.

### Fixed
- Correct the GitHub repository badge URL so package README badges render cleanly on npm and GitHub.

## [v0.1.2](https://github.com/runapi-ai/infinitetalk-mcp/releases/tag/v0.1.2) - 2026-06-24

### Changed
- Refresh the public README with focused install paths, model links, and agent prompt examples.
- Update npm and GitHub metadata for developer discovery.
- Keep server.json and packaged contract/pricing data aligned with the release artifact.

## [v0.1.1](https://github.com/runapi-ai/infinitetalk-mcp/releases/tag/v0.1.1) - 2026-06-24

### Changed
- Distinct per-line README, npm keywords/description, and GitHub topics for InfiniteTalk so the package is discoverable on its own name and capabilities. No tool, schema, or behavior changes.

## [v0.1.0](https://github.com/runapi-ai/infinitetalk-mcp/releases/tag/v0.1.0) - 2026-06-24

### Added
- Initial release of the InfiniteTalk MCP server: create tasks, poll their status, and check pricing for every InfiniteTalk model with a single RunAPI API key.
