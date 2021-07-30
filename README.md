

## Build it locally and print a PDF

1. [install jekyll](https://jekyllrb.com/docs/installation/) on your computer. `gem install jekyll` will do for most users.
2. Clone your fork on your computer
3. Type `jekyll serve` and you'll be able to see your CV on your local host (the default address is http://localhost:4000).
4. You can edit the `index.md` file and see changes live in your browser.
5. To print a PDF, just press *Print*. Print and web CSS media queries should take care of the styling.

## Build it locally by docker

1. Clone your fork on your computer
2. Type `make build` to set up service
3. Type `make` or `make start`  to start service, then your can open `localhost:4000` on your local host to see your CV
4. You can edit the `index.md` file and see changes live in your browser.
5. Since the `jekyll-pdf` does not work well with this repo, try using Chrome's print feature, just right-click in your browser and click *print* tag

## Generating PDFs in one command

You can optionally integrate [jekyll-pdf](https://github.com/abeMedia/jekyll-pdf) to the package and automatically generate the PDF along with the HTML version. See more instructions in the [repo](https://github.com/abeMedia/jekyll-pdf). As of 02/07/2019, `jekyll-pdf` does not work well with this repo.

