[![Build Status](https://travis-ci.org/cdcrabtree/revisions.svg?branch=master)](https://travis-ci.org/cdcrabtree/revisions)

## revisions: An R package that contains macroeconomic revisions data.
This R package contains vintages of macroeconomic data. These vintages are introduced and described in [Kerner and Crabtree 2018](https://osf.io/preprints/socarxiv/qsxae).

### Data
`gdp.wide` contains revision year data for the following macroeconomic indicators: GDP, GDP Per Capita, GDP Growth.

## Package Installation
The latest development version on GitHub can be installed using `devtools`.

```
if(!require("ghit")){
    install.packages("ghit")
}
ghit::install_github("cdcrabtree/revisions")
```

## Support or Contact
Having trouble with `revisions`? Please email [Charles Crabtree](mailto:ccrabtr@umich.edu) and he'll help you sort it out.
