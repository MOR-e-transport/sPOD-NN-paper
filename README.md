## Parametric model order reduction for a wildland fire model via the shifted POD based deep learning method

This repo contains the source code for a novel non-intrusive model reduction method named sPOD-NN. The script (`.ipynb`) files for all the test cases are present in the `tests` folder. 
* `synthetic.ipynb` describes the application of the proposed methods on a 1D synthetically generated data set.
* `wildfire1D.ipynb` performs the non-inrusive model reduction on a 1D wildland fire model.
* `wildfire2D.ipynb` shows the application of the proposed methods on a 2D wildland fire model without any external wind.
* `wildfire2DNonLinear.ipynb` is similar to the previous case but under the influence of a constant unidirectional wind.

The reader is encouraged to try out the sample test case : `synthetic.ipynb` for which the data generation is already included in the code. However, for other examples the reader can open an issue and the data could be provided thereafter upon request.
