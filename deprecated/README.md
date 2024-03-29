> WARNING: This folder is under active development
# Examples

This folder provides example scripts to run and visualize Pace.

To run Pace, specify the serialized data path, number of time steps, and the desired backend:

```
python dyn_phy.py /test_data/c128_6ranks_baroclinic_dycore_microphysics 15 gtc:gt:gpu
```

- `dyn_phy`: this is the current front end code to initialize from serialized output data, run the dynamical core and physics. The current model output format is subject to change.

- `plotting_model_outputs`: example plotting scripts using tools in [fv3viz](https://github.com/ai2cm/fv3net/tree/master/external/fv3viz). Note that `fv3viz` is currently not a requirement for this repository, additional requirements are needed to run the plotting scripts. This is subject to change.
