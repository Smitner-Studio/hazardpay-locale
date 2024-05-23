# Game (Hazard Pay)

[Hazard Pay](https://smitner.studio/hp?utm_source=github) is using the `gettext` method of translation in the [Godot Engine](https://godotengine.org).

## Getting started

1. [Poedit](https://poedit.net/) is recommended, install it for your OS.
2. Inside Poedit and open the `translation_template.pot` file.
3. Click "Create a new translation" on the bottom of the window.
4. Enter in the translation language, and you're good to go!
5. After translating, save the file, this should save two files `.po` and `.mo` (`.mo` can be ignored)

## Testing your translations / Seeing it in-game

> If you don't have access to a build, reach out on [Discord](https://smitner.studio/discord) and tag `@Smitner`.

[Hazard Pay](https://smitner.studio/hp?utm_source=github) supports loading translation files at runtime, simply place the `.po` file inside a directory with the name `locales/` inside the game's data folder. If the folder is not present, create it.

### Data folder locations
- Windows: `%APPDATA%\Godot\app_userdata\Hazard Pay`
- macOS: `~/Library/Application Support/Godot/app_userdata/Hazard Pay`
- Linux: `~/.local/share/godot/app_userdata/Hazard Pay`

## Submitting your translation

1. [Fork](https://github.com/Smitner-Studio/hazardpay-locale/fork) this repository.
2. Commit the new translation file (`.po`)
3. Submit a [Pull Request](https://github.com/Smitner-Studio/hazardpay-locale/compare)
4. Thank you! You'll now find yourself in [Hazard Pay](https://smitner.studio/hp?utm_source=github)'s credits. <3

