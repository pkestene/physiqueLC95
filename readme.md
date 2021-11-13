## Getting started - requirements

- python3 Mkdocs : pip3 install mkdocs
- material theme : pip3 install mkdocs-material
- extensions :
   - pip3 install pymdown-extensions
   - pip3 install mkdocs-enumerate-headings-plugin


## Configuration

About Latex rendering with [katex](https://katex.org/), see pages
  - https://squidfunk.github.io/mkdocs-material/extensions/pymdown/
  - https://www.mkdocs.org/user-guide/configuration/#extra_css
  - https://facelessuser.github.io/pymdown-extensions/extensions/arithmatex/#mathjax-output-format

Finally modify mkdocs.yml, especially arithmatex to generate generic output needed by katex.

## Running localy

```shell
mkdocs serve
```

## github pages

See https://squidfunk.github.io/mkdocs-material/publishing-your-site/
