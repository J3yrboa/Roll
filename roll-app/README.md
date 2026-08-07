# ROLL — put it on your home screen

Four files. Any static host works. GitHub Pages is free and takes about five minutes.

## Host it (GitHub Pages)

1. Go to github.com, make a new **public** repo called `roll`.
2. Click **Add file > Upload files**, drag in all five files (`index.html`, `manifest.json`, `sw.js`, `icon-180.png`, `icon-192.png`, `icon-512.png`), commit.
3. Repo **Settings > Pages**. Under Source pick **Deploy from a branch**, branch `main`, folder `/ (root)`. Save.
4. Wait about a minute, then open `https://YOURUSERNAME.github.io/roll/`

It has to be https for the offline caching to work, which GitHub Pages gives you for free.

## Add the icon

**iPhone:** open the link in Safari (not Chrome). Tap the share button, scroll down, tap **Add to Home Screen**. It opens fullscreen with no browser bar.

**Android:** open in Chrome, tap the three dots, tap **Add to Home screen** or **Install app**.

## About reminders

A website cannot send you a scheduled notification on iPhone, even from the home screen. Use the Reminders app or a Calendar alert for the nudge, and this for the log.

## Back up the roll

Your sessions are stored on the device, not on a server. If you clear Safari data or switch phones, they are gone. Tap **Copy roll** at the bottom every so often and paste it into a note. **Paste roll** puts it back.
