---
title: The Sphinx Book Theme
---

::::{grid}
:reverse:
:gutter: 2 1 1 1
:margin: 4 4 1 1

:::{grid-item}
:columns: 4

```{image} ./_static/logo-square.svg
:width: 150px
```
:::

:::{grid-item}
:columns: 8
:class: sd-fs-3

A Sphinx theme with a clean design, support for interactive content, and a modern book-like look and feel.
:::

::::

[Flexible content layout](reference/special-theme-elements.md)
: Inspired by beautiful online books, such as [the Edward Tufte CSS guide](https://edwardtufte.github.io/tufte-css/)

[Visual classes designed for Jupyter Notebooks](reference/notebooks)
: Cell inputs, outputs, and interactive functionality are all supported.

[Launch buttons for online interactivity](launch)
: For pages that are built with computational material, connect your site to an online BinderHub for interactive content.

[Bootstrap 4](https://getbootstrap.com/docs/4.0/getting-started/introduction/)
: To style visual elements and add functionality.

International
: All text integrated in the theme is translated to the specified [Sphinx language](https://www.sphinx-doc.org/en/master/usage/configuration.html#confval-language).

:::{seealso}
This is the default theme in [Jupyter Book](https://jupyterbook.org).
:::

# Topic areas

The following topic areas will help you understand and use the theme.

```{toctree}
:maxdepth: 1
:caption: Topic Areas

tutorials/get-started
customize/index
content-blocks
launch
```

# Reference pages

Reference pages demonstrate the visual look of this theme.

```{toctree}
:caption: Reference
:maxdepth: 2

reference/special-theme-elements
reference/notebooks
reference/kitchen-sink/index
reference/blog
```


```{toctree}
:caption: About the theme
:maxdepth: 2

contributing
```

# Acknowledgements

This theme is heavily inspired by (and dependent on)
[PyData Sphinx Theme](https://pydata-sphinx-theme.readthedocs.io/) for its base
structure and configuration.

[pypi-badge]: https://img.shields.io/pypi/v/sphinx-book-theme.svg
[pypi-link]: https://pypi.org/project/sphinx-book-theme
