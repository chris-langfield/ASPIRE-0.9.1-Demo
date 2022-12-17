# ASPIRE-0.9.1-Demo

Minimal example dataset needed to run the [ASPIRE](https://github.com/ComputationalCryoEM) 0.9.1 Demo file.

Run the following (`conda` required)

```
conda create -n aspire_demo python=3.8
conda activate aspire_demo
pip install aspire==0.9.1
pip install jupyter
jupyter notebook aspire_demo.ipynb
```

Then change `root_folder` in the first cell to your local path to this repository after cloning.


