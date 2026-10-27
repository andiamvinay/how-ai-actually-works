# How AI Actually Works

An interactive, single-page course that takes software engineers from zero to understanding LLM internals, inference optimization and AI systems such as RAG and agents. It has 30 modules, each with an explanation, a hands-on simulation, a production note, a quiz and interview practice.

Everything lives in one self-contained `index.html`. There is no build step, no backend, no tracking and no external requests. Progress is saved in your browser's local storage on each device.

## Run locally

Open `index.html` in any modern browser.

## Publish on GitHub Pages

1. Create a new **public** repository on GitHub, for example `how-ai-actually-works`.
2. Choose **Add file → Upload files**, drop in `index.html`, `README.md` and `.nojekyll`, then commit.
3. Go to **Settings → Pages**. Under **Build and deployment**, set **Source** to **Deploy from a branch**, pick `main` and `/ (root)`, then click **Save**.
4. After a minute or two the site is live at `https://<your-username>.github.io/how-ai-actually-works/`.

To publish an update, upload the new `index.html` over the old one and commit. Pages redeploys automatically.

### Using git instead

```bash
git init
git add index.html README.md .nojekyll
git commit -m "Publish How AI Actually Works"
git branch -M main
git remote add origin https://github.com/<your-username>/how-ai-actually-works.git
git push -u origin main
```

Then enable Pages as in step 3.

## Linking to a module

Each module has a stable link, for example `.../#m16` for RAG or `.../#m30` for the interview drill.
