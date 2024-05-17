# One Dark Pro Preset for Windows Terminal

## [GitHub Repo](https://github.com/VictorPLopes/OneDark-Pro-Windows-Terminal)

I like to keep my software consistent and uniform, which is why I try to use the same theme on most of my apps. This is why I made a Windows Terminal theme inspired by my favorite theme, [Binaryify's One Dark Pro theme for Visual Studio Code](https://github.com/Binaryify/OneDark-Pro). There is already a One Dark implementation bundled with Windows Terminal, "One Half Dark", but it's not exactly the same as Binaryify's.

![Windows Terminal](./screenshots/one-dark-pro.png)

## VictorPL's One Dark Collection

- [One Dark Pro for Visual Studio Code (by Binaryify)](https://github.com/Binaryify/OneDark-Pro)
- [One Dark Pro for Visual Studio (by Binaryify)](https://marketplace.visualstudio.com/items?itemName=zhuangtongfa.onedarkpro)
- [One Dark Pro for Windows Terminal](https://github.com/VictorPLopes/OneDark-Pro-Windows-Terminal)
- [One Dark Pro for Kitty Terminal](https://github.com/VictorPLopes/OneDark-Pro-Kitty-Terminal)
- [One Dark Pro for Chromium Browsers](https://github.com/VictorPLopes/OneDark-Pro-Chromium)
- [One Dark Pro for Starship Prompt](https://github.com/VictorPLopes/OneDark-Pro-Starship)
- [One Dark Pro for Neovim (by olimorris)](https://github.com/olimorris/onedarkpro.nvim)
- [One Dark Pro for iTerm (by chinhsuanwu)](https://github.com/chinhsuanwu/one-dark-pro-iterm)
- [One Dark for JetBrains IDEs (by Mark Skelton)](https://plugins.jetbrains.com/plugin/11938-one-dark-theme)

![One Dark Pro Collection](./screenshots/one-dark-pro-collection.png)

## Screenshots

### PowerShell 7, Windows Terminal, Windows 11

![Windows](./screenshots/one-dark-pro-windows.png)

## Pre-requisites

- If you are using the Starship Prompt, [my One Dark Pro preset for Starship](https://github.com/VictorPLopes/OneDark-Pro-Starship) is highly recommended. If you aren't, you can still use the theme, but it won't be as consistent and I highly recommend you give Starship a try.

## How to install

The installation process is simple, just follow the steps below:

- Download the latest [source code release](github.com/VictorPLopes/OneDark-Pro-Windows-Terminal/releases), save it anywhere you want, extract the zip file, open the `One-Dark-Pro.json` file and copy its contents. Alternatively, you can use the `git clone` command to clone the repository to your computer or simply copy the following JSON code:

```json
{
    "background": "#282C34",
    "black": "#3F4451",
    "blue": "#61AFEF",
    "brightBlack": "#4F5666",
    "brightBlue": "#4DC4FF",
    "brightCyan": "#4CD1E0",
    "brightGreen": "#A5E075",
    "brightPurple": "#DE73FF",
    "brightRed": "#BE5046",
    "brightWhite": "#E6E6E6",
    "brightYellow": "#E5C07B",
    "cursorColor": "#528BFF",
    "cyan": "#56B6C2",
    "foreground": "#ABB2BF",
    "green": "#98C379",
    "name": "One Dark Pro",
    "purple": "#C678DD",
    "red": "#E06C75",
    "selectionBackground": "#ABB2BF",
    "white": "#D7DAE0",
    "yellow": "#D19A66"
}
```

- Open Windows Terminal and press `Ctrl + ,` to open the Settings. You can also open it by clicking on the down arrow on the top bar and selecting `Settings`.
- From the settings, click on the gear icon on the bottom left corner to open the `settings.json` file.
- There, scroll down to the `schemes` section and paste the JSON code you copied earlier at the end of the list. Make sure to add a comma at the end of the last scheme before pasting the new one.
- Save the file and go back to the Terminal's settings GUI. There, click on the Color Schemes button and select `One Dark Pro` from the list, then scroll down and click on the "Set as default" button. Alternatevely, instead of going to the Color Schemes section, you can set your theme to a specific profile by clicking on it (still in the settings GUI) and heading to the Appearance section. From there, you can select the `One Dark Pro` theme from the dropdown menu.
- Click on the "Save" button on the bottom right corner and close the settings window. Your terminal should now be using the One Dark Pro theme.

## Support me

If you like this theme, and my work, you can always support me via **[Ko-fi](https://ko-fi.com/victorplopes)**. If I get enough support, I will pay the developer registration fee and publish my port of the One Dark Pro theme for Chromium Browsers on the Chrome Web Store.
</br>
<a href='https://ko-fi.com/S6S7DTZCA' target='_blank'><img height='36' style='border:0px;height:36px;' src='https://storage.ko-fi.com/cdn/kofi2.png?v=3' border='0' alt='Buy Me a Coffee at ko-fi.com' /></a>

## [CHANGELOG](./CHANGELOG.md)
