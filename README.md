# data-visualization-intro

[![Renku](https://renkulab.io/renku-badge.svg)](https://renkulab.io/p/boehs/data-visualization-intro)

The suggested way to run this tutorial is via renku (a service provided by the Swiss Data Science Center).
Simply click on the above link, which takes you to renku.
Then click on the green "Launch" button, which launches the renku session.
Now you can run various available jupyter notebooks on data visualization.

> [!WARNING]
>
>- a running renku session will be saved for 2 weeks and during this time you can always resume your work by clicking on the "resume session" button. Do not click "shut down session" as this means all your changes to the renku files will be lost.
>- before you shut down your session and/or if you want to have access to your files there for more than 2 weeks, it is adviced to create a local copy of your work by downloading your renku files to your local machine
<br>

## Only as an alternative: run the tutorial on your computer

You have two ways in which you can run the tutorial **locally**.

### 1. With a `conda` environment

#### 0. Prerequisites

To run the tutorial locally, you should first install [conda](https://docs.conda.io/en/latest/miniconda.html) (or [mamba](https://mamba.readthedocs.io/en/latest/installation/mamba-installation.html)).

It is also suggested that you have a recent version of `git`. Check out [how to install `git`](https://git-scm.com/book/en/v2/Getting-Started-Installing-Git) on your operating system.

#### 1. Download the material

Go to the directory on your machine where you want to download the material and clone the repository:

```console
git clone https://github.com/simonboehme/data-visualization-intro.git
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
