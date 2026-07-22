# pagerain.org

Static website for [pagerain.org](https://pagerain.org), hosted with GitHub Pages.

## Local development

```bash
npm install
npm run dev
```

Open <http://localhost:41789>.

## Deployment

GitHub Pages serves the repository root from the `main` branch. The `CNAME` file configures the custom domain, and `.nojekyll` ensures the files are served without Jekyll processing.

After pushing the first commit, open **Settings → Pages** in `nbgyxi/pagerain.org` and select **Deploy from a branch**, then choose `main` and `/ (root)`.
