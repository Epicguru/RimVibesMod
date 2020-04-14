# RimVibes
RimVibes adds Spotify integration into RimWorld, allowing you to control music playback without leaving the game. In future it will have more interesting features such as music automatically changing based on in-game events, or having a disco room that changes based on what music you are playing. See the plans section for more info.

## Quick info
* Can be used without Spotify Premium, but works best with Premium.
* Works on Windows and Linux, Mac support is planned soon™.

## Installation
Press Subscribe (and Like :D) on the Steam Workshop page. For non-Steam users, download the latest release from the Releases section on Github.

## How to use
Once you open the game with the mod installed, it should show a Terms of Use dialog that you should read and accept. Then, it will prompt you to connect your Spotify account to the mod (known as Authorizing). Simply follow the instructions and it should be fairly straightforward from there.
Next click the button on the main menu to check that your account is connected successfully.

![Main menu button](https://github.com/Epicguru/RimVibesMod/blob/master/Documentation%20Images/Main%20Menu%20Button.png)

If you are playing music on Spotify, it should display the name of the song.
Now you should also see a smaller, semi-transparent button that appears in the top-right area of your screen, by default.

![Main menu button](https://github.com/Epicguru/RimVibesMod/blob/master/Documentation%20Images/Main%20Menu%20HUD%20Button.png)

Clicking this brings up the control panel, where you can do things like pause, skip etc.

## Settings
You can control many important things from the settings menu in this mod. Simply go to Options>Mod Options>RimVibes and take a look at the options. The most important one is the Anchor and Offset settings. The Anchor changes where the control panel will appear, such as on the right or left side of the screen, and the Offset values allow you to finely adjust where you want to place the panel.

## Troubleshooting
Even though the mod is simple in functionality, there is some surprisingly complicated stuff going on in the background. Bugs are expected to come up, and you can help me fix them. Please create an issue here on Github to notify me of bugs.

## How to fix…
### Connected but no authority
This means that everything is working but you haven’t given Authority to RimVibes. Press the Authorize button and follow the instructions in the browser window that opens.

### Disconnected
This should generally never happen (by design). It means that the process that the mod launches behind the scene has crashed, or never started. You can re-launch the process by pressing Relaunch. If it crashes repeatedly, please submit a bug report.

### Not responding
The internal process has been launched but is not responding to requests. This may be caused by a Firewall, so check your firewall settings (uses ports 7868 and 7869).

## Technical stuff
Nerd stuff. I can't post the source for this mod because it could expose sensitive API key data, or expose the method that I use to encrypt client tokens. Having said that, it isn't too difficult to get hold of my API key if you try hard enough, but please don't ruin the fun for everyone :).
If you experience delay when pressing buttons, it may be due to the limit of API requests that I am allowed to make, which I can't fix or control.
The permissions that I use to control your spotify account are `user-modify-playback-state` and `user-read-playback-state`. That means that I don't have access to personal info.
