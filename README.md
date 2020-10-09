


# ![](https://www.chromium.org/_/rsrc/1438879449147/config/customLogo.gif?revision=3) Chromium AppImage ![](https://www.chromium.org/_/rsrc/1438879449147/config/customLogo.gif?revision=3)


Chromium Latest (unofficial) AppImages by GitHub Actions Continuous Integration

## Get Started

[Download the latest release here](https://github.com/igorlogius/chromium-browser-appimage/releases)


### Executing
#### File Manager
Just double click the `*.AppImage` file and you are done!

> In normal cases, the above method should work, but in some rare cases
the `+x` permission missing. So, right click > Properties > Allow Execution

#### Terminal 
```bash
./Chromium-*.AppImage
```
```bash
chmod +x Chromium-*.AppImage
./Chromium-*.AppImage
```

In case, if FUSE support libraries are not installed on the host system, it is 
still possible to run the AppImage

```bash
./Chromium-*.AppImage --appimage-extract
cd squashfs-root
./AppRun
```

## License
https://chromium.googlesource.com/chromium/src/+/master/LICENSE

"GH Continuous Integration" is licensed under the MIT License. 
