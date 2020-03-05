
In this repo, I compare the numerical convergence rates of Gradient Descent, Newton-Raphson and The Method of Scoring in implementing MLE of a parameter of Weibull distributed data.  

There is a Jupyter Notebook (weibull_mle.ipynb). It can be viewed on GitHub, but GitHub may not render some of the LaTeX correctly.  

To run on you computer, install pipenv. Clone the repo. Go into the repo. Run `pipenv install` to install the environment. Run `pipenv shell` and then `python -m ipykernel install --user --name num-methods-MLE --display-name num-methods-MLE` to connect the environment to Jupyter. Exit the subshell with `exit`. The environment num-methods-MLE will appear as a kernel in Jupyter.