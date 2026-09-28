# OpenRock-Compat

Version-selection for a library whose exported API is keyed by version - a provider exposing {"1.0.0": apiV1, "2.0.0": apiV2} resolves per-consumer against that consumer's own declared apiVersion range.

Part of the [OpenRock](https://github.com/codex-alchemist-dev/OpenRock) Minecraft Bedrock mod-packaging ecosystem - a Codex Alchemist project, under Fireball Everything. Consumed as a real git submodule at `libs/compat` in the main OpenRock repo, and directly `npm require`/`import`-able (real top-level CommonJS exports, esbuild-CJS/ESM-interop-compatible) by any mod's own build-time kernel registration or real in-game script.

## License

MPL-2.0. See [LICENSE](LICENSE).
