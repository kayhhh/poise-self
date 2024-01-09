[![Build](https://img.shields.io/github/actions/workflow/status/serenity-rs/poise/ci.yml?branch=current)](https://serenity-rs.github.io/poise/)
[![crates.io](https://img.shields.io/crates/v/poise.svg)](https://crates.io/crates/poise)
[![Docs](https://img.shields.io/badge/docs-online-informational)](https://docs.rs/poise/)
[![Docs (git)](https://img.shields.io/badge/docs%20%28git%29-online-informational)](https://serenity-rs.github.io/poise/)
[![License: MIT](https://img.shields.io/badge/license-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![Rust: 1.74+](https://img.shields.io/badge/rust-1.74+-93450a)](https://blog.rust-lang.org/2023/11/16/Rust-1.74.0.html)

# Currently not working. Use Serenity-self instead.

# Poise-self
Poise-self is an opinionated Discord bot framework with a few distinctive features:
- user account: user tokens are allowed making this a great choice for selfbots
- slash commands: completely define slash commands with a single function signature
- flexible argument parsing: command parameters are defined with normal Rust types and parsed automatically
- text commands: commands are agnostic over old text-based commands and slash commands
- edit tracking: when user edits their message, automatically update bot response

# Fork Changes

Changed to serenity-self 1.13.0-alpha to allow user tokens for the development of selfbots.

Credits
- [Poise](https://github.com/serenity-rs/poise) for the original Discord API wrapper
- [Serenity](https://github.com/serenity-rs/serenity) for the original Discord API wrapper
- [@Suffix](https://github.com/suffixarchive) for testing and helping with bug hunting

# How to use

Add the following to your `Cargo.toml` file:

```toml
[dependencies]
poise = { git = "https://github.com/gx-aura/poise-self", branch = "current" }
```

Most information is in the [API documentation](https://docs.rs/poise/). Also take a
look at the [examples](examples), especially [`feature_showcase`](https://github.com/ev3nvy/poise/tree/current/examples/feature_showcase), to learn what poise can do.

If you're using a development version from git directly, you probably want to look at the documentation for
[`current`](https://serenity-rs.github.io/poise/current), [`next`](https://serenity-rs.github.io/poise/next)
or [`serenity-next`](https://serenity-rs.github.io/poise/serenity-next) branch instead.

For further questions, don't hesitate to join the support server: https://discord.gg/serenity-rs.

# Bots using poise

For each bot, there's a list of notable features for you to take inspiration from.

- [Dexscreener Pricebot](https://github.com/keiveulbugs/Dexscreener_pricebot) by [@keiveulbugs](https://github.com/keiveulbugs): embeds, API calls, ephemeral messages
- [TTS Bot](https://github.com/Discord-TTS/Bot/) by [@GnomedDev](https://github.com/GnomedDev): localization, database, voice
- [Scripty](https://github.com/scripty-bot/scripty) by [@tazz4843](https://github.com/tazz4843): localization, database, voice
- [Etternabot](https://github.com/kangalio/Etternabot) by [@kangalio](https://github.com/kangalio): response transformation, variadic and lazy arguments
- [Rustbot](https://github.com/kangalio/rustbot) by [@kangalio](https://github.com/kangalio): database, custom prefixes

You're welcome to add your own selfbot [via a PR](https://github.com/serenity-rs/poise/compare)!

For more projects, see GitHub's [Used By page](https://github.com/serenity-rs/poise/network/dependents).
