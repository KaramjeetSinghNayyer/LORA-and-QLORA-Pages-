# LoRA & QLoRA — GitHub Pages edition

`index.html` is a standalone edition of the interactive article. It embeds its styles, scripts, and downloadable Python project. Upload this single HTML file to your repository root; no build, package installation, or additional article assets are required. Google Fonts and linked research resources require an internet connection. Python training runs separately.

## Publish

1. Create or open a GitHub repository with GitHub Pages available for your plan.
2. Upload `index.html` directly to the root of the `main` branch and commit it. Keep the filename exactly `index.html`.
3. Open **Settings → Pages**.
4. Select **Deploy from a branch**, choose **main**, and select **/ (root)**.
5. Click **Save**, then open the site URL shown by GitHub once deployment completes.

Extract the supplied archive before uploading; GitHub Pages does not unpack ZIP files. The HTML file itself is all that is needed to serve the article. The included `.nojekyll` file can also be uploaded when publishing the full folder.

Official instructions: [Configure a GitHub Pages publishing source](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site).

## Local preview

From this folder:

```sh
python3 -m http.server 8776 --bind 127.0.0.1
```

Open http://127.0.0.1:8776/.

The separate LoRA/QLoRA tabs, diagrams, quizzes, code copying, Markdown export, themes, and embedded project download are retained. Existing external links to the earlier Fieldbook retain their original access requirements.

The source project and full resource catalog are documented in `field-guide/README.md` in the original workspace. Educational Python training has not been executed or benchmarked here.
