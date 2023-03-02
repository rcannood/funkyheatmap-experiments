# FunkyHeatmap D3 experiment

Superseded by [nmarkov/funkyheatmap-js](https://github.com/mxposed/funkyheatmap-js).

## Install

Install R and quarto.

Run:

```R
install.packages("renv")
renv::restore()
```

(Normally, running `quarto preview` will perform `renv::restore()` automatically).

## Install extra dependency and update renv

```R
install.packages("fs")
renv::snapshot()
```

## Preview

Run:

```bash
quarto preview
```

## Build

Run:

```bash
quarto render
```