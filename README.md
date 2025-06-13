<<<<<<< HEAD
# User-Guide
Documentations for Cudy products
=======
# Cudy Documentation

This repository is the source code for documentation of Cudy Products.

## Environment 

Build by [mkdocs](https://www.mkdocs.org/) 1.5.3, with theme [mkdocs-material](https://squidfunk.github.io/mkdocs-material/) 9.4.6

## Installation

Create a new python virtualenv

`python3 -m venv docs-venv`

Activate the virtualenv, then

`pip install mkdocs-material` or `pip install mkdocs-material=="9.*" `

Or use the requirements.txt in the root of the project

`pip install -r requirements.txt`

Refer: [https://squidfunk.github.io/mkdocs-material/getting-started/#with-pip](https://squidfunk.github.io/mkdocs-material/getting-started/#with-pip)

## Online View

Please view the docs online at [https://cudy.com/docs](https://cudy.com/docs)

## Guide

### Markdown syntax

Each page use markdown, please check out this basic syntax of markdown [here](https://www.markdownguide.org/basic-syntax/).

### Open in new tab

If you wanna a link to open in new tab, add `{target="_blank"}` at the end of link block.

### Image file type

Prefer to use png.

### Image lightbox

If the size of image is too big, please use the PhotoSwipe, check out [here](#about-plugin-photoswipe).

### Image captions

```html
<figure>
  <img src="https://dummyimage.com/600x400/eee/aaa" width="300" />
  <figcaption>Image caption</figcaption>
</figure>
```

### Use relative path to link internal content

```
[easymesh](../../../setup_guide/easymesh)
```

## About plugin PhotoSwipe

Using the v4 version, v5 version looks better, but need to load js module. Don't know how to work it out in mkdocs.

Suggest to use PhotoSwipe when the width of image is large than 1021px.

Reference:

[https://photoswipe.com/documentation/getting-started.html](https://photoswipe.com/documentation/getting-started.html)

[https://codepen.io/dimsemenov/pen/ZYbPJM](https://codepen.io/dimsemenov/pen/ZYbPJM)

## About versoning

There is a plugin named `mike` is for versoning, it need to deploy with Github Page, but I don't use Github Page, I just copy the file structure like `mike` does. Please check out [mkdocs-material-example-versioning](https://github.com/squidfunk/mkdocs-material-example-versioning), and switch to `gh-pages` branch.

Reference:

[Setting up versioning](https://squidfunk.github.io/mkdocs-material/setup/setting-up-versioning/)

[https://squidfunk.github.io/mkdocs-material-example-versioning/](https://squidfunk.github.io/mkdocs-material-example-versioning/)

## Jenkins integration

```
# go to docs-build path to get latest git commit
# incase some guys build on their computer
cd /root/docs-build/
git reset --hard HEAD
git pull
# activate virtualenv
cd /root/docs-venv/
. ./bin/activate
# git pull latest commit
cd docs4.x
git checkout master
git reset --hard HEAD
git pull
# build docs to /root/docs-build/router/en/4/
mkdocs build
# deactivate virtualenv
deactivate
echo "finish building"
#
cd /root/docs-build/
git add .
git commit -m "docs4 build"
git push
echo "done"
```
>>>>>>> 1dbb8a4 (Initial commit)
