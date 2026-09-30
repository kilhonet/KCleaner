# KCleaner

**A free Windows PC cleaner that closes every unnecessary program with one click, leaving only what Windows really needs — and cleans up autorun items, leftover junk files and force-installed security programs in the same place.**

English · [한국어](README.ko.md) · [简体中文](README.zh-CN.md) · [日本語](README.ja.md) · [Español](README.es.md) · [Português (Brasil)](README.pt-BR.md) · [Français](README.fr.md)

> This document is a translation. If anything differs, the [Korean version](README.ko.md) is authoritative.

![Platform](https://img.shields.io/badge/platform-Windows%2010%20%2F%2011%20(64--bit)-0078D4)
![License](https://img.shields.io/badge/license-Freeware-brightgreen)
![Version](https://img.shields.io/badge/version-4.0.0-blue)
[![Download](https://img.shields.io/badge/download-kilho.net-orange)](https://down.kilho.net/kcleaner?lang=en)

![KCleaner screen](images/kcleaner-en.webp)

## Overview

Leave your PC on for a while and lots of programs end up running in the background — messengers, update helpers, programs you used and never closed, even security programs that banking sites made you install. Hunting them down one by one is tedious.

With one click on **Clean**, KCleaner closes everything except the programs Windows needs to run, then frees up the remaining memory. Essential drivers such as graphics and sound, and trusted antivirus software, are left running; programs disguised with the same names as Windows system programs are closed. Programs are only closed, never uninstalled.

Three more cleanup tools come along as tabs:

- **Startup** — turn off programs, scheduled tasks and services that start with Windows, without deleting them.
- **Cleanup** — pick and delete junk such as caches and temporary files left by installed apps.
- **Bundle** — find and remove security programs that banking and government sites required you to install.

## Features

- **Close everything at once** — One button closes every program except the essential ones.
- **Safe rules** — Essential Windows programs, graphics and sound drivers, and trusted antivirus software are kept. Fake system programs that only imitate Windows names are closed.
- **Memory cleanup** — Once programs are closed, the remaining memory is freed.
- **Exception list** — Programs that must always keep running can be excluded from closing.
- **Results** — When cleaning finishes, a results page opens showing the programs that were closed and how memory changed.
- **Startup management** — Turn autorun items from startup folders, the registry, Task Scheduler and services on and off from a single list.
- **Junk file cleanup** — Analyze and delete caches, temporary files and logs only for apps installed on this PC. Personal records such as bookmarks, passwords and browsing history are unchecked by default.
- **Remove force-installed programs** — Lists banking and government security programs and runs their uninstaller with one button.
- **Tray icon** — The installed version waits in the notification area after you sign in, and opens KCleaner with a click.
- **Dark mode** — Colors follow the Windows app mode (light · dark).
- **9 languages** — Korean · English · Japanese · Chinese · Russian · Italian · French · Spanish · Arabic.

## Download / Installation

| Type | Link |
|---|---|
| Installer | [Download](https://down.kilho.net/kcleaner?lang=en) |
| Portable (ZIP) | [Download](https://down.kilho.net/kcleaner?lang=en&nosetup) |

The installer starts KCleaner as soon as installation finishes and adds a tray icon to the notification area. For the portable version, unzip it and run `KCleaner.exe`. Both versions clean the same way; only the installed version has the tray icon.

Closing programs and changing autorun items require administrator rights, so Windows shows an administrator prompt when you run it. Click **Yes**.

## Usage

### Getting started

1. If you have open documents or unfinished work, save it first. Every non-essential program, including browsers and messengers, will be closed.
2. Run KCleaner and click **Yes** at the administrator prompt.
3. On the **Home** screen, click **Clean**.
4. A progress spinner turns where the button was while unnecessary programs are closed and memory is cleaned up.
5. When it's done, a results page opens in your browser and the KCleaner window closes by itself.

### Screen layout

| Element | Purpose |
|---|---|
| **Home** | The first screen, with the **Clean** button |
| **Startup** | Turn items that start with Windows on and off |
| **Cleanup** | Analyze and delete junk files from installed apps |
| **Bundle** | Remove banking and government security programs |
| KILHO.net logo | Opens the KCleaner web page |

Each tab loads its list the first time you open it. If you only use **Clean**, you never need to open the other tabs.

**Startup**

| Element | Purpose |
|---|---|
| **Program** column | Program icon and name (the product name, when there is one) |
| **Source** column | Where the item is registered — **Startup** · **Registry** · **Task** · **Service** |
| Greyed-out row | An item that is disabled |
| **All Programs** | When checked, shows everything, including disabled items |
| **Disable** / **Enable** | Turns the selected item off or on |
| Right-click menu | **Delete** (disabled items only) · **Save List** |

**Cleanup**

| Element | Purpose |
|---|---|
| Category row | **Windows** · browser names · **Internet** · **Multimedia** · **Utilities** · **Applications** · **Games** · **Other**. Click to expand or collapse |
| Item row | One kind of junk that can be deleted. Only checked items are analyzed and cleaned |
| Exclamation mark | An item that needs care before deleting. Hover over it to see a note |
| **Size** column | How much can be deleted, after **Analyze** |
| Text at the bottom | Number of installed apps, progress, and analysis or cleanup results |
| **Analyze** / **Clean** | Finds what can be deleted and shows its size / deletes what was analyzed |
| Right-click menu | **Select all** · **Select none** · **Restore defaults** |

**Bundle**

| Element | Purpose |
|---|---|
| **Program** column | Banking and government security programs installed on this PC |
| **Source** column | The publisher (**Unknown** if there is no information) |
| **Uninstall** | Runs the uninstaller of the selected program |

### How to…

**Clean up a slow PC in one go**
Just click **Clean** on the **Home** screen. Programs running in the background are closed together and memory is freed. Programs are only closed, not deleted, so you can start any you need again and use them as usual.

**Before you click Clean**
Non-essential programs — browsers, messengers, document editors and so on — are closed even while they're open. Save any unsaved work first. Windows Explorer and the desktop, graphics and sound drivers, and trusted antivirus software stay running.

**Keep certain programs running (exception list)**
With the installed version, right-click the KCleaner icon in the notification area → **WhiteList**. Notepad opens; write the programs that should not be closed, one per line, and save.

- `program.exe*` — the program whose executable name matches exactly (e.g. `editplus.exe*`)
- Without `*` — every program whose path contains that text (e.g. `\EditPlus\` covers all programs in that folder)

From the next time you click **Clean**, the programs you listed are not closed. With the portable version, create `NoClean.txt` next to `KCleaner.exe` and write it the same way.

**Check the results**
When cleaning finishes, a results page opens in your browser showing the programs that were closed and memory before and after. The KCleaner window closes by itself once its work is done.

**Open it right from the tray icon**
With the installed version, the KCleaner icon appears in the notification area shortly after you sign in. Left-click it to open KCleaner; if it's already open, its window comes to the front. The right-click menu has **KCleaner** · **WhiteList** · **About** · **Quit**. **Quit** removes the icon until your next sign-in.

**Turn off programs that start with Windows**
On the **Startup** tab, click the program and click **Disable**. The item is turned off, not deleted — it simply stops starting with Windows from the next boot, and the program itself works as before. The row stays in place, greyed out, so you can switch it straight back with **Enable**.

**Turn a disabled item back on**
On the **Startup** tab, check **All Programs** and items you disabled earlier appear as greyed-out rows. Click the row and click **Enable**; it runs again from the next boot.

**Turn off update tasks and services**
Rows whose **Source** is **Task** run automatically at set times; **Service** rows are background services that start with Windows. **Disable** stops a task from running even when its time comes, and keeps a service from starting at boot or when another program calls it. It's best to check which program a service belongs to before turning it off.

**You don't know what a Startup item is**
Double-click the row and your browser opens with information about that item.

**Startup entries left behind by an uninstalled program**
First switch the row to **Disable**, then right-click → **Delete** and click **Yes** to confirm. Deleted items cannot be restored, so only delete what you're sure you don't need. Deleting a service shows the notice "A service that was running is fully removed after a restart" — restart the PC once and it's gone for good.

**Keep a copy of the startup list**
On the **Startup** tab, right-click → **Save List** to save every autorun item, including the essential Windows items that are hidden from the list, to a text file. Services and tasks Windows needs are hidden from the start so you can't turn them off by mistake, and they stay hidden even with **All Programs** checked.

**Win back disk space from junk files**
The first time you open the **Cleanup** tab, KCleaner finds the apps installed on this PC, reports them as **{n} installed apps**, and shows cleanup items only for those apps, grouped by category. Leave the default checks as they are and click **Analyze** to see which files would be deleted and how much space that is; click **Clean** to delete what was analyzed. **Analyze** deletes nothing, so you can use it just to see how much you could free up.

**Choose what to delete yourself**
Click a category row to expand it and see its items; click an item row to toggle its check. The checkbox on a category row checks or unchecks the whole category at once, and turns grey when only some items are checked. Your changes are remembered and used the next time you open the tab. To go back to the original state, right-click the list → **Restore defaults**.

**You also want to delete browsing history or recent file lists**
Records you created — bookmarks, favorites, passwords, web browsing history, chat history — are unchecked by default so they aren't deleted by accident. For apps that mix caches with recent file lists, there is a separate **… · Usage history** item. If you want those records deleted too, check that item yourself.

**Clean can't be clicked**
**Clean** is enabled only after every checked item has been **Analyze**d and there is something to delete. If you checked new items after analyzing, or just finished cleaning, click **Analyze** once more.

**Items with an exclamation mark**
These items have something to know before deleting. Hover over the mark to read the note, and if any such item is checked, you're asked once more when you click **Clean**.

**Your browser is open**
Files currently in use are skipped. To clear more of the browser cache, close the browser before cleaning, or click **Clean** on the **Home** screen first and then clean up.

**Are my own files safe?**
The Documents, Desktop, Pictures, Videos, Music and Downloads folders, as well as hidden and system files, are never analyzed or cleaned. When you're online, the cleanup list is automatically replaced with the latest reviewed version.

**Remove security programs a banking site installed**
Open the **Bundle** tab to see only the banking and government security programs installed on this PC — keyboard security, digital certificate tools, firewalls and the like. Select one and click **Uninstall**, or double-click its row, and the program's own uninstaller opens, just as with "Uninstall a program" in Control Panel. Once removal finishes, it drops off the list by itself. If there's nothing to remove, the tab shows **Nothing to uninstall**. You can always reinstall from the site when you need it again.

**Browse the lists with the keyboard**
On the **Startup** and **Bundle** tabs, use **↑** · **↓** to move between rows; **F5** reloads the list. If names are cut off, drag the border between column headers to adjust the width.

**Running it again while it's already open**
Only one KCleaner runs at a time. Running it again while the window is open doesn't start a new copy; the window that's already open comes to the front.

## Configuration

There is nothing to configure. Programs to keep running go in the **WhiteList** above, and Cleanup checks are remembered as you change them on screen. KCleaner follows these on its own:

| Item | Follows |
|---|---|
| Language | Windows region settings (English if the language isn't supported) |
| Colors | Windows app mode (light · dark) — changes apply right away, even while KCleaner is open |

## Requirements

- Windows 10 · Windows 11 (64-bit)
- Administrator rights — needed to close programs and change autorun items. A prompt appears when you run it.
- No other components need to be installed.
- The internet connection is used for new-version notices, list updates and the results page. Without a connection, cleaning still works with the built-in lists.

## Updates

KCleaner does **not** update itself. When it starts, it checks for a new version and shows a notice; clicking **[Yes]** opens the download page and closes the program. New versions are released manually after internal verification and announced on the [KCleaner page](https://kilho.net/kcleaner). See the [update policy notice](https://en.kilho.net/archives/notice/2940).

**Version history**

| Version | Date | Changes |
|---|---|---|
| 4.0.0 | 2026-10-01 | Rebuilt in Rust for greater reliability, new file cleanup feature (choose what to remove), improved startup program and service lists for easier management |
| 3.8.8 | 2026-07-15 | Faster, more reliable memory optimization, steadier desktop display across PC setups, faster runs with a streamlined cleanup process, efficient browser-focused memory management, Spanish added |
| 3.8.7 | 2026-04-15 | Clean runs reliably even when security software interferes, code signing certificate applied and signing improved |
| 3.8.6 | 2026-03-19 | More efficient memory management, internal processing optimized for faster system response, less unnecessary memory use for a smoother experience, overall performance improvements |

## License

KCleaner is **freeware**. Use it free of charge and without restriction anywhere — at work, at home, in government offices or at school — and redistribute it freely.

The Cleanup list is based on [Winapp2](https://github.com/MoscaDotTo/Winapp2) (CC BY-SA 4.0). Licenses for the components it uses are in `THIRD-PARTY-NOTICES.txt` in the installation folder.

## Links

- Website: <https://kilho.net/kcleaner>
- Forum: <https://kilho.top/forum/qna>
- X (Twitter): <https://www.twitter.com/kilhonet>

© KILHO.NET
