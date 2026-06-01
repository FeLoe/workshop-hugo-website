# Academic Website — Hugo (Wowchemy) + Netlify

A minimal template for an academic personal website using
[Hugo](https://gohugo.io) with the [Wowchemy](https://wowchemy.com) Academic
theme, hosted for free on [Netlify](https://netlify.com).

> **Note:** Wowchemy has been rebranded as [Hugo Blox](https://hugoblox.com).
> The file structure is the same; only the name changed.

## What you get

- About/bio page with photo, social links, interests, education
- Publications list (auto-generated from individual files)
- Talks section
- Dark/light mode toggle
- Deploys automatically on every push to GitHub

## The files you need to edit

| File | What it controls |
|------|-----------------|
| `config/_default/config.yaml` | Site title, URL, navigation |
| `config/_default/params.yaml` | Theme colour, contact info |
| `content/authors/admin/_index.md` | Your bio, photo, social links |
| `content/publication/*/index.md` | One folder per publication |

## Setup (one time, ~20 minutes)

### 1. Fork or use this template on GitHub
Click **Use this template** → **Create a new repository**.

### 2. Connect to Netlify
1. Go to [netlify.com](https://netlify.com) and sign up with GitHub
2. Click **Add new site → Import an existing project**
3. Select your GitHub repo — Netlify detects Hugo automatically
4. Click **Deploy** — your site is live within 2 minutes

Your site URL will be `https://random-name.netlify.app`.
You can change it under **Site settings → Domain management**.

### 3. Fill in your info
Edit the files listed in the table above. Commit and push — Netlify
redeploys automatically.

### 4. (Optional) Preview locally
```bash
# Install Hugo (https://gohugo.io/installation/)
hugo server
# Open http://localhost:1313
```

## Adding a publication

1. Copy the folder `content/publication/my-first-paper/`
2. Rename the copy to something meaningful (e.g. `content/publication/smith-2024/`)
3. Edit `index.md` inside the new folder
4. Push — done

## Adding a profile photo

Put your photo at `content/authors/admin/avatar.jpg`.
