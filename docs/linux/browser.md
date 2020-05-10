---
id: browser
title: Browser
---

## Firefox

- To set Firefox Developer Edition as `sensible-browser` on Linux:

    First, add Firefox Developer Edition to `update-alternatives`:

    ```
    sudo update-alternatives --install /usr/bin/x-www-browser x-www-browser /opt/firefox_dev/firefox/firefox 200
    ```

    (assuming the given executable path: `/opt/firefox_dev/firefox/firefox`)

    Then, set it as `sensible-browser`:

    ```
    sudo update-alternatives --config x-www-browser
    ```

- ### `about:config` settings

    - `browser.bookmarks.openInTabClosesMenu` - true -> false
    - `browser.bookmarks.showMobileBookmarks` - true -> false
    - `browser.tabs.loadBookmarksInTabs` - false -> true
    - `browser.tabs.tabMinWidth` - 76 -> 100
    - `browser.tabs.closeTabByDblclick` - false -> true
    - `browser.tabs.closeWindowWithLastTab` - true -> false
    - `geo.enabled` - true -> false


## Useful Shortcuts
Shortcuts:
https://support.mozilla.org/en-US/kb/keyboard-shortcuts-perform-firefox-tasks-quickly

- `<C-l>` - to highlight the url bar.
- `<C-Shift-r` / `<C-F5` - reload the tab and clear the cache.
- `<Shift-t>` - get a dropdown menu of all open tabs.
- `<C-Shift-t` - undo close tab.


## Miscellaneous

- Chromium and Firefox DevTools allow you to take a fullsize screenshot of any webpage!