<p align="center"><img src="assets/bildtitel-icon.png" width="104" height="104" alt="Bildtitel icon"></p>
<h1 align="center">Bildtitel</h1>
<p align="center"><strong>Images. Well named.</strong><br>A native Mac app that turns screenshot content into meaningful filenames.</p>
<p align="center">
  <a href="https://github.com/Nature0ne/Bildtitel/releases/download/v1.3.0/Bildtitel-1.3.0-macOS-AppleSilicon.dmg"><strong>↓ Download Bildtitel 1.3.0</strong></a> ·
  <a href="https://github.com/Nature0ne/Bildtitel/releases/download/v1.3.0/Bildtitel-1.3.0-macOS-AppleSilicon.zip">ZIP</a> ·
  <a href="README.md">Deutsch</a> · <a href="README.nl.md">Nederlands</a>
</p>
<p align="center">macOS 26+ · Apple Silicon · Deutsch · English · Nederlands · Free download</p>

![Bildtitel in dark mode with a name preview](assets/bildtitel-dark.png)

## Give your screenshots names you can find again

Bildtitel recognizes image content and suggests a suitable filename. Review the suggestion, edit the title if needed and rename the file. It can also monitor your screenshot folder and rename new screenshots automatically.

Version 1.3.0 adds English and Dutch, a saved Inbox, naming profiles and more control over working with several images at once.

| Feature | What it does for you |
|---|---|
| **On-device AI** | Apple Intelligence creates titles locally; text recognition is available when AI cannot be used. |
| **Preview before renaming** | See the image, original name, editable title and complete filename together. |
| **An Inbox that stays** | Open suggestions and edited titles are saved locally and restored at the next launch. |
| **Naming profiles** | Save and reuse name length, style, date format and the AI setting for different tasks. |
| **Selected batches** | Review visible images or a selection, edit the proposed names and see the results afterward. |
| **Folder monitoring with clear status** | See preparation, active monitoring, pauses and errors, the last successful check, and automatic retries. |
| **Searchable history** | Search original or new names and filter by period, method or status. |
| **Images from the clipboard** | Save a copied image as a new PNG and get a name suggestion. |
| **Duplicate detection** | Mark images whose file content matches another Inbox image or a known file; nothing is deleted automatically. |
| **Your date format** | Add a date prefix or suffix, for example `yy-MM-dd` → `26-11-12`. |
| **Light, dark or system appearance** | Choose your appearance, with clearer hints and layouts that allow longer text. |
| **Menu-bar-only mode** | Hide the Dock icon and reopen Bildtitel from its status icon. |
| **Updates in the app** | Check for new versions or opt into background downloads and installation on quit. |

<details>
<summary><strong>See the light appearance</strong></summary>

![Bildtitel in light mode](assets/bildtitel-light.png)

</details>

## Install

Download the **[DMG for Apple Silicon](https://github.com/Nature0ne/Bildtitel/releases/download/v1.3.0/Bildtitel-1.3.0-macOS-AppleSilicon.dmg)**, open it and drag **Bildtitel.app** into **Applications**. A **[ZIP download](https://github.com/Nature0ne/Bildtitel/releases/download/v1.3.0/Bildtitel-1.3.0-macOS-AppleSilicon.zip)** is also available. Release downloads are Developer ID signed and notarized by Apple; SHA-256 checksums are included in the [release](https://github.com/Nature0ne/Bildtitel/releases/tag/v1.3.0).

**Updating an older version?** From 1.2.0, choose **Check for updates…**. Install this release manually if you are on 1.1.0. Finish open suggestions in those older versions before updating: they do not yet save the Inbox. Existing preferences and rename history are retained; Inbox persistence starts with 1.3.0.

## Get started

### Rename one image or a selection

Drop files into the window or choose **Add images**. Check the suggestion, edit the title and click **Rename**. You can undo the change in **History**. Existing files are not overwritten.

For several images, select entries in the Inbox and choose **Review selection**. With no selection, use **Review visible images**. The search filter and selection define the scope. The batch preview shows the proposed names before you start; the result report lists successful and failed changes. Failed suggestions remain in the Inbox.

### Monitor new screenshots

Choose the folder where macOS saves your screenshots under **Settings → Screenshot folder**. Enable **Rename new screenshots immediately** if you want automatic renaming. Files already present when monitoring starts are skipped; use **Prepare folder** for older images.

Monitoring distinguishes preparation, active monitoring, pauses and errors. It shows the last successful check and offers **Check now**. Temporary access errors trigger retries. Individual unreadable files are skipped and counted in a status hint.

### Keep suggestions and reuse naming profiles

The Inbox and edited suggestions are saved locally, so you can continue after a restart. Restored suggestions are not renamed automatically.

Create profiles under **Settings → Naming profiles**, for example for work, personal images or receipts. You can apply, update and delete them. Your own profile names and edited titles are not translated when the app language changes.

Under **Names**, choose **Date prefix** or **Date suffix**. `yy-MM-dd` gives **26-11-12**, while `dd.MM.yyyy` gives **12.11.2026**. The preview updates immediately and uses your Mac’s local time zone.

### Clipboard images and duplicates

Choose **Add image from clipboard**, or press **⇧⌘V**, to import a copied image. You choose where the new PNG file will be saved. Existing files are not overwritten.

Files with identical content are marked as duplicates. Show the original in Finder or choose **Analyze anyway** to analyze the image again deliberately. Nothing is deleted automatically; marked duplicates are not automatically analyzed or renamed again.

### History, language and appearance

Search History by original or new filename, then filter by period, AI/text recognition or processing status.

Bildtitel follows your macOS language preferences and supports **German, English and Dutch**. You can choose an app-specific language in **System Settings → General → Language & Region → Applications**. The app language is also taken into account when requesting AI titles; your own titles and filenames remain unchanged.

Choose **System**, **Light** or **Dark** under **Appearance**. Turn off **Show in Dock** to keep Bildtitel in the menu bar only. Closing the window leaves the app running; reopen it from the status icon.

### Updates

Choose **Check for updates…** from the app menu, status menu or settings. Automatic checking is enabled by default. Opt into **Settings → Updates → Automatically install updates** to download new versions in the background and install them when you quit. A restart is never forced.

Updates use [Sparkle](https://sparkle-project.org/). The feed and downloads are signature-verified. Update requests connect to GitHub without sending images, recognized text or diagnostic logs. System profiling is turned off.

## Apple Intelligence and privacy

AI naming requires Apple Intelligence to be enabled and its model to be available on your Mac. On macOS 27+, the local model receives the image as well as extracted text. On macOS 26, naming uses extracted text and image labels.

If AI is unavailable or cannot name an image, Bildtitel uses local text recognition. **The preview and History show which method was actually used.** A fallback after an AI error is identified as text recognition.

No Bildtitel account, API key or subscription. Images are not uploaded to an external AI service. Preferences, naming profiles, Inbox suggestions and recognized text, rename history and a bounded technical diagnostic log are stored locally on your Mac.

## Requirements

- **Apple Silicon — M1 or later.** This download does not include an Intel build.
- **macOS 26 or later.**
- For AI titles: **Apple Intelligence enabled and available**.
- Interface: **German, English and Dutch**, selected automatically from macOS language preferences.

67 automated tests passed. The English and Dutch interfaces, plus manual and automatic updates with edited suggestions in the Inbox, were checked on macOS 27.2.1. macOS 26 has not been separately field-tested.

## Questions or a problem?

Open an [Issue](https://github.com/Nature0ne/Bildtitel/issues) with your macOS version and a short description.

If new screenshots do not appear in the Inbox, keep Bildtitel open, create a new screenshot and choose **Settings → Diagnostics → Export diagnostics…**. You can also export from the status menu. The JSON file contains technical states, timestamps, counts and error codes; it excludes images, recognized image text, filenames, folder paths and stored access grants. Nothing is uploaded automatically.

Version 1.3.0 improves monitoring and its feedback. The cause of the previously reported failure on another Mac has not yet been confirmed by diagnostics from that device.

This repository distributes the finished app, product previews, release notes and the signed update feed.

---

Developed by [Nature0ne](https://github.com/Nature0ne).
