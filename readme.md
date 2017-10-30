sbvchk
===

[![Build Status](https://travis-ci.org/vzaccaria/sbvchk.png)](https://travis-ci.org/vzaccaria/sbvchk)

See https://vzaccaria.github.io/sbvchk/index.html for project description.

~~~
stack build --test --exec "$(stack path --local-install-root)/bin/sbvchk-example" --exec "$(stack path --local-bin)/pandoc -f markdown+lhs -i app/example.lhs -t html -o index.html --filter pandoc-include --mathjax" --file-watch
~~~
