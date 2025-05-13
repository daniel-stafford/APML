# Advanced Python and Machine Learning

Find here the course material for the advanced course on Python programming and Machine Learning (5th, 6th, 12th, and 13th of May 2025) offered in the Transferable Skills programme ([course description](https://fortbildung.unibas.ch/courses/organizer/scientific-tools/advanced-python-and-machine-learning-300461) of the University of Basel.

Do you want to immediately dive into the course material? Check out [Renku lab](https://renkulab.io/v2/projects/samarinm/apml) and click "Launch" to run the notebooks without any installation!

<p align="center">
    <a href="https://renkulab.io/v2/projects/samarinm/apml">
        <img src="Notebooks/images/renku.jpg" width="200" class="center-img">
    </a>
</p>


## Updates

* Sunday, 4th May: Upload course material of first week and assignments.
* Monday, 5th May: Upload adjusted course material and solutions of first day.
* Tuesday, 6th May: Upload adjusted course material and solutions of second day.
* Friday, 9th May: Upload course material of second week.
* Monday, 12th May: Upload adjusted course material and solutions of third day.
* Tuesday, 13th May: Final upload of all course material after last course day.

## Set up Python

In order to set up Python on your own machine, we recommend using [Anaconda](https://www.anaconda.com/products/individual). Follow the steps outlined in our [YouTube instruction video](https://youtu.be/-RJnYbxVZTg) to install Python and getting started with the Jupyter notebooks.

If you are more advanced and/or Anaconda is already set up on your machine, you can create the course environment with the necessary libraries through the following two steps.

1. Install `mamba` (in the `base` environment). This can significantly speed up the creation of new conda environments. Do this with the following command in your terminal:

```
conda install conda-forge::mamba
```

2. Set up the new environment `APML` by running the following command in your terminal:

```
mamba env create -f environment.yml
``` 

Now, you can activate the environment via

```
conda activate APML
``` 

and start Jupyter lab with

```
jupyter lab
``` 