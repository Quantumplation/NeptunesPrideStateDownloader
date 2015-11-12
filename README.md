# Neptune's Pride State Downloader

Downloads the state of your Neptune's Pride 2 game.  If all the players in your
game run this in the background while the game proceeds, you can recreate a
complete history of the game state.

**Note:** This only saves state visible to _you_.

## Setup

1. Edit `App.config` and enter your username, password, and the game number of
   the game you wish to track (the number at the end of the game URL).
2. Change optional settings if you like.
   * `refreshSeconds`: how often to check for updated game state, in seconds.
     Defaults to two minutes.  Set it lower for faster-paced games.
   * `downloadDirectory`: the directory in which game state files will be saved.
     If this directory does not exist it will be created.
3. Run.

That's it.