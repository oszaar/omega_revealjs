# A bare-bones Quarto template for presentations

## Summary

- Contains weird black .svg background for when I have match the .ppt template from my job
- Contains more generic .svg vertical split background of a dark and light color that matches the style I use for labnotes slides that I typset in org-mode

## Usage

```bash
quarto use template oszaar/omega_revealjs
```

This will install the extension and create an example qmd file that you can use as a starting place for your article.

## A nice set of plugins

### Attribution

```bash
quarto add quarto-ext/attribution
```

### Pointer

```bash
quarto add quarto-ext/pointer
```

```bash
title: My Presentation
format:
    revealjs: default
    pointer:
      - # set pointer configuration options here
revealjs-plugins:
  - pointer
```

## Further work

*TODO*: There is an ugly workaround for the title-slide. The goal was to have a vertical split in color but could not manage to fill the entire screen. For now I use a svg image and when switching to group slides I switch to the black background.