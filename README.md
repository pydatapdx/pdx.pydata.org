# PyData PDX Website

This repository contains the source code for the website [pdx.pydata.org](https://pdx.pydata.org).

## Developing

1. Install [Docker](https://docs.docker.com/v17.12/install/)
2. Clone the project repository
3. Run the following command to serve it:
   ```
   export JEKYLL_VERSION=4
   docker run --name pydatapdx --volume="$PWD:/srv/jekyll" -p 4000:4000 -it jekyll/jekyll:$JEKYLL_VERSION jekyll serve --watch --drafts
   ```
5. Natigate to `http://localhost:4000`

While running Jekyll will automatically rebuild the site and refresh the browser when changes are made to the source code.


## Removing the container
```
docker rm -f pydatapdx
```
