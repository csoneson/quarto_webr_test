## Quarto webR example

1. Install the webR quarto extension (from within a project):
```
quarto add coatless/quarto-webr
```
2. Open a Quarto document and add the following to the YAML header:
```
filters:
    - webr
```
3. Create webR chunks by labeling them `{webr-r}` (rather than the usual `{r}`). 
4. Render the document as usual. 

### Resources
- [https://github.com/coatless/quarto-webr](https://github.com/coatless/quarto-webr)
