# BuildCraft-Localization

Localization repository for BuildCraft.

## Repositories

* `3.7.x` - covers BuildCraft 3.2.x - 3.7.x releases (Minecraft 1.3.2 - 1.5.2).
- `4.2.x` - covers BuildCraft 4.2.x releases (Minecraft 1.6.4).
- `7.1.x` - covers BuildCraft 7.1.x - 7.2.x releases (Minecraft 1.7.10 - 1.8.9).
- The main repository covers BuildCraft 7.99.x - 8.x releases.

Translations for BuildCraft Compat are stored on its separate repository.

## License

The BuildCraft license applies.

## Contributing

The best way to contribute to pre-7.99.x versions is to use the online [Weblate interface](https://weblate.asie.pl/projects/buildcraft/).

For 7.99.x and above, use GitHub pull requests.

### en_US

The en_US localization is mirrored in this repository to support Weblate translations; however, the version in the main mod repository is the one packaged with releases.

### Encoding

For Minecraft 1.7.10+, files must be encoded in UTF-8 without BOM. Pull requests, submissions or contributions not encoded in UTF-8 without BOM will have to be rejected or reverted.

For Minecraft 1.3.2 - 1.6.4, files must be encoded in ISO-8859-1, using escape codes for Unicode characters.

### Issues

Errors in translation that you are somehow unable to make a pull request for, can be filed here. Missing localization support or code issues that affect localization should be filed in the main BuildCraft repository.

### Gate localization

If your language requires a specific sequence for the Gates, you can replace the "%s" with "%1$s" for the material and "%2$s" for the type of gate (AND and OR)
