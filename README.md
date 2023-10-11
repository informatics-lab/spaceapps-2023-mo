# Nasa Space Apps 2023 - Met Office, Exeter

![NASA SpaceApps Logo](nasa_spaceapps_logo.png)

* [Introduction](#introduction)
* [Resources](#resources)
  * [Challenges related to space weather, resources, and teams](#challenges-related-to-space-weather-resources-and-teams)
  * [Creche-compatible challenges](#creche-compatible-challenges)
  * [Introduction to Python for Environmental Science](#introduction-to-python-for-environmental-science)

## Introduction

This repository provides a series of tutorials on technical and data resources
for NASA Space Apps Challenge 2023, hosted in Exeter by the Joint Centre of Excellence
in Environmental Intelligence and TechExeter.

## Resources

* [2023 challenges](https://www.spaceappschallenge.org/2023/challenges/)
* [Met Office blog](https://blog.metoffice.gov.uk/2023/09/07/nasa-space-apps-challenge-is-coming-to-exeter/)
* [Exeter event](https://www.spaceappschallenge.org/2023/locations/exeter/)
  * [Teams who took part](https://www.spaceappschallenge.org/2023/locations/exeter/?tab=teams)

### Challenges related to space weather, resources, and teams

1. [Develop the Oracle of DSCOVR](https://www.spaceappschallenge.org/2023/challenges/develop-the-oracle-of-dscovr/)
   1. 2 teams chose
      1. [BANSSAB](https://www.spaceappschallenge.org/2023/find-a-team/banssab/)
         1. [Outputs](https://www.spaceappschallenge.org/2023/find-a-team/banssab/?tab=project)
      2. [Solar Storm](https://www.spaceappschallenge.org/2023/find-a-team/solar-storm/)
         1. *No outputs*
2. [Immersed in the Sounds of Space](https://www.spaceappschallenge.org/2023/challenges/immersed-in-the-sounds-of-space/)
   1. 1 team chose
      1. [Solar Sounds](https://www.spaceappschallenge.org/2023/find-a-team/solar-sounds/)
         1. Local event winners!
         2. [Outputs](https://www.spaceappschallenge.org/2023/find-a-team/solar-sounds/?tab=project)
         3. *Contained members of pre-event team [Solar Audible Experience](https://www.spaceappschallenge.org/2023/find-a-team/solar-sounds/)*
   2. Data: Solar Dynamics Observatory imagery in [`data/immersed_sounds_space/SDO/`](data/immersed_sounds_space/SDO/)
      1. Attribute as follows: ["Courtesy of NASA/SDO and the AIA, EVE, and HMI science teams."](https://sdo.gsfc.nasa.gov/data/rules.php)
      2. Data retrieval script: [`bin/download_sdo_data`](bin/download_sdo_data)
3. [Magnetic Reconnection](https://www.spaceappschallenge.org/2023/challenges/magnetic-reconnection/)
   1. *No teams participated locally*
   2. *No resources created*
4. Potentially: [Winning the Helio Big Year with Joy, Curiosity, and Science!](https://www.spaceappschallenge.org/2023/challenges/winning-the-helio-big-year-with-joy-curiosity-and-science/)
   1. *No teams participated locally*
   2. *No resources created*

### Creche-compatible challenges

The creche could possibly come up with some activities linked with these challenges:

1. [Eclipses: Perspective is Everything](https://www.spaceappschallenge.org/2023/challenges/eclipses-perspective-is-everything/)
   1. Get kids to make a game for kids to explain why not whole Earth can see given eclipse
2. [Create a Work of SARt (Synthetic Aperture Radar Art)](https://www.spaceappschallenge.org/2023/challenges/create-a-work-of-sart-synthetic-aperture-radar-art/)
   1. Craft activities - interpret SAR imagery with crayons, glitter, glue, ...
3. [Artemis II and You!](https://www.spaceappschallenge.org/2023/challenges/artemis-ii-and-you/)
   1. Get kids to create a video?
4. [Open Science Storytelling](https://www.spaceappschallenge.org/2023/challenges/open-science-storytelling/)
   1. Find a case; get children to come up with a story about it

### Introduction to Python for Environmental Science

*The following guidance is taken from the [bootcamp run before NASA Space Apps 2022](https://github.com/informatics-lab/spaceapps-2022-mo-bootcamp).*
*No bootcamp was run in 2023.*
*Nevertheless, cross-linking the previous guidance to flag resources available*
*at the link above to help with Python and environment management*

Learn about useful Python packages for working with environmental datasets and work
through some basic examples for loading and exploring different types of data.

#### Machine Learning with Weather Data

A brief introduction to machine learning and have the opportunity to work through
a simple (cloud computing) example, specifically using some readily available weather
data.

#### Introduction to Weather and Climate Datasets

A brief overview of the types of data we have available within the Met Office.
These datasets are open source, you'll have the oppertunity download and explore
this data through the example notebooks provided.
This will give you the tools to explore weather and climate data yourself.

______________________________________________________________________

We will assume you have some experience with programming langauges and ideally have a
little bit of knowledge of python.
There are a lot of excellent resources on the internet for learning python.
This short series of tutorials condenses the most important parts for working
specifically with enviromental datasets and provides an overview of tools to make
this easier.
For a more in depth understanding of python, exploring these exellent tutorials is
recommended:

* Software Carpentry: <https://swcarpentry.github.io/python-novice-inflammation/index.html>
* DataCamp: <https://www.datacamp.com/courses/intro-to-python-for-data-science>

#### Python environment set up

Some of these tutorials require some python package management, we have done this
through [Conda](https://docs.conda.io/projects/conda/en/latest/).
If you don't have Conda, [install miniconda here](https://docs.conda.io/en/latest/miniconda.html).
If you prefer other package management methods please feel free to use them.
More information about package management for each session will be contained in the
README of that folder.

#### Acknowledgements

Development of these tutorials was funded by the [Joint Centre for Excellence in Environmental Intelligence](https://jceei.org/).

![JCEEI logo](jceei_logo.png)
