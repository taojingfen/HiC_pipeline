Release Notes
=============
Version 0.8.3 (2019-03-04)
--------------------------
- Parallelize statistics collecting
- Reduce computational overhead of the filtering step

Version 0.8.2 (2019-01-16)
--------------------------
- Fix the bug of large dataset overflow in binning

Version 0.8.1 (2018-12-23)
--------------------------
- Support Arima Hi-C

Version 0.8.0 (2018-9-16)
-------------------------
- Migrate to Python 3 (will not support Python 2 anymore)
- Change data container from HDF5 to Pairs and Cooler (to comply with 4DN standards)
- Two aligner options: bwa-mem (short reads) / minimap2 (long reads)
- Optionally output filtered SAM/BAM for further analysis
- Merge *binning* and *correcting*.

Version 0.7.0 (2017-10-29)
--------------------------
- Parallelized the execution on both laptops and PBS-based clusters.
- Included the latest *mirnylib* and *hiclib* source code.
- Tuned the class/function interfaces in sync with the lastest *hiclib*.
- Removed the *visualize* subcommand.
- Changed the default "--chroms" setting to "['#','X']"
- Refined the log.
- Added the detailed documentations.

Version 0.6.6-r2 (2016-5-4)
---------------------------
- Fixed a bug related to "--bowtieIndex".
- Included LICENSE.

Version 0.6.6-r1 (2015-11-10)
-----------------------------
- Only check for update when you are online.

Version 0.6.6 (2015-11-6)
-------------------------
- Removed redundant command-line arguments.
- Added detailed descriptions for the quality assessment module in Recipes.rst.
- Added snippets for automatic update checking.

Version 0.6.5 (2015-9-29)
-------------------------
- More sophisticated quality assessment module.
- Changed the filtering settings for *pileup*.
- Redirected the exception information into the log file.

Version 0.6.4 (2015-9-21)
-------------------------
- Fixed a bug related to the metadata loading.

Version 0.6.3 (2015-9-16)
-------------------------
- Customized the mirnylib Genome class by overriding the *_extractChrmLabel* method.

Version 0.6.2 (2015-8-21)
-------------------------
- Added the *visualize* subcommand.

Version 0.6.1 (2015-7-21)
-------------------------
- Improved the logging system.

Version 0.6.0 (2015-6-16)
-------------------------
- Fixed a bug for bam file parsing in the case of FASTQ read format.
