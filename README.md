# INSA_LFP_DATASET

This sample dataset was used in our paper: « SocSHAP: a new data driven explainable prediction of battery state of charge ». It consists of two lithium-ion battery cells cycled with WLTP (Worldwild harmonised Light vehicle Test Procedure) test. The two lithium-ion phosphate (LFP) produced by A123 Systems (under the reference APR18650M1A) were cycled using the test system XCTS from Basytec. The cells have a nominal voltage of 3.3 V and a nominal capacity of 1.1 Ah.

The battery cycler is programmed to wear out the cells in cycles consisting of a charge phase and a discharge phase. The charging phases are carried out using the classic method of charging cells (constant current charge and then constant voltage for different current intensity levels). The discharge phase is constituted by using the driving cycles described previously by putting end to end several of these cycles. This phase also integrates the phenomenon of regenerative braking.

Two data files are available in .csv format (one file for each cell tested). The discharge phase is the same for both files. However, the first one contains charging phases with multiple step intensities and the second one contains only one intensity step.

The measured raw data available in the files are:
- The time (hours)
- The voltage of the cell (V)
- The current delivered by the cell or by the cycler (A)
- The temperature of the cell (°C) measured by a thermocoupler attached to the cell's surface.
- The capacity for the actual state (Ah)

Link to the dataset: https://seafile.unistra.fr/d/170177cbd3d34fb9bc5f/.