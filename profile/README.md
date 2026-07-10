# RustScript

**RustScript is a Rust-inspired scripting language and portable VM ecosystem for building typed, embeddable automation across edge runtimes, controllers, browsers, and host applications.**

RustScript combines familiar Rust-like syntax, strict typing, host-function bindings, portable bytecode/AOT artifacts, and debugger/runtime tooling.

## Quick links

- [Website](https://rustscript.org/)
- [Playground](https://playground.rustscript.org/)

## Repositories

| Area | Repository | Description |
|---|---|---|
| Language + VM | [rustscript](https://github.com/rustscript-lang/rustscript) | RustScript compiler, bytecode VM, tooling, and WASM package |
| Specification | [spec](https://github.com/rustscript-lang/spec) | Language specification and shared assets |
| Website source | [website](https://github.com/rustscript-lang/website) | Source for rustscript.org |
| Compatibility frontends | [rustscript-compat-frontends](https://github.com/rustscript-lang/rustscript-compat-frontends) | JavaScript and Lua frontend plugins for RustScript VM compatibility |
| CLR VM | [rustscript-clr-vm](https://github.com/rustscript-lang/rustscript-clr-vm) | RustScript runtime on Microsoft CLR |
| Embedded runner | [rustscript-embedded](https://github.com/rustscript-lang/rustscript-embedded) | RustScript integration for constrained and embedded targets |
| Data plane | [pd-edge](https://github.com/rustscript-lang/pd-edge) | Programmable data plane powered by RustScript |
| Control plane | [pd-controller](https://github.com/rustscript-lang/pd-controller) | Control plane for pd-edge |
| Bevy example | [rustscript-bevy-gameplay](https://github.com/rustscript-lang/rustscript-bevy-gameplay) | Example repository for embedding RustScript in Bevy gameplay |
| egui example | [rustscript-egui-ui](https://github.com/rustscript-lang/rustscript-egui-ui) | Example repository for embedding RustScript in egui UI apps |
| Pingora example | [rustscript-pingora-gateway](https://github.com/rustscript-lang/rustscript-pingora-gateway) | Example repository for scripting a Pingora gateway with RustScript |

## Project focus

- Portable typed scripts with Rust-like syntax
- Embedding into apps, games, gateways, edge runtimes, and controllers
- Compatibility frontends through plugins
- Browser-based experimentation through the playground
