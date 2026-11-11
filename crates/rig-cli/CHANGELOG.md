# Changelog

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## [Unreleased]
## [0.47.0](https://github.com/kjones/rig/compare/rig-cli-v0.46.0...rig-cli-v0.47.0) - 2026-11-11

### Added

- *(rig-cli)* shorten the warning for a 0.46 home's plugins.toml and defaults.json ([#3245](https://github.com/kjones/rig/pull/3245)) (by [gold-silver-copper](https://github.com/gold-silver-copper))
- *(rig-cli)* warn once per start of a 0.46 home's plugins.toml and defaults.json ([#3239](https://github.com/kjones/rig/pull/3239)) (by [gold-silver-copper](https://github.com/gold-silver-copper))
- *(rig-cli)* [**breaking**] rig update reinstalls rig and /update restarts the session on it ([#3224](https://github.com/kjones/rig/pull/3224)) (by [gold-silver-copper](https://github.com/gold-silver-copper))
- *(rig-cli)* rig plugin list groups rig's plugins and yours; each build writes a writing-rig-plugins skill ([#3218](https://github.com/kjones/rig/pull/3218)) (by [gold-silver-copper](https://github.com/gold-silver-copper))
- *(harness,cli,mcp-client)* [**breaking**] one settings file, plugins from the home list, full trust in projects, and the launcher in its own crate ([#3005](https://github.com/kjones/rig/pull/3005)) (by [gold-silver-copper](https://github.com/gold-silver-copper))

### Fixed

- *(rig-harness-protocol)* say the command line that runs a launcher word given after options ([#3259](https://github.com/kjones/rig/pull/3259)) (by [gold-silver-copper](https://github.com/gold-silver-copper))
- *(rig-cli)* write the writing-rig-plugins skill once, when rig sets up a new home ([#3247](https://github.com/kjones/rig/pull/3247)) (by [gold-silver-copper](https://github.com/gold-silver-copper))
- *(rig-cli)* pass the home and RIG_SOURCE on absolute to processes started elsewhere ([#3254](https://github.com/kjones/rig/pull/3254)) (by [gold-silver-copper](https://github.com/gold-silver-copper))
- *(rig-harness)* keep each launcher warning whole when it holds a line break ([#3258](https://github.com/kjones/rig/pull/3258)) (by [gold-silver-copper](https://github.com/gold-silver-copper))
- *(rig-cli)* `rig plugin check --build` refuses settings a start would refuse ([#3253](https://github.com/kjones/rig/pull/3253)) (by [gold-silver-copper](https://github.com/gold-silver-copper))
- *(rig-cli)* keep the session when the new launcher's agent refuses a /resume ([#3250](https://github.com/kjones/rig/pull/3250)) (by [gold-silver-copper](https://github.com/gold-silver-copper))
- *(rig-cli)* the version names its commit, the lock follows the checkout, and a source mismatch is refused ([#3221](https://github.com/kjones/rig/pull/3221)) (by [gold-silver-copper](https://github.com/gold-silver-copper))
- *(rig-cli)* plugin check says why a plugin's Cargo.toml can't be read ([#3214](https://github.com/kjones/rig/pull/3214)) (by [gold-silver-copper](https://github.com/gold-silver-copper))
- *(harness)* keep prompt history and run logs private to the user ([#3164](https://github.com/kjones/rig/pull/3164)) (by [gold-silver-copper](https://github.com/gold-silver-copper))
- *(harness)* never discard a session whose agent logs hold a conversation ([#3143](https://github.com/kjones/rig/pull/3143)) (by [gold-silver-copper](https://github.com/gold-silver-copper))
- *(rig-cli)* a Ctrl-C'd trial build is not rejected, and running the previous build instead of a rejected one is said ([#3139](https://github.com/kjones/rig/pull/3139)) (by [gold-silver-copper](https://github.com/gold-silver-copper))
- *(tui)* the wheel scrolls the transcript and a drag copies the text under it ([#3104](https://github.com/kjones/rig/pull/3104)) (by [gold-silver-copper](https://github.com/gold-silver-copper))
- *(rig-cli)* rig -p refuses a plugin that does not compile, and plugin disable takes out an unknown plugin ([#3094](https://github.com/kjones/rig/pull/3094)) (by [gold-silver-copper](https://github.com/gold-silver-copper))
- *(rig-cli)* an unknown plugin in settings refuses the start instead of running the previous build ([#3057](https://github.com/kjones/rig/pull/3057)) (by [gold-silver-copper](https://github.com/gold-silver-copper))

### Other

- *(rig)* an install line that works, a quick start, how to update, and what is per home ([#3217](https://github.com/kjones/rig/pull/3217)) (by [gold-silver-copper](https://github.com/gold-silver-copper))
- [**breaking**] remove duplicated tests, dead code and doc bloat across the workspace ([#3202](https://github.com/kjones/rig/pull/3202)) (by [gold-silver-copper](https://github.com/gold-silver-copper)) - #3202
- *(rig-cli)* help-agents says a settings.toml the launcher can't read exits 1 ([#3134](https://github.com/kjones/rig/pull/3134)) (by [gold-silver-copper](https://github.com/gold-silver-copper))

### Contributors

* [gold-silver-copper](https://github.com/gold-silver-copper)
