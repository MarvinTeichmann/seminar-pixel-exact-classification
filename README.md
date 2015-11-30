# seminar-pixel-exact-classification

This paper aims to summarize the state of the art in pixel-level semantic
segmenation. A special emphasis is put on possible applications like detection
of medical instruments when given (time series of) images from minimal-invasiv
operations.


## TODO before end of seminar

* Search TODO: `grep -rni TODO *`
* Remove LaTeX comments: `grep -rnE "%(.+)" *`
* Check .log file for
    * Warning
    * Error
    * Notice
* Use aspell: `aspell --lang=en --mode=tex check file.tex`
* Use academic writing checker (https://github.com/devd/Academic-Writing-Check)
* http://www.cs.umd.edu/~nspring/software/style-check-readme.html
* Cleanup:
    * latexindent
    * Remove trailing whitespace with `find . -type f -name '*.tex' -exec sed --in-place 's/[[:space:]]\+$//' {} \+`
    * Make sure every file ends with a newline
    * grep -P '\t' *

## TODO before submitting to arXiv
* `vorlage.tex`: use `IEEEtranSA`
* `grep -rni arxiv --include \*.tex *`
