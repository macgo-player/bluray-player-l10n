# bluray-player-l10n
Localization files for Macgo Blu-ray Player

## XLIFF Files and Stringdict Files

By following Apple's [Internationalization and Localization Guide][], this project contains a `.xliff` file for each language, and a `.stringsdict` file for the corresponding plural rule.

- `[LanguageID].xliff`
- `[LanguageID].lproj/Localizable.stringsdict`

Development Language (Base Language) is English. 

### Special strings in XLIFF

Do not translate `Info.plist` in xliff, especially version and copyright information. Leave them blank. They will be ignored currently.

The source text contains some special symbols, which looks different on a different OS other than macOS. Be aware of them.

[Internationalization and Localization Guide]: https://developer.apple.com/library/content/documentation/MacOSX/Conceptual/BPInternational/LocalizingYourApp/LocalizingYourApp.html
