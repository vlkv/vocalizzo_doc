## Release Notes

### 2.2-58 (24 Jan 2021)
* Notes become more bright/dark (it depends on whether dark/bright theme is used) if user sings correctly.
* Recorded voice line becomes transparent after a while.
* Application license is validated at startup.

### 2.1-49 (02 Aug 2020)
* Added some new exercises, read [more](https://vlkv.github.io/vocalizzo_doc/new_exercises_and_how_to_find_them.html) about it.
* Implemented a tiny red "new" tag, so users could easily find the new exercises.

### 2.0-48 (11 May 2020)
* Pitch Monitor tool which is great for vocal sirens and slides. It is located in Main menu -> Pitch Monitor. Read [more](https://vlkv.github.io/vocalizzo_doc/pitch_monitor.html) about it, have fun!
* 'What's New' dialog. It will show up once during startup after updating the Vocalizzo app on the device.
* Minor improvements of Privacy Policy and About dialogs.

### 1.12-43 (4 May 2020)
Fixed crash in native pitch detector wrapper code.

### 1.11-39 (22 Apr 2020)
* Ability to skip to a descending part of an exercise (the "Vocalise Direction" button).
* Moved "Info" button to the options menu.
* (Lite only) Changed the Vocalizzo Full version promotion buttons to conform to the new Google "Ads and Monetization" policy update.

### 1.10-38 (16 Apr 2020)
* Disabling the screensaver while exercise is playing.
* Mark the "middle C" (the C4) note on the musical keyboard with a black dot.
* Audio library updated to the latest version.

### 1.9-37 (7 Apr 2020)
* Drag and drop exercises within a playlist for custom ordering.
* Drag and drop groups (on main screen) for custom ordering.
* Remove exercises and playlists with swipe gesture.
* Show paid exercises in disabled font on 'Select exercises to add' screen.

### 1.8-36 (3 Apr 2020)
* Fixed bug voice pitch detection is broken after exercise reaches the end.
* Optimized asset resources.
* Fixed formatting of Privacy Policy document.
* Showing paid exercises in Lite version of the app.
* Fixed crash in TrainingViewModel.updateLiveData.

### 1.7-32 (25 Mar 2020)
* Ability to pause a running exercise and then resume from that point (Play/Stop button is replaced with Play/Pause).
* Highlight the 'pressed' keys of the keyboard while exercise is playing.
* Using icons for buttons (Play/Pause and Mic buttons).
* Fixed flickering the image after the Play button has been pressed.

### 1.6-31 (21 Mar 2020)
Whistle register support. Now Vocalizzo is able to play all the exercises in a full register of grand piano (notes from A0 to C8).

### 1.5-30 (21 Mar 2020)
* Fixed issue with too sensitive vocal range measure tool (the 'Mic' button).
* Trying to support devices with Android 5.1, 5.0, 4.4 (using int16 instead of float for audio stream).
* New pitch detector implemented in C++ (better latency, smoother plot).
* Setting to choose the pitch detection algorithm or disable it (if you wish).
* SurfaceView for rendering recorded pitch TrainingActivity with a better performance.

### 1.4-21 (1 Feb 2020)
* Fixed crash VocalizzoException at r.v.v.g.TrainingActivity.doPlay.
* Fixed crash IllegalArgumentException at r.v.v.g.TrainingActivity.onStop.
* 'Lyrics' for the exercises.
* Optimizations for recorded pitch rendering.
* 'RateThisApp' dialog.

### 1.3-18 (4 Jan 2020)
* The first exercise note is the note at 1/3 of the vocal range (not the lowest note as before). I believe it's more natural and comfortable to start singing exercises somewhere just below the middle of your vocal range.
* Fixed bug in a few exercises: the highest note wasn't reached.
* Landscape layout improvements.

### 1.2-15 (30 Nov 2019)
* Support for different pitch notation systems (Scientific, Helmholtz, Solfege).
* Hide "info" button when exercise has no info.
* Small layout changes.
* Better names for a few exercises.

### 1.1-12 (3 Nov 2019)
* Added more exercises!
* Added menu item with URL to Full version of Vocalizzo app.
* Fixed crash if vocal range is maximized.
* Improved sensitivity of MIC on Vocal Range screen.
* Fixed main menu bug.
* Fixed missed resources issue.

### 1.0-10 (21 Oct 2019)
* Support for old devices down to API 19.
* Various minor code fixes.
