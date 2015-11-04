# CompInvesting1

## Setting up Environment

Setting up the course software can be a hastle despite the detailed instructions the course provides. This is in part because the QSTK software relies on some outdated packages. To ensure that the software for this course doesn't interfere with your other projects, I **highly recommend** either using vagrant image found on the [Quant Software github page](https://github.com/QuantSoftware/QuantSoftwareToolkit) or (what I did) use a virtual environment

Since you are taking this course, I assume that you are interested in scientific computing and data analysis more generally. For that reason, I recommend using the Anacondas python distribution and condas for your package management and virtual environment management. If you are not familiar with virtual environments, I recommend going through the "Get Started" and "Using Conda" tutorials found here: http://conda.pydata.org/docs/get-started.html.

With conda, you can use my environment.yml file to set up the environment

```
conda env create -f environment.yml

source activate qstk
```

