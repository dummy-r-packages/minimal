# Minimal R package

This (I think) is simplest R package you can have - no functions, files, etc. 

The packages builds and passes the usual checks

```
R CMD build minimal
R CMD check --as-cran minimal*.tar.gz
```
