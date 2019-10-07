# PyData PDX Website

This repository contains the source code for the website [pdx.pydata.org](https://pdx.pydata.org).

## Developing

1. Install [Docker](https://docs.docker.com/v17.12/install/)
2. Clone the project repository
3. Remove any Gemfile[.lock] from the project root directory
4. Run `make serve` to build and serve the website from within a [`jekyll`](https://hub.docker.com/r/jekyll/jekyll/) container.
5. Natigate to `http://localhost:4000`

```
git clone https://github.com/pydatapdx/site
cd bokeh.org
rm -f Gemfile Gemfile.lock
make serve
```

While running Jekyll will automatically rebuild the site and refresh the browser when changes are made to the source code.
