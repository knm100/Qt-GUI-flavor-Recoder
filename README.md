# Qt-GUI-Style-Recoder
Simple qt GUI flavor bash script to make recording screen by shortcuts easily. Only work on wlroots based wayland compositors ,uses wf-recorder as backend default.  Inspired by https://github.com/Vescrity/wfrc. 

default language is chinese, fallback language is english

default storage directory is ~/.

Features:
 Area selection or full screen(GUI Chooser),
 Record the audio(GUI Chooser),
 dialog for Notification(Qt style GUI dialog).


Dependencies:
wf-recorder,
bash,
grep,
slurp,
kdialog,
libpulse.

Usage /
(optional) Add it to your PATH /
(optional) Bind it to a keybind /
Run it for the first time to record and the second time it will stop recording 
