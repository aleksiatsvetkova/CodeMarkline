# CodeMarkline

**Branded footers for your photos.**

CodeMarkline is an offline-capable Android photo editor for adding branded footers with logos, text, and reusable styles. Start with a template, customize your branding, and save or share a single photo or a batch. Photo editing and export run on your device.

## Install CodeMarkline

Open the [GitHub releases page](https://github.com/aleksiatsvetkova/CodeMarkline/releases), choose the newest release, and download its APK from **Assets**. Current alpha builds are marked as prereleases. Open the downloaded file and follow Android's installation prompts. If asked, allow the app opening the APK to install apps from that source; you can revoke that permission afterward.

- **Requirements:** Android 10 or later.
- **Note:** CodeMarkline is currently in alpha. Features may be incomplete, and bugs or unexpected behavior may occur.

## Make your photos look like a set

- **Your branding:** Add logo layers and multiline text. Customize fonts, colors, size, placement, and opacity, or import your own logos and fonts.
- **Reusable styles:** Start with a built-in template and save your own presets for future photos.
- **Photo adjustments:** Crop, rotate, flip, and straighten before exporting.
- **Precise placement:** Move text and logos in the preview, with optional alignment guides and snapping. Undo and redo let you revisit edits.
- **Batch export:** Apply a consistent style to a batch of up to 100 photos, then export the current photo or the whole batch.
- **Flexible output:** Save to your gallery or share with another app. Choose JPEG, PNG, or WebP, with size and quality options where applicable.

### Three ways to finish a photo

| Layout | Look |
| --- | --- |
| **Overlay** | Branding over the photo, with an optional bottom gradient. |
| **Bar** | A solid footer beneath the photo. |
| **Frame** | A border around the photo with a footer below it. |

## Create your first export

1. Open CodeMarkline and tap **Select photos**. Choose the photos you want to edit using Android's photo picker.
2. Choose a style in **Templates**. Use **Layout**, **Text**, and **Logos** to customize it.
3. Tap a logo or the text in the preview to select it. Drag to move it; use **Position** for size, opacity, and placement controls. Pinch to zoom for a closer look.
4. Use **Crop** if a photo needs cropping, rotation, flipping, or straightening. Drag a corner or edge to crop, drag the photo to reposition it, and pinch to zoom. Twist with two fingers or use the dial to straighten, and double-tap to zoom in or show the whole photo again. Tap **Done** to keep those adjustments.
5. Open **Export**, choose the format, size, and photos to include, then tap **Save to gallery** or **Share**.

To reuse your style, choose **Save as preset** in Templates. Your original photos are not overwritten by editing or export.

### Placement tips

- In **Position**, use the previous and next arrows beside the element name to cycle through text and logos, including hidden or off-canvas elements.
- Drag a selected element to move it. Use the Size slider to resize it, the nudge arrows for small adjustments, or tap the X/Y readouts to enter a position.
- Turn on **Show guides** for visual alignment targets and **Snap to guides** to help align elements.
- Pinch to zoom; double-tap the preview to return to automatic framing.

## Keep CodeMarkline up to date

CodeMarkline checks GitHub once each time the app starts a new session, including published prereleases. You can also open **About → Check for updates**.

Release notes are displayed with Markdown formatting, including headings, emphasis, lists, code blocks, tables, strikethrough, and task lists. Tap a web link to open it in your browser. Embedded images are not loaded, and links to files or other app-specific actions are ignored.

When an update is available, review its release notes and choose **Download update**. Keep the app open while downloading; progress is shown in the update dialog. After verification, choose **Install update**. If Android asks, allow CodeMarkline to install apps from this source, then confirm the update in Android's installer. You can revoke that permission afterward.

An in-place update keeps your workspace, presets, and imported content without uninstalling the app. You can decline or cancel before installation without changing the installed app. If verification fails or the APK has an incompatible signing identity, it will not be installed; do not uninstall the app to bypass that warning. Network, storage, and device-policy restrictions can prevent an update; editing and export remain available.

## Privacy and offline use

- Photo editing and export happen entirely on your device. CodeMarkline does not upload photos for processing or require an internet connection for local editing and export.
- Editing and export work offline with photos already available on your device. Cloud-only photos offered by the system picker may need connectivity before they can be used.
- Automatic and manual update checks contact GitHub. Downloading an update also contacts GitHub's servers, which receive connection information such as your IP address. Update downloads and installation require your approval.
- Exported images do not retain the source photo's EXIF metadata, such as embedded GPS coordinates. Visible details in a photo can still reveal personal information.
- Choosing **Share** passes your exported images to the app you select. That app's permissions and privacy practices apply.
- Android backup or device-transfer services act according to your device settings and their own privacy practices.

For help choosing photos, see [Android's photo picker guide](https://support.google.com/android/answer/13356023?hl=en). Picker appearance and available options can vary by device and Android version.

## Feedback

Use this repository's [Issues](https://github.com/aleksiatsvetkova/CodeMarkline/issues) tab to report a bug or suggest a feature. For bugs, include your Android version, CodeMarkline version, steps to reproduce, and what you expected versus what happened.

Issues are public. Do not include private photos, personal information, or other sensitive material. Use a non-sensitive example if an image is needed to explain a problem.

## Ownership and permitted use

© 2026 aleksiatsvetkova. All rights reserved.

CodeMarkline is proprietary, not open-source software. Ordinary app use, photo editing, and saving or sharing your exports are permitted within the applicable terms and the rights you hold in the content. Modification of owner-controlled app material is reserved to aleksiatsvetkova; no general permission for redistribution, reverse engineering, or unpermitted AI or automated extraction is granted. Applicable mandatory legal rights remain unaffected.

You retain your rights in your own photos. Third-party logos and trademarks belong to their respective rights holders; inclusion in the app does not grant permission to use them or imply endorsement. Use only content you have the right to use. Bundled fonts are licensed under the SIL Open Font License; applicable third-party licenses remain in effect.

See [Copyright & Ownership Notice](COPYRIGHT.md) and [Restricted Use Policy](POLICY.md) for the full terms. This README is an end-user overview, not a separate license grant.
