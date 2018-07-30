# naive-bayes
[![npm](https://img.shields.io/badge/langage-Python-blue.svg?style=flat-square)](https://www.python.org/) [![npm](https://img.shields.io/npm/l/date-2.svg?style=flat-square)](https://github.com/touir1/Date2/blob/master/LICENSE)

A hardcoded naive bayes with python.

This project is part of the <b>#100DaysOfMLCode</b> challenge proposed By [Siraj Raval](https://twitter.com/sirajraval).

## Jupyter notebooks ##
* Hardcoded naive bayes: [naive-bayes-hardcoded.ipynb](http://nbviewer.jupyter.org/github/touir1/naive-bayes/blob/master/naive-bayes-hardcoded.ipynb).

## Dependencies ##
I'm using [pipenv](https://docs.pipenv.org/) for the dependencies. So for installing dependencies, you need to:
* _pip install pipenv_
After that you only need to execute _pipenv install_.

If you don't want to use pipenv, you can install the dependencies manually:

* [numpy](http://www.numpy.org/): _pip install numpy_
* [matplotlib](https://matplotlib.org): _pip install matplotlib_
* [pandas](https://pandas.pydata.org/): _pip install pandas_
* [ipykernel](https://ipython.readthedocs.io/en/stable/): _pip install ipykernel_
* [sklearn](http://scikit-learn.org/stable/): _pip install sklearn_
* [scipy](https://www.scipy.org/): _pip install scipy_

## How to run ##

If you are using pipenv:
* Go to the project directory
* Execute in a command promt (windows) or a terminal (linux): pipenv shell
* Execute: python -m ipykernel install --user --name=my-virtualenv-name
* Execute: jupyter notebook
* In the jupyter notebook web app, open the corresponding .ipynb file.

If you don't use pipenv:
* Execute: jupyter notebook
* In the jupyter notebook web app, open the corresponding .ipynb file.

<b>Note:</b> If you are unfamiliar with [jupyter](http://jupyter.org/) notebook, you can visit their website to learn more:
* How to install: [http://jupyter.org/install](http://jupyter.org/install).
* How to run: [https://jupyter.readthedocs.io/en/latest/running.html](https://jupyter.readthedocs.io/en/latest/running.html).
* Full documentation: [https://jupyter.org/documentation](https://jupyter.org/documentation).

## Authors ##

* Mohamed Ali Touir
  * Github: [https://github.com/touir1](https://github.com/touir1)
  * Email: [touir.mat@gmail.com](mailto:touir.mat@gmail.com)
  * Twitter: [@TouirMohamedAli](https://twitter.com/TouirMohamedAli)

## License ##

naive-bayes is published under the [MIT license](http://www.opensource.org/licenses/mit-license).

## Special thanks ##

[Siraj Raval](https://twitter.com/sirajraval) for starting the [#100DaysOfMLCode](https://twitter.com/search?q=%23100DaysOfMLCode&src=tyah) challenge.
