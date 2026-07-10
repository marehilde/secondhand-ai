# Viewing the site — GitHub Pages setup

These `.dc.html` pages need to be **served by a web server** to display — they don't
render when you double-click a downloaded file (that's normal for this format, not a
sign anything is missing). GitHub Pages is a free web server built into your repo, so
turning it on gives you a shareable link that renders the site properly.

---

## One-time setup (about 2 minutes)

1. Push/upload **all** the site files to your GitHub repo, in the **same folder**:
   - `index.html`  ← new redirect page (opens the site automatically)
   - `Landing.dc.html`
   - `Secondhand AI.dc.html`
   - `Research - Harm to Learning.dc.html`
   - `Research - Workslop.dc.html`
   - `Research - Persuasiveness.dc.html`
   - `Research - Opinionated AI.dc.html`
   - **`support.js`**  ← required; the pages won't render without it

2. On GitHub, open your repository and go to **Settings** (top of the repo).

3. In the left sidebar, click **Pages**.

4. Under **Build and deployment → Source**, choose **Deploy from a branch**.

5. Set the branch to **`main`** (or whatever your branch is called) and the folder to
   **`/ (root)`**, then click **Save**.

6. Wait ~1 minute, then refresh the Pages settings screen. It will show:

   > Your site is live at `https://<your-username>.github.io/<your-repo-name>/`

That link is your shareable site. Thanks to `index.html`, the base URL opens the
index page automatically — you don't need to add `Landing.dc.html` on the end.

---

## Sharing it

Just send that `https://<username>.github.io/<repo>/` link. Anyone can open it in a
browser — no login, no download, no setup on their end.

> **Note:** the pages load a couple of libraries from the internet at runtime, so the
> person viewing needs an internet connection (always true for a web link, so this is
> fine for sharing).

---

## Updating the site later

Whenever you change a page:

1. Upload the changed file(s) to the repo again (same filenames overwrite the old ones).
2. GitHub Pages redeploys automatically within a minute or two.
3. Refresh the link. If you don't see the change, do a hard refresh
   (**Ctrl+F5**) to clear the cached version.

---

## Troubleshooting

- **The link shows a blank page or "404":** give it another minute after saving —
  the first deploy can take a moment. Confirm the branch/folder in Settings → Pages
  match where your files actually live.
- **The page loads but content is missing:** `support.js` probably isn't in the same
  folder as the pages in the repo. Upload it next to the `.dc.html` files.
- **A "Read the study" / research link 404s:** check the research filenames on GitHub
  exactly match (including the spaces and the ` - `), e.g. `Research - Workslop.dc.html`.
- **You want to keep editing in the other platform:** that's unaffected — Pages is just
  for viewing. Keep editing the raw `.dc.html` files as before; re-upload to refresh the link.

---

## Reminder

Double-clicking a downloaded `.dc.html` will always look broken — that's the format,
not your files. Use the GitHub Pages link (or your editing platform) to see it render.
