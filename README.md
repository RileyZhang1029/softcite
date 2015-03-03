softcite
========

A repo to hold the data and analysis files for a study of the citation of scientific software.

Currently the code that runs and executes some SPARQL queries against the data/SoftwareCitationDataset.ttl file.  Those are run with mvn exec:java.

To run the SPIN rules:

mvn -Dtest=AppTest#testSPINoutput test

Contact: 

James Howison
jhowison@ischool.utexas.edu

[![DOI](https://zenodo.org/badge/9584/jameshowison/softcite.svg)](http://dx.doi.org/10.5281/zenodo.14727)


