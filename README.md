# Running Intermine web services via Binder

[![Binder](https://beta.mybinder.org/badge.svg)](https://beta.mybinder.org/v2/gh/fomightez/intermine-binder/master?filepath=index.ipynb)

Intermine Web Services available in a Jupyter environment running via the Binder service.

Click any `launch binder` badge on this page to run code that takes advantage of Intermine Web Services inside your browser.

----

Getting Started
---------------

See:
* a [Guide to getting started with using Intermine sites and Jupyter using MyBinder-served Jupyter notebooks](https://github.com/fomightez/guide_to_intermine-binder).


Background
----------

InterMine provides programmatic access to its features via [web services](http://intermine.readthedocs.io/en/latest/web-services/). This repository is set up to make use of the Intermine web services via active Jupyter sessions served from [MyBinder.org](https://mybinder.org/).

***Clarifying Attribution: I, Wayne, am not involved in the Intermine web services or Binder system software at all. Those listed among the resources noted here are the respective developers. See their materials. I simply set up this repository to make the Intermine web services useable without installation/Python 2 vs 3 headaches.***

Technical Details
-----------------

This repository is set up to make use of the binder service offered by [MyBinder.org](https://mybinder.org/). See their site or [here](https://github.com/fomightez/guide_to_intermine-binder) for more information about Binder.

Chances are good that this repository I have set up is enough to get you started if you want to use Python and Intermine. The [`requirements.txt file`](https://github.com/fomightez/intermine-binder/blob/master/requirements.txt) has some of the main popular modules and you can always use `!pip install` followed by the module name in a cell within an active notebook to install additional modules into that session. Advanced users will most likely to set up their own Binder repository to specify certain modules to already be there upon launch. See [here](https://github.com/fomightez/guide_to_intermine-binder/blob/master/part_2.md#mybinderorgbinder-and-github) for more on adapting repositories to your needs. You may wish to start with a 'fork' of this one.

Click this button below to begin using Intermine web services via Binder:

[![Binder](https://beta.mybinder.org/badge.svg)](https://beta.mybinder.org/v2/gh/fomightez/intermine-binder/master?filepath=index.ipynb)
