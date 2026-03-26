# Jess Pinili — Link in Bio

A custom Linktree-style link-in-bio page. Single HTML file, no build step required.

## Swapping images

Replace any file inside the `/images` folder with a new image of the same name:

| File | Used for |
|---|---|
| `wmhq.png` | Woman Mastery HQ (Links + Shop) |
| `think-like-a-ceo.png` | Think Like A CEO masterclass |
| `seen-in-seasons.png` | Seen in Season Workshop |
| `unmuted.png` | Unmuted Content Dashboard |

Images are referenced as `./images/filename.png` — keep filenames exact.

## Updating links

Open `index.html` and use **Ctrl+F** (or Cmd+F) to find the URL you want to change, then replace it.

## Deploying to Vercel

**Option A — CLI:**
```bash
vercel --prod
```

**Option B — Drag & drop:**
Go to [vercel.com](https://vercel.com), create a project, and drag the entire project folder in.

## Deploying to Netlify

Go to [netlify.com/drop](https://app.netlify.com/drop) and drag the entire project folder onto the page. Done.
