# ExamStudio: Ledger Lab

**Live website:** [Open Ledger Lab](https://jonasnekzad.github.io/examstudio/)  
**Source repository:** https://github.com/JonasNekzad/examstudio  
**Submission details:** [SUBMISSION.md](SUBMISSION.md)

Independent practice website for Data Analytics in Accounting, with 25 source-grounded exercises, six targeted mistake reviews, a mock exam and downloadable course materials.

## Source and deployment

The complete site source and course files are included in `examstudio-source.zip`. The GitHub Actions workflow extracts the archive and publishes its `dist/` directory to GitHub Pages when changes are pushed to `main`.

The site stores practice progress in browser local storage. It does not execute arbitrary SQL or formulas, grade free-text answers, or claim measured learning outcomes.
