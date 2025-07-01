

## 🎮 Your Core Keybinds (Re-Reminder)

| Action                 | Keybind            |
| ---------------------- | ------------------ |
| Launch Terminal        | `Ctrl+Shift+Space` |
| App Launcher/Search    | `Ctrl+Space`       |
| New Tab (Browser/Term) | `Ctrl+T`           |
| New Terminal Window    | `Ctrl+N`           |

These are clean. Now let’s expand:

---

## 🧠 Sensible Dev Mapping Suggestions (Based on Your Layout)

| Action                     | Suggested Keybind                  | Why It Works / Notes                         |                               |
| -------------------------- | ---------------------------------- | -------------------------------------------- | ----------------------------- |
| Close Tab/Pane             | `Ctrl+W`                           | Consistent across browsers, VSCode, etc.     |                               |
| Switch Tabs (L/R)          | `Ctrl+PageUp/PageDown`             | Standard in VSCode, browsers, tmux, etc.     |                               |
| Split Pane (Vert/Horiz)    | \`Ctrl+Alt+                        | `/`Ctrl+Alt+-\`                              | Terminal multiplexers or IDEs |
| Focus Terminal Pane (L/R)  | `Ctrl+Alt+←/→`                     | Works well in tmux / IDEs / i3               |                               |
| Kill Current Terminal/Pane | `Ctrl+Shift+W`                     | Mirrors browser tab kill, just with Shift    |                               |
| App-Specific Dev Launcher  | `Ctrl+Shift+Space` (already yours) | Keep using this for full terminal launcher   |                               |
| Clipboard Manager          | `Ctrl+Shift+V`                     | Make consistent with paste history or CopyQ  |                               |
| DevTools (Inspect Element) | `Ctrl+Shift+I`                     | Browser + Electron apps universal debug bind |                               |
| Emoji Picker / RofiMoji    | `Ctrl+.`                           | Non-conflicting, meme/utility use 🥲         |                               |
| Lock Screen                | `Ctrl+Alt+L`                       | Common Linux standard, safe to keep          |                               |
| Quick File Explorer        | `Ctrl+E` or `Ctrl+Shift+E`         | Easy left-hand combo                         |                               |
| Global Scratchpad/Note App | `Ctrl+Alt+N`                       | Good muscle memory, near `Ctrl+N`            |                               |

---

## 🧱 Pro Mapping Layers (Optional but Pro AF)

| Tool                                   | Suggestion                     | Bind Logic                     |
| -------------------------------------- | ------------------------------ | ------------------------------ |
| **tmux**                               | Prefix `Ctrl+A`                | (or `Ctrl+G` if A is taken)    |
| **bspwm/i3**                           | Move/Resize with `Super+Arrow` | Works well with stacked tiling |
| **Rofi/Launcher**                      | `Ctrl+Space`                   | You already use this 🧠🔥      |
| **Window Switcher**                    | `Alt+Tab`                      | Keep universal standard        |
| **Global HUD (like Ulauncher/Albert)** | `Ctrl+Alt+Space`               | Emergency brain search 🧠      |

---

## 🧬 Additional Binding Layers (If You Want More Sauce)

| Layer                  | Tool                    | Bind Suggestion     | Notes                            |
| ---------------------- | ----------------------- | ------------------- | -------------------------------- |
| Notification Center    | Dunst                   | `Ctrl+Shift+M`      | Dismiss or show center           |
| Bluetooth Toggle       | Custom Script           | `Ctrl+Alt+B`        | Easy toggle                      |
| WiFi Toggle            | Custom Script           | `Ctrl+Alt+W`        | Panic button for distractions 😤 |
| Screenshot             | Flameshot               | `Ctrl+Shift+S`      | Already standard on Windows      |
| Quick Scratch Terminal | Dropdown like `yakuake` | `Ctrl+\`` or `F12\` | Quake-style pull-down terminal   |

---

## 🔧 Implementation Tips

* **Linux**: Use `sxhkd`, `xbindkeys`, or DE built-in shortcut managers (like GNOME’s or KDE’s).
* **Window Manager setups** (i3, bspwm, etc.): define these in `.config/i3/config` or `sxhkdrc`.
* **Windows**: Use [AutoHotKey](https://www.autohotkey.com/) or [PowerToys](https://github.com/microsoft/PowerToys) for easy global mapping.
