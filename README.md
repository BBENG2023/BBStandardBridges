# Beaver Bridges — Standard Bridge Catalogue

Public-facing catalogue and interactive configurator for the Beaver Bridges standard permanent bridge range.

## Files

| File | Purpose |
|---|---|
| `index.html` | Product catalogue — 7 standard bridge forms, specs, photos, loading matrix |
| `configurator.html` | Interactive 5-step configurator — routes users to the right product, generates a pre-filled enquiry email to bbsales@beaverbridges.co.uk |

Both files are fully self-contained single-file HTML — all images, fonts, and styles embedded. No build tools, no dependencies, no server needed.

---

## Hosting on GitHub Pages — step by step

### 1. Create the repository

1. Go to [github.com/new](https://github.com/new)
2. Repository name: `bb-bridge-catalogue` (or your preference)
3. Set to **Public**
4. Leave "Add a README file" unchecked
5. Click **Create repository**

### 2. Upload the files

1. On the empty repo page, click **"uploading an existing file"**
2. Drag in all three files from this zip: `index.html`, `configurator.html`, `README.md`
3. Commit message: "Initial catalogue upload"
4. Click **Commit changes**

### 3. Enable GitHub Pages

1. Go to **Settings** (gear icon, top menu bar)
2. Left sidebar → **Pages**
3. Source: **Deploy from a branch**
4. Branch: **main** / Folder: **/ (root)**
5. Click **Save**
6. Wait 1–2 minutes for deployment

### 4. Your site is live

- Catalogue: `https://<username>.github.io/bb-bridge-catalogue/`
- Configurator: `https://<username>.github.io/bb-bridge-catalogue/configurator.html`

---

## Updating

Replace either HTML file in the repo (upload or edit via GitHub) — Pages redeploys automatically within a couple of minutes.

---

## Optional: Custom domain

To serve from e.g. `catalogue.beaverbridges.co.uk`:

1. In repo **Settings → Pages → Custom domain**: enter `catalogue.beaverbridges.co.uk`, save
2. With your DNS provider, add a CNAME record: host `catalogue` pointing to `<username>.github.io`
3. Wait for DNS propagation (minutes to hours)
4. Tick **Enforce HTTPS** in Pages settings

---

Beaver Bridges Ltd · The Warehouse, Cartmel Drive, Harlescott, Shrewsbury SY1 3TB
01743 811 811 · beaverbridges.co.uk · NCE Bridge Contractor of the Year 2024
