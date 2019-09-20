# GameOn Driver Extensions
Version 190902 of the GameOn Driver introduces the ability to install extensions that can enhance the user's experience. An extension might allow them to get quick access to a Game Wiki, easily stream their Game via GameOn Capture to a streaming platform, create notes on the fly or even perform basic tasks like mathematical calculations. This gives developers an easy platform to offer game enthusiasts a way to expand their quality of life.

## Use case scenario
- A user spends a lot of time playing an MMORPG levelling their skills. In order to max out a skill, the user is calculating their experience targets per objective to estimate time and effort. An extension can be created for this game that mathematically provides them with the appropriate formula and answers based on some general information (such as current XP and target XP)
 
### Samples
Samples have been provided by RWE so that developers can get an easy idea of how an extension may be created.

- HTML Webview Extension [View Sample](https://github.com/RyanWalpoleEnterprises/GameOn-Driver-Extensions/tree/master/Sample%20Extensions/HTML%20Webview%20Extension)
Is an extension sample that takes advantage of the GameOn In-Game Overlay's "Extensions" area and adds a button that opens a lite web browser to the specified local HTML file. This sample includes a manifest, details HTML page and the general logic for the extension to function. The extension logic is a .clx file. CLX (Code LX Universal) can be edited with Visual Studio Code and the Code LX Editor (an upcoming version with native GameOn Extension Support is coming soon.)
