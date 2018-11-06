# journey-paper-replication
Datasets and programs for the paper "A Journey Among Java Neutral Program Variants"

The organization of this repository is the following:
 * `projects/` contains a snapshot of the sources of the 6 java project used for this paper and the test execution traces of the unmodifed projects used as reference for detecting behavior differences
 * `RQ1/` contains the dataset for RQ1 as well as the R scripts to produce figures and tables.
 * `RQ2/` contains R scripts to produce figures and tables for RQ2
 * `RQ3/` contains R scripts to produce figures and tables for RQ3
 * `RQ4/` contains the variants used for RQ4
 * `RQ5/` contains the variants generated for RQ5, and descriptions of the transformations

Variants can be generated with the help of [sosiefier](https://github.com/DIVERSIFY-project/sosiefier/releases/tag/2.0.0) and traces can be obtained and compared with [yajta](https://github.com/castor-software/yajta/releases/tag/2.0.0)
