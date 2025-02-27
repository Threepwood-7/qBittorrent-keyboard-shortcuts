# qBittorrent-keyboard-shortcuts
Documentation of qBittorrent keyboard shortcuts. Please note that some shortcuts are standard Windows shortcuts for any application, they are listed just for convenience of who does not know them.

## Main Window

| Shortcut | Action |
| :--- | :--- |
| `Ctrl+O` | Add Torrent File
| `Ctrl+Shift+O` | Add Torrent Link
| `Ctrl+F` or `Ctrl+E` | Filter Torrents or Filter Files (when in Content View)
| `Ctrl+N` | Torrent Creator
| `Ctrl+I` | Show Global Statistics
| `TAB` | Cycle Main Window Widgets
| `Ctrl-TAB` | Switch Between Main Window Tabs
| |
| `Alt+O` | Options
| `Alt+F` | File Menu
| `Alt+E` | Edit Menu
| `Alt+V` | View Menu
| `Alt+T` | Tools Menu
| `Alt+H` | Help Menu
| `Alt+4` | Show Execution Log
| |
| `Ctrl+L` | Lock qBittorrent
| `Ctrl+Q` | Exit qBittorrent
| `Ctrl+M` | Minimize (macOS only)

## Torrents Actions

| Shortcut | Action |
| :--- | :--- |
| `Ctrl+S` | Start
| `Ctrl+P` | Stop
| `Ctrl+M` | Force Start
| `Ctrl+R` | Recheck
| `Ctrl+A` | Select All
| `Shift+Up` or `Shift+Down` | Select More Items
| `Ctrl+Click` | Select More Items
| |
| `Ctrl++` | Increase Priority in Queue
| `Ctrl+-` | Decrease Priority in Queue
| `Ctrl+Shift++` | Top Priority in Queue
| `Ctrl+Shift+-` | Minimum Priority in Queue
| |
| `Ctrl+Shift+P` | Stop All
| `Ctrl+Shift+S` | Resume All
| |
| `Alt+G` | Show General Widget
| `Alt+C` | Show Trackers Widget
| `Alt+R` | Show Peerlist Widget
| `Alt+B` | Show HTTP Sources Widget
| `Alt+Z` | Show Content Widget
| `Alt+D` | Show Speed Widget
| | 
| `F2` | Rename Item (Torrent or its Content)
| `Shift+F10` | Open Context Menu
| `Return` | Double Click Action

## AutoHotkey
Additional actions could be added via https://www.autohotkey.com using the following clause

`#IfWinActive ahk_class Qt673QWindowIcon`

## Automation
Other ways to automate tasks are via APIs, such as https://github.com/rmartin16/qbittorrent-api that is a comprehensive implementation in Python

Good Luck
