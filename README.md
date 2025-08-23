# Calibre AppImage
    Calibre: 8.9.0

If i fail to update the release, feel free to fork it and update the version number and you'll get the file in release section.

If running the AppImage issues the following error
```
qt.qpa.plugin: From 6.5.0, xcb-cursor0 or libxcb-cursor0 is needed to load the Qt xcb platform plugin.
qt.qpa.plugin: Could not load the Qt platform plugin "xcb" in "" even though it was found.
This application failed to start because no Qt platform plugin could be initialized. Reinstalling the application may fix this problem.
```
a library on the host system is missing.

This can be easily installed 


On Debian based systems (Debian, Ubuntu and derivates like Mint)
```sudo apt install libxcb-cursor-dev```

On Red Hat based systems (f.e. Fedora)
```sudo dnf install xcb-util-cursor*```
