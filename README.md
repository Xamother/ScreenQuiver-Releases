# ScreenQuiver downloads

ScreenQuiver is a portable Windows x64 utility for saving and switching monitor layouts, with global shortcuts, tray controls and recovery if a display change is not confirmed.

Download **ScreenQuiver.exe** from [Releases](https://github.com/Xamother/ScreenQuiver-Releases/releases/latest). No separate .NET installation or administrator access is required. Keep the executable in a permanent, writable folder.

After installing a version that includes the updater, open **Settings → Updates** to check for a new release. Startup checks are optional and installation always requires **Update and restart**. GitHub sign-in is not required for these public downloads.

For an initial manual update, choose **Exit** from the running app’s tray menu, replace the executable, and launch it again. Existing layouts remain in `%LOCALAPPDATA%\MonitorSwitcher`. If you change the executable’s name or location, turn **Start with Windows** off and on again.

## Rust and WinUI 3 prereleases

The Rust preview is available separately under **`rust-vX.Y.Z` prereleases** on the [Releases page](https://github.com/Xamother/ScreenQuiver-Releases/releases). It does not replace the stable C# release.

Download **ScreenQuiver-Rust-win-x64.zip** and extract the complete `ScreenQuiver-Rust` folder to a permanent, writable location. Run **ScreenQuiver.exe** inside that folder. Keep its runtime files, manifest and notices together. No separate .NET installation is needed.

Rust preview settings use `%LOCALAPPDATA%\MonitorSwitcher\RustPreview`. Exit the other version before using global shortcuts. The preview has its own startup option and updater channel. CI exercises simulated monitors; real-monitor acceptance testing is still pending.

This repository hosts downloads and update metadata. Application source is maintained privately and is not published here. No open-source license is granted for the application. Bundled third-party components retain their respective licenses, available inside the executable under **Settings → Updates → Third-party notices**, and in the release’s notices file.
