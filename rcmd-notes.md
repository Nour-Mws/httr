The following notes were generated across my local OS X install, ubuntu running on travis-ci and win builder (devel and release):

* checking CRAN incoming feasibility ... NOTE

  Roxygen and RCurl are not spelling errors.

I have also run R CMD check on downstream dependencies of httr. Results are available at:

* R release: https://github.com/wch/httr-checkresults/blob/master/r-release/00check-summary.txt

* R devel: https://github.com/wch/httr-checkresults/blob/master/r-devel/00check-summary.txt

There were problems with three packages: ecoengine, rinat and RSocrata. I have corrresponded with all authors. The RSocrata author (cc'd) will submit a corrected version when this httr update is accepted. The ecoengine and rinat authors will update in the next couple of days.
