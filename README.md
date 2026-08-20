# Splendor Pizza — Landing Page

A single-page website for Splendor Pizza (Ayeduase, near KNUST campus, Kumasi), built with plain HTML/CSS — no build tools or dependencies needed beyond a Google Fonts link.

## Going live with GitHub Pages (free hosting)

1. **Create a GitHub account** at https://github.com if you don't have one.
2. **Create a new repository**
   - Click the **+** icon (top right) → **New repository**
   - Name it anything, e.g. `splendor-pizza`
   - Set it to **Public**
   - Click **Create repository**
3. **Upload the files**
   - On the new repo page, click **Add file → Upload files**
   - Drag in `index.html` from this folder
   - Click **Commit changes**
4. **Turn on GitHub Pages**
   - Go to **Settings → Pages** (left sidebar)
   - Under "Build and deployment" → **Source**, choose **Deploy from a branch**
   - Branch: **main**, Folder: **/ (root)** → **Save**
5. **Wait ~1 minute**, then refresh the Pages settings page. Your live link will appear at the top:
   ```
   https://YOUR-USERNAME.github.io/splendor-pizza/
   ```

Any time you want to update the site, edit `index.html` in the repo (or re-upload a new version) and GitHub Pages redeploys automatically within a minute or two.

## Using a custom domain (optional)
If you buy a domain, point it at this GitHub Pages site under **Settings → Pages → Custom domain**. GitHub will guide you through the DNS records to add.

## Editing the site yourself
Everything — text, colors, menu items, prices, hours — lives inside `index.html`. Colors are defined once at the top of the file under `:root` (search for `--tomato`, `--cheese`, `--crust`) so you can restyle the whole site by changing a few lines.

## What's included / what to double-check before publishing
- Menu prices: only "All Season Pizza" (GH₵100) had a confirmed price in the source data — other listed items say "See menu for price." Fill in real prices before going live.
- Hours: only the closing time (11 PM) was confirmed, so the page shows one general line rather than a full weekly schedule. Update the hours card if you have exact daily hours.
- Phone number is linked as a tap-to-call link (`tel:`), and the Bolt Food + Facebook links go to the pages found for this listing — double check these still resolve correctly before launch.
