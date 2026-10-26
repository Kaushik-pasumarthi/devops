# Calculator CI Demo

A minimal Python calculator with automated tests using GitHub Actions.

## Run locally

```bash
python -m pip install -r requirements-dev.txt
python -m pytest -v
```

## CI workflow

The workflow at `.github/workflows/ci.yml` runs on pushes and pull requests targeting `main` or `master`. It checks out the repository, configures Python 3.12, installs pytest, and runs the test suite.

## Capture the actual GitHub Actions screenshot

1. Create a GitHub repository and push these files to its `main` branch.
2. Open the repository's **Actions** tab and select **Calculator CI**.
3. Open the latest run and wait for the green check mark.
4. Capture a screenshot showing the successful run and, ideally, the completed **Run tests** step.

A local test screenshot/log is included in this demo, but it is not represented as a screenshot of a real GitHub-hosted run.
