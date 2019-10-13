# Emby Server Launcher for OS X
Helper app to work around Emby Server launch issues on OS X.

This script ensures that Emby Server both launches and terminates properly,
working around the known issues [described
here](https://emby.media/community/index.php?/topic/54022-v3260-doesnt-fully-quit/).

## Installation:
Clone this git repo, or [download
it](https://github.com/thebnich/EmbyLauncher/archive/master.zip) and unzip it
anywhere that Spotlight/Launchpad searches. Your home directory or Downloads
directory will work fine.

That's it -- Spotlight/Launchpad should automatically detect the launcher. Just
run "Emby Server" to fire the launcher!

Note that you'll see both "EmbyServer" (the actual Emby app) and "Emby Server"
(the launcher) in Spotlight/Launchpad. Follow the steps below to fix this.

### Optional, but recommended:
Hide the existing EmbyServer from Spotlight/Launchpad by executing
```
mv /Applications/EmbyServer.app /Applications/.EmbyServer.app
```
in your terminal.
