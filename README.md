<p align="center">
	<a href="https://github.com/betterlite/PocketMine-MP">
		<picture>
			<source srcset="https://raw.githubusercontent.com/betterlite/PocketMine-MP/stable/.github/readme/pocketmine-dark-rgb.gif" media="(prefers-color-scheme: dark)">
			<img src="https://raw.githubusercontent.com/betterlite/PocketMine-MP/stable/.github/readme/pocketmine-rgb.gif" loading="eager" />
		</picture>
	</a><br>
	<b>BetterLite — A modern, community-driven fork of PocketMine-MP</b>
</p>

<p align="center">
	<a href="https://github.com/betterlite/PocketMine-MP/actions/workflows/main.yml"><img src="https://github.com/betterlite/PocketMine-MP/actions/workflows/main.yml/badge.svg" alt="CI" /></a>
	<a href="https://github.com/betterlite/PocketMine-MP/releases/latest"><img alt="GitHub release (latest SemVer)" src="https://img.shields.io/github/v/release/betterlite/PocketMine-MP?label=release&sort=semver"></a>
	<a href="https://discord.gg/vrPugybpJF"><img src="https://img.shields.io/discord/1526008653482692768?label=discord&color=7289DA&logo=discord" alt="Discord" /></a>
	<br>
	<a href="https://github.com/betterlite/PocketMine-MP/releases"><img alt="GitHub all releases" src="https://img.shields.io/github/downloads/betterlite/PocketMine-MP/total?label=downloads%40total"></a>
	<a href="https://github.com/betterlite/PocketMine-MP/releases/latest"><img alt="GitHub release (latest by SemVer)" src="https://img.shields.io/github/downloads/betterlite/PocketMine-MP/latest/total?sort=semver"></a>
</p>

---

## 🚀 What is BetterLite?

**BetterLite** is a fork of [PocketMine-MP](https://github.com/pmmp/PocketMine-MP), the popular open-source server software for **Minecraft: Bedrock Edition** written in PHP.

We took the solid foundation of PocketMine-MP and built on top of it with a clear mission:

> Fix bugs, keep the project alive, and bring it up to date with the latest Minecraft: Bedrock releases — while preparing the ground for a brand-new, Bukkit-compatible API.

If you love PocketMine but miss timely updates, hotfixes and a more familiar developer experience, you're in the right place.

---

## 🎯 Our Goals

- 🐛 **Bug fixes first** — we actively track, triage and fix issues found upstream and reported by our community.
- 📦 **Up-to-date with Minecraft** — we work to bring PocketMine-MP to the latest Minecraft: Bedrock versions as quickly and as stably as possible.
- 🛠️ **Stable daily driver** — every release is meant to be usable in production, not just a tech demo.
- 🌱 **Roadmap to BetterLite 1.0.0** — our next major milestone: a fully revamped, **Bukkit-Like 1:1 API**.

---

## 🔮 The Road to BetterLite 1.0.0

BetterLite 1.0.0 will be a **complete API redesign**.

We want to bring the PocketMine-MP developer experience closer to what Bukkit/Spigot developers already know and love — a clean, familiar, event-driven API that lets plugin authors feel right at home.

Highlights of what we're aiming for:

- 🧱 **Bukkit-Like 1:1 API surface** — commands, events, schedulers, listeners and configuration designed to mirror Bukkit conventions.
- 🔌 **Drop-in familiarity** — if you can write a Spigot/Bukkit plugin, you'll feel at home writing a BetterLite plugin.
- ⚡ **Modern PHP** — fully embracing PHP 8.2+ features for a safer, faster and cleaner codebase.
- 🧩 **Backward compatibility layer** — wherever possible, existing PocketMine plugins will keep working through adapters.

> ⚠️ **Heads up:** BetterLite 1.0.0 will introduce **breaking API changes**. Until then, the current PocketMine-compatible API is the priority.

---

## ⚠️ BetterLite is NOT a vanilla Minecraft server software.

It is **poorly suited to hosting vanilla survival servers** — it does not include vanilla world generation, redstone, mob AI and various other vanilla features.

If you just want to play **vanilla survival multiplayer**, please use the [official Minecraft: Bedrock server software](https://minecraft.net/download/server/bedrock) instead.

---

## 🧰 Features

- 🧩 **Powerful plugin API** — extend and customise gameplay the way you want.
- 🗺️ **Multi-world support** — offer varied experiences without transferring players between nodes.
- 🏎️ **Performance** — designed to handle 100+ players on a single node (depending on hardware and plugins).
- ⤴️ **Continuously updated** — new Minecraft versions supported as fast as we can ship them.
- 🧪 **Bukkit-Like API on the horizon** — see the roadmap above.

---

## 📚 Getting Started

- 📖 [PocketWiki Documentation](http://pmmp.readthedocs.org/) *(reference for the current PocketMine-MP-based API)*
- 🔌 [Poggit Plugin Repository](https://poggit.pmmp.io/plugins) — find plugins for the current API

> BetterLite-specific documentation will be published alongside the **1.0.0** release.

---

## 💬 Community & Support

Join our [Discord](https://discord.gg/vrPugybpJF) server to chat with the team and other users.

You can also post questions on [StackOverflow](https://stackoverflow.com/tags/pocketmine) under the tag `pocketmine`.

---

## 🧑‍💻 Developing Plugins

Want to write your own plugins? These resources cover the current PocketMine-MP-based API:

- 📘 [Developer documentation](https://devdoc.pmmp.io) — General documentation for PocketMine-MP plugin developers
- 📕 [Latest release API documentation](https://apidoc.pmmp.io) — Doxygen API docs for each release
- 📗 [Latest bleeding-edge API documentation](https://apidoc-dev.pmmp.io) — Doxygen API docs generated weekly from `major-next`
- 🛠️ [DevTools](https://github.com/pmmp/DevTools/) — Development tools plugin for building plugins
- 🧪 [ExamplePlugin](https://github.com/pmmp/ExamplePlugin/) — Example plugin demonstrating basic API features

> 🚧 The above links target the upstream PocketMine-MP project and will be replaced with BetterLite-native equivalents once 1.0.0 ships.

---

## 🤝 Contributing

Contributions are welcome and appreciated! 💜

- 🏗️ [Building and running BetterLite from source](BUILDING.md)
- 📜 [Contributing Guidelines](CONTRIBUTING.md)

New here? Start with the [issues labeled "Easy task"](https://github.com/betterlite/PocketMine-MP/issues?q=is%3Aissue%20state%3Aopen%20label%3A%22Easy%20task%22) to get familiar with the codebase.

---

## 📄 Licensing

This project is licensed under **LGPL-3.0**. Please see the [LICENSE](/LICENSE) file for details.

BetterLite is a fork of [PocketMine-MP](https://github.com/pmmp/PocketMine-MP) and inherits its LGPL-3.0 license. Neither BetterLite nor PocketMine-MP are affiliated with Mojang. All brands and trademarks belong to their respective owners. BetterLite is not a Mojang-approved software, nor is it associated with Mojang.
