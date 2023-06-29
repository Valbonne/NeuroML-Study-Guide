# NeuroML-Study-Guide
A set of notebooks designed specifically for neuroscientists to facilitate an easy understanding of machine learning concepts.

**Guide to Use**:

1. Clone or download this repository
2. Navigate to the repository i.e. cd into the repository
3. Execute the following Docker command:

	`` docker run -it --rm  -v $PWD:/home/neuro/test -p 8888:8888 satra/ibro-workshop-2017 ``

4. Next, initiate Jupyter with this command:

	`` $ jupyter-notebook --ip=* ``

5. You can now access the notebooks by opening the provided URL in a local browser.

**Main Resources**:
 - [scikit-learn user guide](http://scikit-learn.org/stable/user_guide.html)
 - [Monte Lunacek tutorial](https://github.com/mlunacek/meetup_data_science_2016)
 - [Jake Vanderplas tutorial](https://github.com/jakevdp/sklearn_tutorial)