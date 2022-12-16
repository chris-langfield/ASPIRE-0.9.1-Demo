# ASPIRE-0.9.1-Demo

Minimal example dataset needed to run the [ASPIRE](https://github.com/ComputationalCryoEM) 0.9.1 Demo file.

Change `root_folder` to your local path to this repository after cloning.

Then run the following (`conda` required)

```
conda create -n aspire_demo python=3.8
conda activate aspire_demo
pip install aspire==0.9.1
pip install jupyter
jupyter notebook aspire_demo.ipynb
```

