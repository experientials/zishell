
> pip3 install virtualenv
> virtualenv myenv
> source ./myenv/bin/activate
> conda install git pip
> pip install git+https://github.com/AIWintermuteAI/aXeleRate 


## Anaconda

Install [miniconda](https://docs.conda.io/en/latest/miniconda.html).

> conda create -n myenv python


Do not use Homebrew. It will assume Python 3.9 from the OS. 
Apple Tensorflow doesn't support 3.9, only Python 3.8

    brew install anaconda

Add `/usr/local/anaconda3/condabin` to PATH.


## TensorFlow 2.3.0

[aXeleRate](https://github.com/AIWintermuteAI/aXeleRate) depends on tensorflow 2.3
This cannot be installed on Mojave with pip3. Anaconda(brew install anaconda) comes with TensorFlow 2.3.0

    conda install tensorflow


## Other dependencies

    conda install axelerate



## Mac ARM

[Spinning up a Python Data Science Environment on Mac ARM](https://github.com/mwidjaja1/DSOnMacARM#spinning-up-a-python-data-science-environment-on-mac-arm).
