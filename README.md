# Zoom Zero Day app

This is a tiny application that runs a script to disable Zoom's hidden web server on MacOS. This allows those less technically inclined to apply the fix without having to resort to using the terminal. Just download the ZIP file in this repo, double-click on it in Finder to unzip it, then double-click on the resulting _ZoomZeroDay.app_ file. All of a sudden, _nothing will happen!_ It ain't fancy. You only need to do this once, however. At the same time, there's no harm in going double-click-happy if you really want to. Have at it!

If you have default security settings, MacOS probably won't let you open the app. If you hold _option_ down and right-click on the application, then choose _Open_, you'll be given a choice to open it instead of being completely denied.

The simple script in the application is taken from the end of [this article](https://medium.com/@jonathan.leitschuh/zoom-zero-day-4-million-webcams-maybe-an-rce-just-get-them-to-visit-your-website-ac75c83f4ef5)

For those with more suspicious minds and who want to make sure I'm not a nefarious actor, after you download and unzip the _ZoomZeroDay.app.zip_ file right-click on _ZoomZeroDay.app_ in the Finder and choose _Show Package Contents_. Click or double-click on _Contents_, then _MacOS_. Right-click on _ZoomZeroDay_ and choose _Open With_. Find _TextEdit_ and choose it. You'll see part of the script that was presented at the bottom of the referenced article. This app only addresses _ZoomOpener_, not _RingCentralOpener_.

This application is presented as a public service. I retain no rights over the code and do not claim ownership of the script used therein.
