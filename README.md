# Asana Inbox

A small Mac app that lives in your menu bar and shows only the places where
someone @mentioned you in Asana. No task updates, no noise. Reply, react, star
and flag right from the menu bar, or jump straight to the task in Asana.

Works on macOS 13 (Ventura) or later, on Apple Silicon and Intel Macs.

## Download

**[Download Asana Inbox](https://github.com/designbycosmic/asana-inbox-releases/releases/latest/download/Asana-Inbox-mac.zip)**

That link always gets the newest version. What changed in each version is on
the [Releases page](https://github.com/designbycosmic/asana-inbox-releases/releases).

## Install

It takes about five minutes, and you only do this once. The app isn't signed
with an Apple developer certificate, so macOS asks you to approve it the first
time. After that it updates itself without asking.

1. **Download** the zip with the link above.
2. **Unzip it.** Double-click `Asana-Inbox-mac.zip` in your Downloads folder
   (Safari may have done this for you). You get a folder called **Asana
   Inbox** with the app and **Install.command** inside. Keep them together.
3. **Double-click Install.command.** macOS says it was not opened because
   Apple could not check it. Click **Done** (not "Move to Trash").
4. **Approve it.** Open the Apple menu > **System Settings** > **Privacy &
   Security**. Scroll down to the Security section, where it says
   "Install.command" was blocked. Click **Open Anyway**, then **Open Anyway**
   again, and enter your Mac password or use Touch ID.

A Terminal window opens and installs the app into your Applications folder,
then opens it. If macOS asks whether Terminal can access your Downloads
folder, click **Allow**. When it says **Done**, you can close the window.

On macOS 14 (Sonoma) or earlier you can skip step 4: Control-click
Install.command, choose **Open**, then click **Open** again.

## Sign in

1. Look for the **@** icon at the top right of your screen, in the menu bar.
   The app has no Dock icon.
2. Click it, then click **Sign in with Asana**.
3. Your browser opens Asana. Check it shows your account and click **Allow**.
   If the browser doesn't come back to the app, click **Browser didn't come
   back? Get a code instead** in the app and paste the code Asana shows you.

Your mentions from the last week show up within a minute or so.

## Updates

The app checks for new versions once a day. When there is one, a bar at the
top of the panel says so. Click **Install and relaunch**: the app downloads
the new version, swaps itself out and opens again, with no macOS prompts. You
stay signed in and keep your stars, flags and read marks.

If the app can't update itself (for example because it isn't in your
Applications folder), it downloads the new zip in your browser instead. Unzip
it and run Install.command again, the same way as the first time.

## Uninstall

1. Right-click the **@** in the menu bar and choose **Quit Asana Inbox**.
2. Drag **Asana Inbox** from your Applications folder to the Trash.
3. To remove your settings too, in Finder choose **Go > Go to Folder**, paste
   `~/Library/Application Support/Asana Inbox`, and move that folder to the
   Trash.
4. If you like, remove the app's access in Asana: your profile settings, then
   the **Apps** tab.
