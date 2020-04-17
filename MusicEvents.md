# Setting up music events

To configure this feature, go into the mod settings and click the `Change custom music events` button.

Let's take a look at the UI.

### UI Overview

![UI Overview](https://github.com/Epicguru/RimVibesMod/blob/master/Documentation%20Images/UI%20Overview.png)

In this example, it is configured to play a random song from a playlist whenever a raid starts. I'll explain how this was achieved.
Here are what each button and option does:
1. Click to add a new event action.
2. Click to delete this action.
3. Toggles weather this action is enabled.
4. Clicking this will change the type of event that the action responds to. For example, *Raid*, *Wedding Ceremony*, *Death*, *Small Threat*, *Quest Recieved* etc. If it is *None* then the action will never be triggered.
5. Changes the type of action. There are only 3 options: *Play Music*, *Pause Music*, or *None*. None does nothing, obviously.
6. When playing music, you can either play from a playlist or you can play a specific track. If you want to play from a playlist, enable this. If you just want to play a single track, disable this.
7. If playing from a playlist, enabling this will select a random song from the playlist. If disabled, it will start playing in order, starting with the first song in the playlist.
8. Clicking this will try to run the action, such as playing one of the songs from the playlist. If clicking this does nothing, you have configured the action wrong (or it is disabled).
9. The Spotify track or playlist URI. See the following section for how to find this.

### Finding a playlist URI
To get the URI of a spotify playlist, go onto the Spotify desktop app and find the playlist, then do this:
![Playlist URI](https://github.com/Epicguru/RimVibesMod/blob/master/Documentation%20Images/HowToCopyPlaylistURI.png)

### Finding a track URI
Finding the URI of a track is very similar:
![Playlist URI](https://github.com/Epicguru/RimVibesMod/blob/master/Documentation%20Images/HowToCopyTrackURI.png)
