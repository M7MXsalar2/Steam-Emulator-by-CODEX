# Steam-Emulator-by-CODEX
CODEX emulator v1.0.1.41 - Steamclient version (x64-x86)


------------

1. Download Emulator files from Releases page
[https://github.com/M7MXsalar2/Steam-Emulator-by-CODEX/releases](https://github.com/M7MXsalar2/Steam-Emulator-by-CODEX/releases)
2. Backup games original **steam_api.dll** / **steam_api64.dll**
3. Copy **steam_api.dll** (or **steam_api64.dll**) and related **steam_emu.ini** files to game directory
4. Edit **steam_emu.ini** file: `Line 21: AppId=442120`
5. Set `AppId` to match games identifier
http://store.steampowered.com/app/[gameid]
6. Enjoy

------------

**As per Pandoriaantje's findings**:<br>
There are 2 versions: `CODEX api-only build` and `SteamClient build`.<br>
For the `SteamClient build`, *as archived here*, one needs to (hex) edit the original `steam_api(64).dll` manually, and replace `SHELL32` with `CODEX(64)`<br>
Afterwards, rename original `steam_api(64).dll` to `steam_api(64).cdx` for CODEX redirection purposes.

------------

I AM NOT CODEX, I AM NOT RELATED IN ANY WAY TO CODEX. JUST SHARING WHAT THEY LEFT AFTER THEIR GOODBYES.

~ FAREWELL CODEX ~
