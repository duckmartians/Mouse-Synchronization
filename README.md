<h1 align="center">Mouse Synchronization</h1>

<p align="center"><b>Control many windows at once with a single mouse — click, scroll and drag in one leader window, and every other window in the list does exactly the same at the same moment.</b></p>

<p align="center">
  <b>English</b> ·
  <a href="README.vi.md">Tiếng Việt</a> ·
  <a href="README.bn.md">বাংলা</a> ·
  <a href="README.hi.md">हिन्दी</a> ·
  <a href="README.pt_BR.md">Português (BR)</a> ·
  <a href="README.ru.md">Русский</a> ·
  <a href="README.tr.md">Türkçe</a> ·
  <a href="README.ur.md">اردو</a> ·
  <a href="README.zh_CN.md">简体中文</a>
</p>

<p align="center">
  <a href="https://github.com/duckmartians/Mouse-Synchronization/releases/latest"><img alt="Download for Windows" src="https://img.shields.io/badge/Download-Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white"></a>
</p>

---

## Install

### Step 1 — Download

Download the latest build from **[Releases](https://github.com/duckmartians/Mouse-Synchronization/releases/latest)**:

| Your machine | Download | Notes |
|---|---|---|
| 🪟 **Windows** | [Windows (.zip)](https://github.com/duckmartians/Mouse-Synchronization/releases/latest) | The file is named `Mouse-Synchronization_v<version>.zip`. There is no macOS version. |

### Step 2 — Unzip and run

<details open>
<summary><b>🪟 On Windows</b></summary>

1. **Unzip** the downloaded `.zip` file to any folder you like (right-click → **Extract All…**). There is no installer.
2. Open the extracted folder and run **`Mouse Synchronization.exe`**.
3. If **"Windows protected your PC"** (SmartScreen) appears: click **More info** → **Run anyway**. *(The app isn't code-signed with a Microsoft certificate, so it can be flagged — it isn't a virus.)*
4. Keep the whole folder together — the `.exe` needs the files next to it. To remove the app, just delete the folder.

</details>

### Step 3 — Free, no account

Mouse Synchronization is **free**: no account, no activation key, no ads. It doesn't need administrator rights for normal windows (see [Troubleshooting](#troubleshooting) for windows that run as administrator).

---

## First run

1. **Open the windows you want to control** — for example, several copies of the same program.
2. **Run Mouse Synchronization.** The left panel, **Open windows**, lists everything currently open.
3. **Add them to the sync list.** Click the green **➕** next to a window (or select several and press **Add →**). They move to the right panel, **Sync list**. You need **at least 2 windows**.
4. **Choose the leader.** In the Sync list, click the **star ☆** next to the window you want to control from. It turns **gold ★** — this is now your main window.
5. **Press Start** (or **Ctrl + 1**).
6. **Use your leader window.** Click, scroll or click-and-drag inside it, and every other window in the list does the same at the same moment.

To stop, click **Stop sync** (or **Ctrl + 2**). To take a quick break without stopping, press **Pause** (**Alt + 1**).

---

## Features

<img width="1052" height="792" alt="Mouse Synchronization" src="https://github.com/user-attachments/assets/57c22608-46a6-4206-adde-aa456440619e" />
<img width="1919" height="1032" alt="Mouse Synchronization" src="https://github.com/user-attachments/assets/c93fee4f-a696-451e-894b-94fe3312fd58" />

- **One mouse, many windows** — left, right and middle clicks, scrolling and click-and-drag inside the leader window are sent at the same time to every window in the Sync list. Only the mouse is synced, not the keyboard.
- **Sync by window ratio** — when windows differ in size or position, actions are matched by *relative* position instead of exact coordinates.
- **Find and add windows fast** — live window list with a search box, **Add all matching** for a whole batch at once, and a filter for the current virtual desktop.
- **Arrange into a grid** — tidy your sync windows into an even grid on the monitors you pick.
- **Open more windows** — launch 1–20 extra copies of the program behind a window.
- **Custom hotkeys** — Start, Stop and Pause / Resume, remembered between sessions.
- **Floating status badge** — green while syncing, amber while paused; click it to pause or resume.
- **Run several copies of the tool** — each copy gets its own number and its own Pause hotkey.
- **9 languages** — switch instantly from the 🌐 button, no restart needed.

---

## The main window

### 🪟 Left panel — Open windows

A live list of every open window on your computer.
- **➕** — add this window to the sync list.
- **👁** — bring this window to the front so you can see it.
- **Search box** — type part of a window's name to filter the list.
- **Add all matching** — adds every window that matches your search in one click (works once you've typed something in the search box). Great when you have 10+ windows to add.
- **Only current Desktop** — hides windows that live on your other virtual desktops.

### ➕ Open more windows

Want more copies of a program? Click a window in the **Open windows** list, set the **Window count** (1–20), and click **Open more**. The app finds the program behind that window and launches extra copies. Some programs only allow one copy of themselves — they will close the extras on their own; that's the program's rule, not a bug.

### ↔️ Middle column — actions

- **Add → / ← Remove / Remove all** — move windows in and out of the sync list.
- **Refresh** — re-scan for open windows (use it if a window is missing).
- **Arrange** — tidy your sync windows into an even grid on the monitors ticked under **Select monitor**.
- **Select monitor** — tick the screens to arrange windows on. The **star** marks your "main" screen; it is only a label inside the app and does **not** change your Windows settings.

### ⭐ Right panel — Sync list

The windows that will follow your leader.
- **Star ★** — pick the leader (main) window. Only one window can be the leader.
- **👁** — bring that window to the front.
- **➖** — remove this window from the list.

While a window is in the sync list, the app adds a small number like `[1]`, `[2]` to its title so you can tell them apart. The original titles come back when you remove the window or close the app.

### ▶️ Bottom bar — controls

- **Start / Pause / Stop sync** — run, pause or stop syncing. The small boxes under each button are its keyboard shortcut.
- **Sync by window ratio** — turn it **on** if your windows are different sizes or in different positions; leave it **off** if they are all the same size and lined up.
- **🏠** — opens the Duck Martians website ([duckmartians.info](https://duckmartians.info)).
- **🌐** — change the app's language (English, Tiếng Việt, বাংলা, हिन्दी, Português (Brasil), Русский, Türkçe, اردو, 简体中文).

---

## Keyboard shortcuts

| Action | Default shortcut |
|---|---|
| Start | **Ctrl + 1** |
| Stop | **Ctrl + 2** |
| Pause / Resume | **Alt + 1** |

**Change a shortcut:** click a shortcut box, type the keys you want (for example `Ctrl` in the first box and `F5` in the second), then click away. The shortcut boxes are **locked while syncing** — stop first to change them. Your shortcuts are remembered the next time you open the app.

## Floating status badge

When syncing starts, a small badge appears in the corner of the screen: **green** = syncing, **amber** = paused. **Click the badge** to pause or resume — handy when other windows cover the app. It disappears when you press Stop.

## Running several copies of the tool

You can open Mouse Synchronization more than once. Each copy gets its own number ("Instance 1", "Instance 2"…) shown in its title and on its Pause button, and its own default Pause shortcut (**Alt + its number**), so you can pause them independently.

---

## Where your data lives

| What | Where |
|---|---|
| Language and keyboard shortcuts | `%APPDATA%\Mouse Synchronization\settings.ini` |

Nothing else is saved, and the app sends nothing anywhere — mouse actions are passed straight to windows on your own computer.

---

## Troubleshooting

**Start does nothing / shows a warning** — pick a main window (gold star ★) and add at least 2 windows to the sync list.

**A window I want isn't in the list** — click **Refresh**. If it's on another virtual desktop, untick **Only current Desktop**.

**The other windows don't react when I click** — you must act inside the leader window (gold star) while syncing is running (green badge). If a target window runs "as administrator", Windows blocks normal apps from controlling it — right-click Mouse Synchronization → **Run as administrator**.

**Windows aren't lined up the way I expect** — if they're different sizes, turn on **Sync by window ratio**. To tidy them into a grid, tick monitors under **Select monitor** and click **Arrange**.

**"Open more" opens a copy that closes right away** — that program allows only one copy of itself.

**Windows blocks it at "Windows protected your PC"** — click **More info → Run anyway**. The app isn't code-signed with a Microsoft certificate — it isn't a virus.
