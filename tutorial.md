# Building a Portfolio Site with Jupyter Book / MySt and Github Pages

## Prerequisites

1. [Anaconda](https://www.anaconda.com/download) <- Need to Sign up first
2. Visual Studio Code with [Jupyter Extension](https://marketplace.visualstudio.com/items?itemName=ms-toolsai.jupyter)
3. [Git](https://git-scm.com/install/) running on your laptop 
4. A [GitHub](https://www.github.com) account

## Setup

1. Create a folder for the project, a Conda environment and a local git repo

```shell
mkdir portfolio & cd portfolio
conda create --name portfolio
conda activate portfolio
git init
```
2. Install required packages

```shell
conda config --add channels conda-forge
conda install jupyter-book
```

3. Start

```shell
    jupyter-book init --gh-pages
```

4. Create Remote

    1. Create a new repository on github.com
    2. Add remote to your local 

``` shell
 git remote add origin git@github.com:paulusm/portfolio-demo.git
```



