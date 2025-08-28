# GrammarPolice-Translations
This repository contains all the language files for GrammarPolice. <br>
GrammarPolice uses the Microsoft Speech Platform, which allows GrammarPolice to use a range of languages. In order for GrammarPolice to support each language, files need to be translated into that language first.

ℹ️ When GrammarPolice is updated, these files are included. Users can make a contribution to GrammarPolice to improve its language compatibility.<br><br>

## How to use your language with GrammarPolice:
1. Install the Microsoft Speech Platform Runtime from here: https://www.microsoft.com/en-us/download/details.aspx?id=27225
 <br>→ Use the larger SpeechPlatformRuntime.msi file (2.6 MB) which supports x64.

2. Install the language you want to use from here: https://www.microsoft.com/en-us/download/details.aspx?id=27224
 <br>→ Make sure you install the MSSpeech_SR file for your language, not TTS.

## Want to contribute a translation?
All contributions are appreciated. Please try to keep translations as accurate as possible, as they will be used by other people.

If you are contributing to a new language, you will need to:
1. Create a new grammar folder to match your language code and follow the folder structure.
2. Translate the XML files to your language in your new folder.  Only change the strings underneath PHRASES.  Do not change the names, commands, or targets.
3. Create a new XML file in the interface folder matching your language.  Only change the menu and item NAMES.  Do not change the actions.
4. Update the README file with a tick.
5. **Submit a [Pull Request](https://docs.github.com/en/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/creating-a-pull-request) for it to be added.**

If you get stuck, visit the [IPT Support Server](https://discord.gg/AuJCUag). Thank you for supporting our plugins. 

| Code   | Language (Region)                            | Status |
|--------|----------------------------------------------|--------|
| ca-ES  | Catalan (Spain)                              | ❌     |
| da-DK  | Danish (Denmark)                             | ❌     |
| de-DE  | German (Germany)                             | ✅     |
| en-AU  | English (Australia)                          | ✅     |
| en-CA  | English (Canada)                             | ✅     |
| en-GB  | English (United Kingdom)                     | ✅     |
| en-IN  | English (India)                              | ✅     |
| en-US  | English (United States)                      | ✅     |
| es-ES  | Spanish (Spain)                              | ✅     |
| es-MX  | Spanish (Mexico)                             | ❌     |
| fi-FI  | Finnish (Finland)                            | ❌     |
| fr-CA  | French (Canada)                              | ❌     |
| fr-FR  | French (France)                              | ✅     |
| it-IT  | Italian (Italy)                              | ✅     |
| ja-JP  | Japanese (Japan)                             | ❌     |
| ko-KR  | Korean (South Korea)                         | ❌     |
| nb-NO  | Norwegian Bokmål (Norway)                    | ❌     |
| nl-NL  | Dutch (Netherlands)                          | ❌     |
| pl-PL  | Polish (Poland)                              | ❌     |
| pt-BR  | Portuguese (Brazil)                          | ❌     |
| pt-PT  | Portuguese (Portugal)                        | ❌     |
| ru-RU  | Russian (Russia)                             | ✅     |
| sv-SE  | Swedish (Sweden)                             | ✅     |
| zh-CN  | Chinese (Mainland China, Simplified)         | ❌     |
| zh-HK  | Chinese (Hong Kong, Traditional)             | ❌     |
| zh-TW  | Chinese (Taiwan, Traditional)                | ❌     |

