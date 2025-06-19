# data-visualization-intro

[![Renku](https://renkulab.io/renku-badge.svg)](https://renkulab.io/p/boehs/data-visualization-intro)

## Run the tutorial on your computer

You have two ways in which you can run the tutorial **locally**.

### 1. With a `conda` environment

#### 0. Prerequisites

To run the tutorial locally, you should first install [conda](https://docs.conda.io/en/latest/miniconda.html) (or [mamba](https://mamba.readthedocs.io/en/latest/installation/mamba-installation.html)).

It is also suggested that you have a recent version of `git`. Check out [how to install `git`](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git) on your operating system.

#### 1. Download the material

Go to the directory on your machine where you want to download the material and clone the repository:

```console
git clone https://github.com/simonboehme/data-visualization-intro
```


#### 2. Create a dedicated environment

Enter the tutorial folder with

```console
cd /path/to/data-visualization-intro

```

> If you have installed Anaconda, then you can use Anaconda Prompt to run the following commands.

You should now create a new environment with `conda`:

```console
conda env create -f environment.yml
```

> [!WARNING]
>
> If you are on Windows and using Command Prompt or the PowerShell, please make sure to adjust the paths in the commands above accordingly.

Then activate the environment with

```console
conda activate data-visualization-intro

```

You can update the existing environment (that is, downloading the latest version of the packages) with:

```console
conda env update -f environment.yml
```

#### 3. Launch the tutorial via Jupyter

Finally, launch JupyterLab with

```console
jupyter lab
```
