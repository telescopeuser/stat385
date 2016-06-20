# STAT 385 Course Website

Within this repository, the source code that is behind the [STAT 385 @ UIUC](http://stat385.thecoatlessprofessor.com) Summer 2016 Course Website can be found. 

Generally speaking, the website is made using the following tools:

- The backend of the site is powered by [`jekyll`](https://jekyllrb.com/), which enables the static generation of files from markdown documents.
- The service that is hosting the website is [GitHub Pages](https://pages.github.com/) via the `gh-pages` branch.
- To locally preview the website and convert `.Rmd` files to `.md` files, the [`servr`](https://cran.r-project.org/web/packages/servr/index.html) that interfaces with [`knitr`](https://cran.r-project.org/web/packages/knitr/index.html).
- The display of LaTeX math is done via [MathJax](https://www.mathjax.org/) code snippet that must be enabled within the post front matter via `mathjax:true`

For more information, please see refer to a future post on <http://thecoatlessprofessor.com/>.