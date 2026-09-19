# Contribution Boundaries / 担当範囲

This case study separates my project work, AI assistance, and upstream ownership.

| Area | My responsibility | AI assistance | Upstream / third party |
| --- | --- | --- | --- |
| Product concept | Defined the dual-screen Nuzlocke companion and target experience | Helped refine requirements | — |
| Architecture | Chose read-only integration, normalized state, platform-independent parser boundary, and fail-closed behavior | Investigated options and proposed implementations | mGBA's existing core/frontend architecture |
| Live state | Specified automatic current-location tracking and validated behavior | Assisted with implementation and debugging | Pokémon game memory layouts documented by pret repositories |
| ROM parsing | Required ROM-derived encounters instead of manual route selection | Assisted with structural scanning and validation code | Game data formats; no ownership claimed |
| Linux UI | Defined companion behavior and reviewed the working vertical slice | Assisted with Qt integration code | Qt and mGBA Qt frontend |
| Android prototype | Defined AYN Thor dual-display goal and tested the shell on a physical Android handheld | Assisted with Android, Gradle, and porting scaffolding | Android SDK `Presentation`; mGBA upstream |
| Documentation | Supplied project facts, intent, constraints, and final approval | Assisted with drafting and organization | — |

## Not claimed as my work

- The mGBA emulator, its emulation core, frontends, build system, or existing features
- RetroArch or the libretro API
- Pokémon games, characters, names, ROM data, or other Nintendo / Game Freak / Creatures assets
- `pret/pokefirered` research and decompilation work
- Framework, SDK, or library code

## Repository scope

This public repository contains only portfolio documentation. The modified prototype source is kept separate from this case study so generated build products and a large amount of unchanged upstream source are not mistaken for original authorship.

