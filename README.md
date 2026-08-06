# diss-interactive-plots

Interactive plots of contextual embedding distribution for lexical-semantic change case studies in PhD dissertation.

## Publish Plotly HTML files on GitHub Pages

1. Upload your Plotly HTML files into `/home/runner/work/diss-interactive-plots/diss-interactive-plots/docs/plots/`.
2. Edit `/home/runner/work/diss-interactive-plots/diss-interactive-plots/docs/index.html` and add each file name to the `PLOT_FILES` array.
3. In GitHub: **Settings → Pages**:
   - **Source**: `Deploy from a branch`
   - **Branch**: `main`
   - **Folder**: `/docs`
4. Open your site at: `https://vlunardi.github.io/diss-interactive-plots/`

Each listed file will appear as a link and open in a new tab.
