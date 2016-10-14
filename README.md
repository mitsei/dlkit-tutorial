Basic DLKit tutorial, to run in Jupyter Notebook (formerly iPython Notebook).

$ pip install -r requirements.txt
$ git submodule init
$ git submodule update --init --recursive

You'll also need to create three simple files and put them into the `dlkit_edx`
directory.

`configs.py`:
    from tutorial_configs.configs import *

`handcar_configs.py`:
    from tutorial_configs.handcar_configs import *

`registry.py`:
    from tutorial_configs.registry import *

Then, to open the notebook:

$ jupyter notebook

Open `DLKit Tutorial` in your browser (http://localhost:8888/tree).

Note that all data generated with this tutorial is saved in JSON files to your harddrive, in a folder called `tutorial-data`, sibling to this `README`. If you ever want to start over, just delete that folder and all its contents.
