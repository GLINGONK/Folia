# Folia

**Tabs, favorites and window groups for Windows File Explorer.**

Folia adds a modern tab bar and a favorites bar directly inside Windows File Explorer, in the spirit of the classic *Clover* extension. On Windows 11 it replaces the native Explorer tabs.

## Download

Get the latest installer from the **[Releases](../../releases/latest)** page: `Folia-setup-x.y.z.exe`.

- Windows 10 / Windows 11, 64-bit
- No administrator rights required to install
- Free to use — see [License](#license)

> The installer is not code-signed. Windows SmartScreen may show a warning: click **More info → Run anyway**.

## Features

### Tabs in File Explorer
- Chrome-style tab bar inside every Explorer window (replaces the native Windows 11 tabs)
- New Explorer windows open as tabs of the existing window (optional)
- Drag to reorder, middle-click to close, right-click menu (duplicate, close others, copy path…)
- Keyboard shortcuts:

| Shortcut | Action |
|---|---|
| `Ctrl+T` | New tab |
| `Ctrl+W` / `Ctrl+F4` | Close tab |
| `Ctrl+Shift+T` | Reopen closed tab |
| `Ctrl+Tab` / `Ctrl+Shift+Tab` | Next / previous tab |
| `Ctrl+PgDn` / `Ctrl+PgUp` | Next / previous tab |
| `Ctrl+1` … `Ctrl+8` | Go to tab 1…8 |
| `Ctrl+9` | Go to last tab |

### Favorites bar
- One click to open a favorite folder; `Ctrl+click` or middle-click opens it in a new tab
- Drag a folder onto the bar to add it, or click the star to add the current folder
- Groups (folders of favorites) with a drop-down menu and "open all in tabs"
- Rename, reorder and organize with a right-click

### Window groups
- Group any application window with an Explorer window: it becomes a tab
- Add a window by dragging it onto the tab bar, or via right-click → *Add a window*
- The group moves, resizes, minimizes and maximizes as one
- Hidden windows are always restored when Folia exits

### Settings (tray icon)
- Theme: automatic (follows Windows), light or dark
- Open new windows as tabs
- Show / hide the favorites bar
- Start with Windows
- Administrator mode: Folia restarts elevated to control applications running as administrator (UAC prompt)

## Uninstall

Use **Settings → Apps → Installed apps → Folia → Uninstall**. Your favorites are kept in the installation folder (`data`) unless you delete it.

## Notes

- Folia works by adding its own interface to Explorer windows; a Windows update may occasionally change Explorer's layout.
- If a window ever stays hidden, simply restart Folia: hidden windows are restored at startup.

## License

Folia is **freeware**: free to use, **selling is prohibited**. See [LICENSE](LICENSE).

© 2026 GLINGONK
