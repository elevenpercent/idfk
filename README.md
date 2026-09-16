# about:blank launcher

A single static HTML page. Enter a URL, click Launch, and a new window opens
whose address bar reports `about:blank` while an iframe inside it loads the
real page. Press `Ctrl+Shift+L` in the launched window to change the URL live.

Open `index.html` directly, or serve it via GitHub Pages.

Note: many sites (Google, YouTube, GitHub, banks, etc.) send headers that
refuse to be framed, so they won't render inside the iframe — this is a
browser-side display trick, not a network proxy.
