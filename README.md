# WAL Cache Analysis Methodology

This is a cache analysis library based on the methodology presented in our paper
"An Extensible and Flexible Methodology for Analyzing the Cache Performance of Hardware Designs".

To analyze the exemplary IBEX waveforms run
```
wal ibex.wal traces/ibex_bubblesort_disabled.fst
```
or
```
wal ibex.wal traces/ibex_bubblesort_enabled.fst
```

To run the analysis on the example traces you need to have `pylibfst` installed.
Install `pylibfst` with `pip install pylibfst` (does not work on windows currently).
