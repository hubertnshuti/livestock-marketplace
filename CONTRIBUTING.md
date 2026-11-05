# Contributing to Livestock Marketplace

Thank you for helping improve this project! All skill levels are welcome.

## Quick start
1. Fork the repository and clone your fork.
2. Create a branch: `git switch -c type/short-description`.
3. Install dependencies with `pip install -r requirements.txt`.
4. Run migrations with `python manage.py migrate`.
5. Make a focused change and add or update tests when relevant.
6. Run `python manage.py check` and the test suite before committing.
7. Push your branch and open a pull request using the template.

## Run the home page smoke test

After installing dependencies, run the focused Django smoke test:

```shell
python manage.py test livestock.tests.HomePageSmokeTests
```

This test requests the public home page and checks for HTTP 200 and the `home.html` template.

## Good first contributions
Look for issues labeled **good first issue** or **help wanted**. Comment on an issue before starting substantial work so efforts do not overlap.

## Commit and pull request guidance
Use a clear imperative commit subject, keep pull requests focused, explain what changed and how it was tested, and link the related issue with `Fixes #N` when appropriate.

## Code of conduct
By participating, you agree to follow our [Code of Conduct](CODE_OF_CONDUCT.md).
