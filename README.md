# IntelArcProB70-LLM-Benchmarks
Intel Arc Pro B70 LLM Benchmarks

## Viewing the Benchmarks

The benchmark results are published via **GitHub Pages** and are accessible at:

```
https://kinetic69.github.io/IntelArcProB70-LLM-Benchmarks/
```

## How to Add / Update the Benchmark HTML File

1. **Save your HTML file** as `docs/index.html` inside this repository (replacing the placeholder that is already there).
2. Commit and push the file:
   ```bash
   git add docs/index.html
   git commit -m "Add benchmark results"
   git push
   ```
3. **Enable GitHub Pages** (one-time setup, repo owner only):
   - Go to **Settings → Pages** in this repository.
   - Under *Source*, select **Deploy from a branch**.
   - Choose the `main` branch and the `/docs` folder, then click **Save**.

After a few seconds the page will be live at the URL above.

> **Tip:** If you want to keep additional benchmark HTML files (e.g. for different models or parameter sets), add them to the `docs/` folder and link to them from `docs/index.html`.
