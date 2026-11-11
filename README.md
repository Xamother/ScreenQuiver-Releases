<!-- ScreenQuiver download instructions; maintained by release workflows. -->
# ScreenQuiver downloads

ScreenQuiver is a portable Windows x64 utility for saving and switching monitor layouts, with global shortcuts, tray controls and recovery if a display change is not confirmed.

## Stable C# version

**[Download ScreenQuiver.exe](https://github.com/Xamother/ScreenQuiver-Releases/releases/latest/download/ScreenQuiver.exe)**. Save it in a permanent, writable folder and run it. No separate .NET installation or administrator access is required.

From version 1.3.1, settings use `%LOCALAPPDATA%\ScreenQuiver`. Existing settings are copied from the old `MonitorSwitcher` folder on first launch, without removing the originals or overwriting settings already in the new location.

## Rust and WinUI 3 preview

For Rust 2.0.1 or newer, open its **`rust-vX.Y.Z` prerelease** on the [Releases page](https://github.com/Xamother/ScreenQuiver-Releases/releases), download **ScreenQuiver-Rust-win-x64.exe**, and run it from a permanent, writable folder. No installation, .NET or administrator access is required. You can rename the EXE.

The older Rust 2.0.0 release uses **ScreenQuiver-Rust-win-x64.zip**: extract the entire folder and run its **ScreenQuiver.exe**, keeping the runtime files together.

From Rust 2.0.1, the EXE contains the app, WinUI runtime and all third-party notices. First launch extracts them to `%LOCALAPPDATA%\ScreenQuiver\Runtime\<version>-<package-hash>`; later launches verify and reuse that cache. Settings use `%LOCALAPPDATA%\ScreenQuiver\RustPreview`, with existing preview settings copied from the old `MonitorSwitcher\RustPreview` folder.

The extra ZIP asset lets existing Rust 2.0.0 installations update automatically. New users should download the EXE. The preview has separate settings, startup registration and an updater channel from stable C#. Exit the other version before using global shortcuts. Real-monitor acceptance testing remains pending.

Before interactive features start, Rust 2.0.1 displays the application terms and the applicable Microsoft runtime terms. Choose **Agree and continue** to use the app, or **Exit**. Acceptance stays on your PC and needs no account. Unchanged terms do not prompt again after updates. All terms remain available offline under **Settings → About ScreenQuiver**.

## Updates and portability

Open **Settings → Updates** to check for releases without signing in to GitHub. Startup checks are optional, and **Update and restart** installs a newer version. For a manual update, choose **Exit** from the tray menu, replace the downloaded EXE, and run it again. If you move it, toggle **Start with Windows** off and on to refresh its path.

Portable means no installation or administrator access is needed. Settings and the runtime cache are stored in your Windows profile; copying the EXE to another PC does not copy your settings. Export/import layouts to transfer them. You can delete the runtime cache while ScreenQuiver is closed; it is recreated on the next launch.

**GitHub automatically adds “Source code (zip)” and “Source code (tar.gz)” to releases.** This repository contains documentation and community guidance, so those archives do not contain the app. Use the EXE download above. Application source is private.

No open-source license is granted for the application. Bundled components retain their own licenses. All notices are included in the EXE and available in **Settings → About ScreenQuiver → Third-party notices**; the C# release also provides a separate notices file.
