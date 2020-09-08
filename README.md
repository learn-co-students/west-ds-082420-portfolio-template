# Portfolio Website Template

Template for Flatiron School Data Science students to build a portfolio website

## To use:
1. Make a fork of this repository
2. Rename the repository `<your github username>.github.io`
3. Clone the repository locally
4. Edit `index.html` so it has information about you, and your project
5. Replace `img/profile.jpg` with a photo of you, and `jupyter_notebooks/example.html` with your actual exported Jupyter Notebook (see explanation below for how to export a Jupyter Notebook as HTML)
6. Git commit and push
7. Now your website is live!  It might take a couple minutes the first time around, but you should be able to navigate to `https://<your github username>.github.io` in the browser to see your live portfolio.  This is a service of GitHub, called [GitHub Pages](https://help.github.com/en/articles/what-is-github-pages)

### To export your Jupyter Notebook:
1. In the same directory as the notebook, run `jupyter nbconvert <your notebook name>.ipynb --to html --output <output file name>.html` (for more details about the different `nbconvert` options, see the [documentation](https://nbconvert.readthedocs.io/en/latest/usage.html))
2. Move the generated `.html` file into the `jupyter_notebooks` directory of this repository
3. Edit the link in `index.html` so it points to the generated file.  This will be a relative path, something like `<a href="jupyter_notebooks/king-county-housing.html" class="text-primary">View Jupyter Notebook</a>`


## Attribution

Start Bootstrap is an open source library of free Bootstrap templates and themes. All of the free templates and themes on Start Bootstrap are released under the MIT license, which means you can use them for any purpose, even for commercial projects.

* https://startbootstrap.com
* https://twitter.com/SBootstrap

Start Bootstrap was created by and is maintained by **[David Miller](http://davidmiller.io/)**, Owner of [Blackrock Digital](http://blackrockdigital.io/).

* http://davidmiller.io
* https://twitter.com/davidmillerskt
* https://github.com/davidtmiller

Start Bootstrap is based on the [Bootstrap](http://getbootstrap.com/) framework created by [Mark Otto](https://twitter.com/mdo) and [Jacob Thorton](https://twitter.com/fat).

## Copyright and License

Copyright 2013-2019 Blackrock Digital LLC. Code released under the [MIT](https://github.com/BlackrockDigital/startbootstrap-resume/blob/gh-pages/LICENSE) license.
