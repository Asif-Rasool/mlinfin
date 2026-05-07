# Machine Learning in Finance

Hugo course website for Machine Learning in Finance, using the PaperMod theme.

The public site is intentionally simple:

- Home
- Syllabus
- Video Lessons
- Projects
- Quizzes
- Exams
- Files

## Local Development

```powershell
git submodule update --init --recursive
hugo server
```

The site will be available at `http://localhost:1313/`.

## Production Build

```powershell
hugo --minify
```

## GitHub Pages

The repository includes a GitHub Actions workflow at `.github/workflows/hugo.yml`.

After pushing to GitHub:

1. Go to the repository settings.
2. Open **Pages**.
3. Set **Source** to **GitHub Actions**.

The live site will publish to:

`https://asif-rasool.github.io/mlinfin/`
