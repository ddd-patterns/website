# Domain-Driven Design Patterns

ReadTheDocs requires repository to be public if we want the page to be automatically built and published on git push.

For now we can stick to the local building and publish the repo and site once we are ready. In order to work on it locally we need sphinx and a theme:

```bash
pip install sphinx
pip install sphinx_rtd_theme
```

Once that's done we can build and open the page:
```bash
cd docs
make html
open build/html/index.html
```

If something doesn't render as expected:
```bash
make clean
```

The site generated locally is a basic one, but the one generated on read the docs also generates pdf, epub etc and includes a link to editing the page on github. A dummy example here: https://ddd-patterns-www.readthedocs.io/

RST markup language (an examples):
* https://en.wikipedia.org/wiki/ReStructuredText
* https://sphinx-rtd-theme.readthedocs.io/en/stable/index.html