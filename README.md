# Dockee Privacy Policy

**Effective date: September 12, 2026**
**Applies to: Dockee 0.5.0**

Dockee is a Chrome extension that puts a small dock at the bottom of webpages, with quick notes, screenshots, media controls and download progress.

Dockee has no servers, no account, and no analytics. Nothing you do in Dockee is sent to us, because there is nowhere for it to be sent. Everything described below happens on your own computer unless this policy says otherwise.

## Where Dockee runs

Dockee runs on ordinary web pages served over `http` and `https`. It does not run on local
files, on `chrome://` pages, on the Chrome Web Store, or on other extensions' pages.

## What Dockee can access, and why

Dockee requests these browser permissions:

| Permission | What it is for |
| --- | --- |
| Access to `http` and `https` sites | Draw the dock on the page, read the page title and address for notes, and find audio or video that is playing |
| `storage`, `unlimitedStorage` | Keep your notes, your dock preference, and the screenshot you are currently editing, on your device |
| `downloads` | Show progress for downloads in the dock, and pause, resume, cancel or reveal them |
| `tabCapture` | Show a live picture of a video playing in another tab, when you ask for it |
| `scripting` | Place the dock on tabs that were already open when Dockee was installed or updated |
| `clipboardWrite` | Copy a note or a screenshot when you press Copy |

## Notes

A note is saved only when you press Save. Each saved note contains the page title, the page
address, the text you typed, and any text you had selected on the page when you opened the
note.

Notes are kept in the extension's local storage on your device. There is one note per page
address: saving a note for a page you have already noted replaces the previous one. Notes are
never uploaded anywhere.

Dockee does not yet have a button to delete an individual note. Until it does, you can remove
saved notes by clearing Dockee's storage from `chrome://extensions`, or by uninstalling Dockee.

## Screenshots

Screenshots are taken and edited entirely on your device. Dockee never uploads them.

While you are editing one, the working image is held in the extension's local storage together
with the address and title of the page it came from. It is deleted when you close the editor.
A screenshot leaves your device only if you choose to download it or copy it to the clipboard.

## Audio and video controls

Dockee looks for playing audio and video in your open tabs so it can show what is playing and
let you pause, skip and scrub. For each one it reads the title, the artist or site, whether it
is playing, the position and duration, the volume and mute state, and which tab it is in.

This information is held in memory for the current browser session only. It is never written to
disk and it is gone when you quit Chrome.

Dockee also registers the media keys on your keyboard (play/pause, next, previous, stop) so
they control whatever the dock is showing. Dockee receives these key presses only; it does not
monitor your keyboard otherwise.

### Live video from another tab

If a video is playing in a different tab, Dockee can show it moving inside the dock. This uses
Chrome's tab capture, and it only starts after you click the Dockee toolbar icon on the tab the
video is in. Chrome shows that tab as being captured while this is running.

What Dockee receives is a live video stream of that tab's visible area. Dockee crops it down to
the video itself and displays it in the dock. The stream is never recorded, saved or
transmitted — it exists only while the video is on screen, and it stops when you close the
dock, close the panel, or leave the tab.

## Downloads

Dockee reads your current and recent downloads to show them in the dock: the file name, the
site it came from, the size, the progress, and whether it finished, failed or was cancelled.

Dockee does not open or inspect the contents of downloaded files. Download details are held in
memory for the current browser session only.

## Images loaded from the web

To show artwork for what is playing, the dock may load an image over the network:

- artwork the page itself declares for the media it is playing
- the video's own poster image, or the page's preview image
- for YouTube, the standard thumbnail for that video, from `i.ytimg.com`
- the site's favicon, for tabs where no artwork is available

These are ordinary image requests. They tell the host serving the image your IP address and
which image was asked for, exactly as loading the page itself would. No information about you,
your notes or your browsing is attached to them. Dockee sends nothing else to anyone.

## What Dockee does not do

Dockee does not collect, store or transmit:

- personally identifiable information
- health information
- financial or payment information
- passwords or other authentication credentials
- location
- your personal communications
- your browsing history

Dockee does not sell or share user data. Dockee does not use anything it sees for advertising,
profiling, credit scoring, lending decisions, or any purpose other than the features described
above. There is no tracking and no telemetry of any kind.

## Keeping and removing your data

Everything Dockee stores stays on your device:

- **Saved notes** and your **minimised or expanded** dock preference persist until you remove them.
- **The screenshot being edited** is removed when you close the editor.
- **Media and download details** live in memory and are cleared when Chrome closes.

Uninstalling Dockee removes its stored data, according to how your browser handles extension
storage.

## Chrome Web Store Limited Use

Dockee's use of information received from Chrome APIs complies with the
[Chrome Web Store User Data Policy](https://developer.chrome.com/docs/webstore/program-policies/limited-use),
including the Limited Use requirements. Information accessed through Chrome APIs is used only
to provide the user-facing features described in this policy, and is not transferred to anyone.

## Security

Dockee is built so that as little as possible leaves your device, and in normal use nothing
does. No software can promise perfect security, and data stored by your browser is protected by
your browser and your computer.

## Changes to this policy

If Dockee gains a feature that changes how information is accessed, stored or shared, this
policy and the Chrome Web Store disclosures will be updated before that feature ships.

## Contact

Questions about this policy or about how Dockee handles data:

**contact@dockee.xyz**
