# A survey of optimisation methods

Materials of the talk given at [PyData Cambridge](https://www.meetup.com/PyData-Cambridge-Meetup/events/259428201/)

While mathematical optimisation is key in many domains, it is usually seen only as an addendum of other techniques,
instead of as a discipline of its own. For example, gradient descent methods, will be often studied
in the context of machine learning models (e.g. Logistic regression), but they will rarely be presented compared
to other optimisation techniques such as linear programming or genetic algorithms.

Not having optimisation as an independent subject also causes that different techniques use different terminology,
depending on the area in which they are mostly used (machine learning, operational research, engineering...).
For example, depending on the domain we can talk about objective function, cost/loss function,
utility function or energy, to refer to the same exact concept. Making it even more difficult to understand
an optimisation method in the context of the others.

This talk will go into the details of what is an optimisation problem and which are the different parts that define them.
How the problems can be different, and how to identify the best technique for each kind of problem.
The most common optimisation methods of different areas will be briefly explained, and compared to each other.
During the talk, many examples of optimisation problems will be presented, as well as different open source tools to approach them.

Marc Garcia is a senior data scientist at Tesco. He holds a master degree in AI by the Technical University of Catalonia,
and a master degree in finance from EADA business school. He is a Python fellow, a pandas core developer, a NumFOCUS ambassador,
and a co-organiser of the London Python sprints group.

## Set up

- Install [Miniconda 3.7](https://docs.conda.io/en/latest/miniconda.html)
- Open an Anaconda/UNIX terminal
- `git clone https://github.com/datapythonista/optimisation.git`
- `cd optimisation`
- `conda env create`
- `source activate optimisation` (in Windows: `conda activate optimisation`)
- `jupyter notebook`
- Open `Optimisation.ipynb` notebook
- Click the icon with the bar plot to show as slides with [RISE](https://damianavila.github.io/RISE/)

## Run online
  [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/datapythonista/optimisation.git/master)
 
 Make sure to restart the Kernel an run all the cells to get the interactive graphs.
