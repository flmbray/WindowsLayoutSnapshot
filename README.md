WindowsLayoutSnapshot
=====================

Ever switch monitor configs on your laptop and all of your windows are squished down in size and in the wrong position?  Ever want to minimize all windows but save their layouts and min-max'ed states for later?

WindowsLayoutSnapshot is a windows app to remember and restore window positions.

If you don't want the source code, just download `WindowsLayoutSnapshot.exe`.  There's no installer; just put it in your Startup folder.

The app takes a "snapshot" of your windows layouts every thirty minutes.  You can see the list of snapshots when you click on the tray menu icon.


#### Tips
* When there are many stored snapshots, all very recent ones are shown, plus more spaced-out but distant past snapshots.
* Automatically taken snapshots are shown in normal text.  Manually taken snapshots (`Take Snapshot`) command are shown in **bold**.
* As you mouse over each snapshot, it is restored, so it's easy to find the layout you want.
* Snapshots keep track of, and restore, the "normal size" of windows even if they're currently minimized or maximized.
* This app makes sure all windows fit inside a currently-visible display when restoring snapshots.  Because of that, if you ever have a window that's off-screen because of a bug in other software, just restore the "(Just now)" snapshot.
* Snapshots are not stored across app instances (or, thus, restarts).


#### Screenshot
<img src="https://raw.github.com/adamsmith/WindowsLayoutSnapshot/master/screenshot.png" />


#### License
This app and its source code are released into the public domain.

From https://github.com/adamsmith/WindowsLayoutSnapshot/issues/8:
Hi,

I see this project is not maintained for years.

But there are a lot of good forks, my suggestion is to select/create a new fork, and do all the changes from the other forks there.

Then create a community and so on.

See the forks here: https://techgaun.github.io/active-forks/index.html#https://github.com/adamsmith/WindowsLayoutSnapshot
