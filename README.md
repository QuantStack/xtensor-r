# ![xtensor-r](http://quantstack.net/assets/images/xtensor-r.svg)

**THIS IS A SUPER EARLY PREVIEW OF THE R BINDINGS, PLEASE DON'T USE IT JUST YET**

R bindings for the [xtensor](https://github.com/QuantStack/xtensor) C++ multi-dimensional array library.

## Test

Install `devtools` and `Rcpp` for R: 

```
install.packages('Rcpp')
install.packages('devtools')
```

And then, to build the `xtensor` R package, and install into the R workspace, run the following script. 
It will also call the `rcpp_hello_xtensor` function from `src/rcpp_hello_xtensor.cpp`.

```
cat install_and_test.R | R --no-save
```
