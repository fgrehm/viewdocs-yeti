# Welcome to viewdocs-yeti

[Viewdocs](http://viewdocs.io) is [Read the Docs](https://readthedocs.org/) meets
[Gist.io](http://gist.io/) for simple project documentation. It renders Markdown
from your repository's `docs` directory as simple static pages.

viewdocs-yeti is a theme for Viewdocs that is based on [Yeti](http://bootswatch.com/yeti/)
with [syntax highlighting styles](https://github.com/broccolini/dinky/blob/master/stylesheets/pygment_trac.css)
from the [Dinky](https://github.com/broccolini/dinky) theme available on GitHub pages.

### Getting Started

Just make a `docs` directory in your Github project repository, download the available [template.html](https://github.com/fgrehm/viewdocs-yeti/blob/master/docs/template.html)
from this project over there and create a `index.md` file to get started:

    cd project
    mkdir -p docs
    wget https://raw.github.com/fgrehm/viewdocs-yeti/master/docs/template.html -O docs/template.html
    echo '# Hello world' > docs/index.md

Push the code back to the repository and browse to:

    http://<github-username>.viewdocs.io/<repository-name>
    # or if you pushed the code to a branch different than master
    http://<github-username>.viewdocs.io/<repository-name>~<branch-name>

Any other Markdown files in your `docs` directory are available as a subpath,
including files in directories. You can update pages by just pushing to your
repository or editing directly on Github. It can take up to 1-2 minutes before
changes will appear.

If you want to find out how things look like locally before pushing your code back
to the remote repository, you might want to try out [`previewdocs`](http://fgrehm.viewdocs.io/previewdocs).

This page is an example of what documentation will look like by default. Here
is [another example page](example). The source for these pages are in the
[docs directory](https://github.com/fgrehm/viewdocs-yeti/tree/master/docs) of the
viewdocs-yeti project.

<br />
<br />
Enjoy!<br />
[Fábio Rehm](http://twitter.com/fgrehm)
