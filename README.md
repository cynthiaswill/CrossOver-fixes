# Please update to CrossOver-22.1.1
As CodeWeavers have provided an official update please use that instead.


## CrossOver-fixes


Heres a quick fix for macOS Ventura 13.3 until CodeWeaver provide a new release.

- Download the attached archive
- Open Terminal and run the following command
> xattr -drs com.apple.quarantine ~/Downloads
- extract the archive
- copy/paste these files into
> CrossOver.app/Contents/SharedSupport/CrossOver/bin
- (replace when prompted)

CrossOver should now run like normal

<br>

<br>
if your CrossOver is not version 22.1.1, ONLY replace file "wine64-preloader", not the ohter two files

# Disclaimer
While the provided fix gets CrossOver functioning again modifying CrossOver isn't supported by CodeWeavers.

CodeWeavers have imported the exact same fixes into there nightly builds and a release should land shortly.

<br>

The _only_ reason I've decided to provide a public fix is downgrading Apple Silicon systems can be rather complicated.
