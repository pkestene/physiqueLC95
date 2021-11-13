# Composition de physique du concours ENS Lyon/Cachan 1995

## le [sujet](docs/compo_physique_ensLC95.pdf)

## le [corrigé](https://pkestene.github.io/physiqueLC95)

# MkDocs

le corrigé est rédigé en markdown à l'aide de l'outil [mkdocs](https://www.mkdocs.org/)

## Prérequis

Pour ceux qui souhaitent savoir comment le site a été configuré avec MkDocs, il est nécessaire d'avoir installé les paquets suivants:

- python3 Mkdocs : pip3 install mkdocs
- material theme : pip3 install mkdocs-material
- extensions :
   - pip3 install pymdown-extensions
   - pip3 install mkdocs-enumerate-headings-plugin

## Configuration

A propos du rendu HTML des équations mathématiques, on utilise ici l'extension arithmatex.

Autres resources intéressantes:

  - [katex](https://katex.org/)
  - https://squidfunk.github.io/mkdocs-material/extensions/pymdown/
  - https://www.mkdocs.org/user-guide/configuration/#extra_css
  - https://facelessuser.github.io/pymdown-extensions/extensions/arithmatex/#mathjax-output-format

Finally modify mkdocs.yml, especially arithmatex to generate generic output needed by katex.

## Visualiser le site localement

```shell
mkdocs serve
```

## Publier un site mkdocs sur github pages

See https://squidfunk.github.io/mkdocs-material/publishing-your-site/
