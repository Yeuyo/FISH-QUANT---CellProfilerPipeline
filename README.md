# FISH-QUANT---CellProfilerPipeline

This is the pipeline file required for CellProfiler to identify cell and nucleus boundaries.
The original pipeline is obtained from https://bitbucket.org/muellerflorian/fish_quant/src/master/; however, their pipeline is outdated for the newer version of CellProfiler.

The pipeline can be used for different images quality by adjusting the "Threshold smoothing scale" and "Threshold correction factor" in step 5 (IdentifyingPrimaryObjects) and step 6 (IdentifyingSecondaryObjects) respectively.

* Tested on CellProfiler v4.2.1
