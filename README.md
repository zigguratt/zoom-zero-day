# Zoom Zero Day app

This is a tiny application that runs a script to disable Zoom's hidden web server on MacOS. This allows those less technically inclined to apply the fix without having to resort to using the terminal.

The simple script in the application is taken from the end of [this article](https://medium.com/@jonathan.leitschuh/zoom-zero-day-4-million-webcams-maybe-an-rce-just-get-them-to-visit-your-website-ac75c83f4ef5)

For those with more suspicious minds and who want to make sure I'm not a nefarious actor, after you download and unzip the _ZoomZeroDay.app.zip_ file right-click on _ZoomZeroDay.app_ in the Finder and choose _Show Package Contents_. Click or double-click on _Contents_, then _MacOS_. Right-click on _ZoomZeroDay_ and choose _Open With_. Find _TextEdit_ and choose it. You'll see part of the script that was presented at the bottom of the referenced article. This app only addresses _ZoomOpener_, not _RingCentralOpener_.

This application is presented as a public service. I retain no rights over the code and do not claim ownership of the script used therein.
