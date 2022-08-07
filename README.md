# *Exoplanet hunting using Machine Learning*

![CartwheelGalaxy](https://user-images.githubusercontent.com/90423812/183287729-c65e66cf-4222-44ab-b363-4c597641bb0c.png)

## What are Exoplanets?

Exoplanets are planets beyond our own solar system. Thousands have been discovered in the past two decades, mostly with NASA’s Kepler Space Telescope.

## NASA Kepler Mission

The Kepler Mission was specifically designed to survey our region of the Milky Way galaxy to discover hundreds of Earth-size and smaller planets in or near the habitable zone and determine the fraction of the hundreds of billions of stars in our galaxy that might have such planets

Kepler was very sensitive to changes in flux (light intensity). Periodically, data was beamed down to Earth and after a bit of de-noising, they were open-sourced via the **[Mikulski Archive](https://archive.stsci.edu/k2/)**.

## The Search for Exoplanets

We may have imagined life on other planets in books and film for centuries, but detecting actual exoplanets is a recent phenomenon. Planets on their own emit very little if any light. We can only see Jupiter or Venus in the night sky because they reflect the sun’s light. If we were to look at an exoplanet (the nearest one is over 4 light-years away), it would be very close to a brilliantly lit star, making the planet impossible to see.

Scientists discovered a very efficient way to study these occurrences; planets themselves do not emit light, but the stars around which they orbit do. Considering this fact into account scientists at NASA developed a method which they called Transit method in which a digital-camera-like technology is used to detect and measure tiny dips in a star’s brightness as a planet crosses in front of the star With observations of transiting planets, astronomers can calculate the ratio of a planet’s radius to that of its star — essentially the size of the planet’s shadow — and with that ratio, they can calculate the planet’s size.
Kepler Space Telescope’s primary method of searching for planets was the “Transit” method.

Transit method: In the diagram below, a star is orbited by a planet. From the graph, it is visible that the starlight intensity drops because it is partially obscured by the planet, given our position. The starlight rises back to its original value once the planets crosses in front of the star.

![motion](https://user-images.githubusercontent.com/90423812/183286971-b65f0a6d-980f-4244-a3ca-9c07eb858d5d.gif)

## The Data

The `.csv` files are hosted on kaggle, where the description of the datasets can also be found.

1. **[Exoplanet Hunting in Deep Space](https://www.kaggle.com/datasets/keplersmachines/kepler-labelled-time-series-data)**
2. **[Kepler Exoplanet Search Results](https://www.kaggle.com/datasets/nasa/kepler-exoplanet-search-results)**

# Issues to note:

On download, the datasets are **unnormalised**. 
