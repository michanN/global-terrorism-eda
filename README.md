# Global Terrorism Database Analysis

### Table of Contents

1. [Installation](#installation)
2. [Project Motivation](#motivation)
3. [File Descriptions](#files)
4. [Results](#results)
5. [Licensing, Authors, and Acknowledgements](#licensing)

## Installation <a name="installation"></a>
The only external libraries necessary to run this code, beyond the Anaconda distribution of Python, are Plotly and Cartopy.
</br>Instructions on how to install Plotly can be found [here](https://plot.ly/python/getting-started/).
</br>Instructions on how to install Cartopy can be found [here](https://scitools.org.uk/cartopy/docs/v0.16/installing.html#installing).

## Project Motivation <a name="motivation"></a>
The purpose of this project is twofold. First, I wanted to learn to better communicate my findings through visuals. Second, I was interested in using the Global Terrorism Database (1970 - 2017) to better understand:
1. Has the number of attacks increased over the years?
2. Which regions are most affected with regards to:
    1. Number of attacks
    2. Casualties
    3. Successful/failed attacks
3. Which type of attack has been the most common and killed most people over the years?

## File Descriptions <a name="files"></a>
The following are the files available in this repository:
* `global-terrorism-analysis.ipynb` - a notebook of the analysis performed following the CRISP-DM process.
* `globalterrorism_0718dist.csv` - csv file that contains the data.
* `/BG/BM.jpg` and `/BG/BM_high.png` - background images used for plots.
* `attacks3.mp4` - video generated that shows attacks on a global map.

## Results <a name="results"></a>
This analysis shows an increase in attacks as well as people affected over the years. This is most evident in the Middle East, Sub-Saharan Africa, and South Asia.

With 81,976 attacks and 156,924 people killed bombing has without a doubt been the most frequently used method as well as the second most deadly attack behind armed assault which has killed 159,799.

A more detailed discussion can be found at the post available [here](https://medium.com/@michel.naslund/a-journey-through-the-global-terrorism-database-ce35076d5289).

## Licensing, Authors, Acknowledgements<a name="licensing"></a>
Thank you to START and Kaggle.com for the data. You can find the Licensing for the data and other descriptive information at the link available [here](https://www.kaggle.com/START-UMD/gtd).
</br>
</br>A big shoutout to Mat Leonard for writing this [blog post](https://medium.com/udacity/creating-map-animations-with-python-97e24040f17b). This post made it possible for me to create the video showing attacks around the world.
</br>
</br>
Otherwise, feel free to use the code here as you would like!