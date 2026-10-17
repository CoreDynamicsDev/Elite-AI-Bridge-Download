<p align="center">
  <img src="https://raw.githubusercontent.com/CoreDynamicsDev/Elite-AI-Bridge/main/branding/Elite_AI_Bridge_Icon.png" alt="Elite AI Bridge icon" width="128">
</p>

# Elite AI Bridge 2.0

**A free Windows companion app for Elite Dangerous.**

Elite AI Bridge puts live ship information and flight controls into a retro command-deck interface. Use its tools without AI, or optionally add a voice-controlled AI co-pilot using your own OpenAI API key.

## Download

**[Get Elite AI Bridge from GitHub Releases](https://github.com/CoreDynamicsDev/Elite-AI-Bridge-Download/releases/latest)**

1. Open the latest release, expand **Assets**, and download the Windows installer (`.exe`).
2. Run the installer and follow its on-screen setup instructions.
3. Launch Elite AI Bridge and complete the first-run wizard.
4. Launch Elite Dangerous to connect live game information.

**Windows note:** The installer is not yet code-signed, so Windows may show an unknown-publisher or SmartScreen warning. Only obtain the installer from this official repository. Review the release's SHA-256 checksum to verify the file you downloaded.

For the in-game overlay, use Elite Dangerous in **Borderless** or **Windowed** mode. The overlay does not display in exclusive fullscreen mode.

## What's included in version 2.0

- **Flight Deck:** live ship, shields, hull, fuel, modules, cargo, event log, route jumps and one-click flight actions.
- **Combat:** target information, fighter and wing controls, and resource extraction site discovery for bounty hunting.
- **Trade:** route searches, trade loops and a trip ledger.
- **Navigation:** live route progress, fuel stars and bookmarks.
- **Colonization:** construction progress, remaining deliveries and supply locations.
- **Commander:** ranks, career statistics, session totals and additional commander statistics.
- **In-game overlay:** optional on-screen flight interface for borderless/windowed gameplay.
- **Ship voice:** locally generated callouts and spoken alerts.
- **Setup wizard and guided tours:** first-run setup and explanations of each module.
- **Optional AI co-pilot:** push-to-talk AI features using an API key you supply.

**Latest: 2.0.3.** The Bridge now checks for updates every time it starts, and the DEEP / VERY DEEP / HIGH voice pitch settings work. 2.0.2 added FLEET on the Commander page: where every stored ship is, with a key to plot a route to it.

Version 2.0 introduces a redesigned interface and setup experience. See the [full changelog in the source repository](https://github.com/CoreDynamicsDev/Elite-AI-Bridge/blob/main/CHANGELOG.md).

## Optional AI co-pilot and privacy

The core Bridge works **without** an OpenAI API key. AI features require your own OpenAI API account and key; API usage may incur separate charges from OpenAI. Never post keys in screenshots, public issues or support files.

See [Privacy and API Keys](https://github.com/CoreDynamicsDev/Elite-AI-Bridge/blob/main/PRIVACY_AND_API_KEYS.md) and [Security](https://github.com/CoreDynamicsDev/Elite-AI-Bridge/blob/main/SECURITY.md) for details.

## Source code and support

- **[Full source code and build instructions](https://github.com/CoreDynamicsDev/Elite-AI-Bridge)**
- **[Report a bug or request a feature](https://github.com/CoreDynamicsDev/Elite-AI-Bridge/issues)**
- **[Support development on Ko-fi](https://ko-fi.com/eliteaibridge)**

If you encounter an issue, go to **Setup > Status** in the Bridge to create a support file. **Review the ZIP before sharing it publicly**: diagnostic files may include local paths, controller names, settings and game-state information.

## Disclaimer

Elite AI Bridge is an independent community-developed application. It is not affiliated with, sponsored by, approved by or endorsed by Frontier Developments plc or OpenAI. Elite Dangerous and related intellectual property belong to their respective owners. See the [license](https://github.com/CoreDynamicsDev/Elite-AI-Bridge/blob/main/LICENSE.txt) and [third-party notices](https://github.com/CoreDynamicsDev/Elite-AI-Bridge/blob/main/THIRD_PARTY_NOTICES.md).
