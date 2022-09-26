# GitHub Mkdocs Template

A template for using [mkdocs](https://www.mkdocs.org/) with GitHub actions to generate a static site.

To get an overview of how to use this template, check out the [main page](https://mooreryan.github.io/github_mkdocs_template/) of the example docs site!

## Install `mkdoks`

To test out your site locally, you will need to install [mkdocs](https://www.mkdocs.org/). You can [install](https://anaconda.org/conda-forge/mkdocs) it with `conda` like so:

```shell
conda create -n mkdocs
conda activate mkdocs
conda install -c conda-forge mkdocs
```

### Run a development server

Activate the `conda` environment, or however you want to install it, and run the following.

```
cd _docs_src/
mkdocs serve
```

## License

<p xmlns:dct="http://purl.org/dc/terms/">
  <a rel="license"
     href="http://creativecommons.org/publicdomain/zero/1.0/">
    <img src="http://i.creativecommons.org/p/zero/1.0/88x31.png" style="border-style: none;" alt="CC0" />
  </a>
  <br />
  To the extent possible under law,
  <span resource="[_:publisher]" rel="dct:publisher">
    <span property="dct:title">Ryan M. Moore</span></span>
  has waived all copyright and related or neighboring rights to
  <span property="dct:title">GitHub Mkdocs Template</span>.
</p>

_If for whatever reason, CC0 will not work for your project, you may use MIT or the Unlicense._
