#Drat repository for my R-packages



###install R-package drat
```r
install.packages("drat")
```
###Install an inofficial release/package (e.g. mesheR)
```r
drat::addRepo("zarquon42b")
install.packages("mesheR")
```

###Update my packages (together with other R-packages)
```r
drat::addRepo("zarquon42b")
update.packages()
```
You can add the repo permanently by adding the line ```drat::addRepo("zarquon42b")``` to ~/.Rprofile.
