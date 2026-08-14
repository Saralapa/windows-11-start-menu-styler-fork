# Windows 11 Start Menu Styler - Fork

Fork of [m417z's Windows 11 Start Menu Styler](https://github.com/m417z/my-windhawk-mods), a [Windhawk](https://windhawk.net/) mod that lets you customize the Windows 11 Start Menu with community themes or your own custom styles.

This fork is based on upstream **v1.3.1** ([commit `7e154be`](https://github.com/m417z/my-windhawk-mods/commit/7e154beef18470df2d8222eabeb1c6415cc785f2)).

## What it does

- Applies visual themes to `StartMenuExperienceHost.exe`, `SearchHost.exe`, and `SearchApp.exe`.
- Supports control style overrides (size, color, layout) and resource variable overrides targeting the Start Menu's XAML resources.
- Ships with several ready-to-use themes (NoRecommendedSection, SideBySide, Windows10, TranslucentStartMenu, RosePine, Everblush, and more).

Full usage docs, theme gallery, and advanced styling syntax are documented inline in [`main.cpp`](main.cpp) (Windhawk mod readme header).

## Differences from the base version

This fork changes the **Everblush** theme:

- Background/border colors switched from green/yellow (`#8ccf7e`, `#e5c76b`) to purple/blue (`#9967e4`, `#5277ff`).
- A `WindhawkBlur` effect was added to the menu background (previously a flat color).
- One element's visibility was set to `Collapsed`.

Aside from that and the mod `@id`/`@name` being renamed for the fork, the code is identical to the base version.

## Installation

This is a [Windhawk](https://windhawk.net/) mod, not a standalone application:

1. Install [Windhawk](https://windhawk.net/).
2. Add this mod's source (`main.cpp`) as a custom mod, or load it via the Windhawk mod editor.
3. Configure themes/styles in the mod's settings.

## Credits

- Original mod by [m417z](https://github.com/m417z) — [ramensoftware/windhawk-mods](https://github.com/ramensoftware/windhawk-mods).
- Theme gallery: [The Windows 11 start menu styling guide](https://github.com/ramensoftware/windows-11-start-menu-styling-guide).

## License

GNU General Public License v3.0.
