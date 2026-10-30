# Mega Man X4 - No Music

A declarative `.psxmod` for [Mega Man X4 Recomp](https://github.com/mstan/MegaManX4Recomp) that mutes all music while preserving voices, cutscene audio, and sound effects.

## Download

[Latest release](https://github.com/YossefKhalil/MegaManX4Recomp-NoMusic/releases/latest)

## Author

Yossef Khalil — https://github.com/YossefKhalil

Built with OpenCode (DeepSeek V4.1 Flash).

## Purpose

Music-free play for players who prefer no music. I'm a Muslim and prefer to play without music.

## Behavior

- Replaces `XA/BGM1_U.XA`, `BGM2.XA`, `BGM3.XA`, `BGM4.XA`, and `BGM5_U.XA` with digital silence via `disc_raw` overlays.
- Covers title, menu, stage, and boss music.
- Leaves voices, boss intros, cutscene audio, and SPU sound effects unchanged.
- Does not modify the stock disc.

## Install

1. Open the launcher's **Mods** page.
2. Choose **Install Mod Package** and select `mmx4.nomusic-1.0.1.psxmod`.
3. Enable **Mute All Music (Menus + Gameplay)**.
4. Select the original USA `.cue` and boot fresh.

## Compatibility

Mega Man X4 Recomp 1.0.18; USA SLUS-00561 disc.

## License

MIT
