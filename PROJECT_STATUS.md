# Project Status

Snapshot reviewed: private prototype commit `4e48e46` (`main commit`).

## Verified in the current prototype

- Linux Qt companion window integrated with the normal mGBA game window
- ROM identification after cartridge load
- Read-only monitor executed from the emulator frame callback
- Polling every six frames, approximately 10 Hz at normal GBA speed
- FireRed (`BPRE`) and LeafGreen (`BPGE`) identification
- Re-resolution and validation of `gSaveBlock1Ptr` for every snapshot
- Current `mapGroup`, `mapNum`, and player coordinates normalized into a UI-independent state
- ROM-derived encounter methods, level ranges, probabilities, and area encounter rates
- Structural discovery and decoding of species names from the loaded ROM
- Qt state delivery queued to the GUI thread
- Unsupported or structurally incompatible inputs fail closed
- Android API 28 display shell with secondary-display detection, `Presentation`, and single-screen fallback
- Debug APK built with API 36 and single-screen path tested on a physical Retroid Pocket 6

## Not yet implemented or verified

- mGBA core lifecycle connected to the Android app through JNI
- Game framebuffer rendered in the Android primary display
- Physical AYN Thor dual-screen validation
- Encounter sprites
- Trainers, bosses, progression, party, Pokédex, and Nuzlocke state
- Complete map-name metadata beyond Pallet Town through Viridian Forest

## Next engineering checkpoint

Cross-compile the mGBA core with the Android NDK, expose a minimal JNI lifecycle, and render the unscaled GBA framebuffer on the primary display while keeping the verified secondary-display shell.

