# Mouse Synchronization

**Control many windows at once with a single mouse.**

Mouse Synchronization lets you pick one window as the "leader" and copies whatever
you do there — clicks, scrolling, and dragging — to as many other windows as you
like, all at the same time. It's perfect when you have several copies of the same
app open and you're tired of repeating the same action in each one.

Made by **Duck Martians** · [duckmartians.info](https://duckmartians.info)

---

## Getting started

1. Open the windows or apps you want to control (for example, several copies of the same program).
2. Open **Mouse Synchronization** (run the app).
3. Follow the 5 steps below.

That's it — no setup, no account.

---

## Use it in 5 steps

1. **Find your windows.** The left panel, **Open windows**, shows everything currently
   open. Your target windows are in there.
2. **Add them to the sync list.** Click the green **➕** next to a window (or select
   several and press **Add →**). They move to the right panel, **Sync list**.
3. **Choose the leader.** In the Sync list, click the **star ☆** next to the window you
   want to control from. It turns **gold ★** — this is now your main window.
4. **Press Start.** Click the green **Start** button (or press **Ctrl + 1**).
5. **Use your leader window.** Click, scroll, or click-and-drag inside the main window,
   and every other window in the list does the exact same thing at the same moment.

To stop, click **Stop sync** (or **Ctrl + 2**). To take a quick break without stopping,
press **Pause**.

> You need a main window chosen **and at least 2 windows** in the sync list before Start will work.

---

## What each part of the screen does

### Left panel — Open windows
A live list of every open window on your computer.
- **➕** — add this window to the sync list.
- **👁 (eye)** — bring this window to the front so you can see it.
- **Search box** — type part of a window's name to filter the list (for example, type
  a program's name to hide everything else).
- **Add all matching** — adds every window that matches your search in one click. Great
  when you have 10+ windows to add. (This button only works after you type something in the search box.)
- **Only current Desktop** — hides windows that live on your other virtual desktops.

### "Open more windows" box
Want more copies of a program?
1. Click a window in the **Open windows** list.
2. Set how many copies you want.
3. Click **Open more**.

The app finds the program behind that window and launches extra copies for you.
(Some programs only allow one copy of themselves to run — those will simply close the
extra copies. That's the program's rule, not a bug here.)

### Middle column — actions
- **Add → / ← Remove / Remove all** — move windows in and out of the sync list.
- **Refresh** — re-scan for open windows (use it if a window is missing from the list).
- **Arrange** — automatically tidy your sync windows into a neat grid. Pick which
  monitor(s) to use with the checkboxes under **Select monitor**, then click Arrange.
- **Select monitor** — tick the screens you want to arrange windows on. The **star**
  marks your "main" screen (this is just a label inside the app — it does **not** change
  your Windows settings).

### Right panel — Sync list
The windows that will follow your leader.
- **Star ★** — pick the leader (main) window. Only one can be the leader.
- **👁 (eye)** — bring that window to the front.
- **➖** — remove this window from the list.

### Bottom bar — controls
- **Start / Pause / Stop** — run, pause, or stop syncing.
- The small boxes under each button are the **keyboard shortcuts** (see below).
- **Sync by window ratio** — turn this **on** if your windows are different sizes or in
  different positions; it then matches actions by *relative* position instead of exact
  coordinates. Leave it **off** if all your windows are the same size and lined up.
- **🏠 Home button** — opens the Duck Martians website.
- **🌐 Language button** — change the app's language.

---

## Keyboard shortcuts

You can control everything without touching the buttons:

| Action | Default shortcut |
|--------|------------------|
| Start  | **Ctrl + 1** |
| Stop   | **Ctrl + 2** |
| Pause / Resume | **Alt + 1** |

**Change a shortcut:** click a shortcut box, type the keys you want (for example,
`Ctrl` in the first box and `F5` in the second), and click away. The shortcut boxes are
**locked while syncing** — stop first if you want to change them.

Your shortcuts are **remembered** the next time you open the app.

---

## The floating status badge

When syncing starts, a small badge appears in the corner of your screen:
- **Green** = syncing is running.
- **Amber** = paused.

You can **click the badge** to pause or resume — handy when your other windows are
covering the app. The badge disappears when you press Stop.

---

## Running several copies of the tool

You can open Mouse Synchronization more than once (each copy gets its own number, like
"Instance 1", "Instance 2"). Each copy has its **own** Pause shortcut (Alt + its number),
so you can pause them independently.

---

## Good to know

- **What gets copied:** left-click, right-click, middle-click, scrolling, and
  click-and-drag (hold the left button and move) — all done inside the main window.
- **Window names change on purpose:** while a window is in the sync list, the app adds a
  small number like `[1]`, `[2]` to its title so you can tell them apart. The original
  names come back when you remove them or close the app.
- **Administrator rights:** the app runs normally without them. But if a window you want
  to control is itself running "as administrator", Windows blocks a normal app from
  touching it — in that case, run Mouse Synchronization as administrator too
  (right-click the app → **Run as administrator**).

---

## Language & saved settings

- The app supports **9 languages**: English, Tiếng Việt, বাংলা, हिन्दी, Português (Brasil),
  Русский, Türkçe, اردو, and 简体中文. Click the **🌐 language button** to switch — it
  changes instantly, no restart needed.
- Your **language** and **keyboard shortcuts** are saved automatically, so the app opens
  the way you left it next time.

---

## Troubleshooting

**Start does nothing / shows a warning.**
Make sure you've picked a main window (gold star) and added at least 2 windows to the
sync list.

**A window I want isn't in the list.**
Click **Refresh**. If it's on another virtual desktop, untick **Only current Desktop**.

**The other windows don't react when I click.**
The window that's *actually* being clicked must be your leader (the one with the gold
star). Also make sure syncing is running (green badge in the corner). If your target
window runs "as administrator", run this app as administrator too.

**Windows aren't lined up the way I expect.**
If they're different sizes, turn on **Sync by window ratio**. To tidy them into a grid,
tick the monitors under **Select monitor** and click **Arrange**.

---

## About

Mouse Synchronization · by **Duck Martians**
[duckmartians.info](https://duckmartians.info)
