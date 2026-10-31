# Slayer Macro

A Windows app that looks after your [Idle Slayer](https://store.steampowered.com/app/1353300/Idle_Slayer/) minions while you're away. When something is ready it opens the game, does the work, and closes it again.

**[Download SlayerMacro.exe](https://github.com/hacker1269/slayer-macro-releases/releases/latest/download/SlayerMacro.exe)**

Open it once and it installs itself: no admin rights and no setup steps. After that, search for Slayer Macro in Windows to open it, like any other app. When a new version is out, one click closes the app for a moment and reopens it on the update.

## What it does

- **Claims and sends your minions** as soon as they're back, using the timers from your game's save
- **Prestiges minions** when they reach max level, with a toggle for each minion
- **Collects silver boxes** and doubles offline earnings
- **Uses the daily skip** at the moment it saves the most mission time
- **Plans your ultra ascension**: pick a date and it gets every minion to max level by then, prestiging on the way for the most divinity points. You ultra ascend yourself
- **Shows your progress** on one page: timers, coins, slayer points, ultra slayer points, divinity points and silver boxes
- **Sends Discord reports** after each session and every hour, if you want them

It only runs while you're away. Move the mouse or press a key and it stops straight away, so it won't fight you for the PC.

## What you need

- Windows 10 or 11
- Idle Slayer on Steam
- A 2560×1440 or 1920×1080 monitor

If something in your game's setup would cause problems, the app tells you what's wrong and how to fix it. It never changes your settings, and it only reads your save file.

## Getting started

1. Download `SlayerMacro.exe`.
2. Open it. If Windows warns you about it, see below. It installs itself, removes the download and opens.
3. Press **Start**.
4. Press **I'm leaving** when you step away, or just leave: it starts once you've been idle for the time set in Settings.

The app lives in the system tray while it runs. Your settings and logs are kept in `%LOCALAPPDATA%\Slayer Macro`, so they stay put when you update. To remove the app, use **Installed apps** in Windows Settings.

## If Windows blocks it

The exe isn't code signed, so Windows Smart App Control or SmartScreen can flag it, especially right after a new version comes out. That can happen again after an update. Trying again a minute later has often worked.

## Good to know

- This is a fan-made tool, not made by or connected to the developers of Idle Slayer. Use it at your own risk.
- The Armory isn't counted yet, so **Divinity points left** will read too high if you've put points into it.
- If you also play on your phone, the app can only see that progress once the game has opened on your PC. It opens the game now and then to catch up.

## Problems?

[Open an issue](https://github.com/hacker1269/slayer-macro-releases/issues) and say what happened. It helps to include the end of the log, from the app's **Log** page.
