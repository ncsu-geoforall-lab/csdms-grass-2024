<!-- Links -->

[jhub]: https://csdms.colorado.edu/wiki/JupyterHub
[badge]: https://img.shields.io/badge/Run%20on-EarthscapeHub-orange
[jhub-link]: https://lab.openearthscape.org/hub/user-redirect/
[jhub-info]: https://csdms.colorado.edu/wiki/JupyterHub



# Coastal evolution analysis and inundation modeling with GRASS GIS (CSDMS Workshop 2024)

This is a set of Jupyter Notebooks for a workshop at CSDMS's 2024 Annual Meeting.

## How to run these notebooks

The notebooks can be run locally
if users installs GRASS GIS along with Jupyter Lab, folium, and a `git` client on their computer.
All notebooks are also available to run
on [EarthscapeHub][jhub].
Click this button:

[![Run on EarthscapeHub][badge]][jhub-link]

to open the lessons directly on the EarthscapeHub *lab* instance!

> **Note:** The EarthscapeHub *lab* instance is password-protected.
  Please contact your instructor about obtaining a login,
  or visit [this][jhub-info] CSDMS wiki page for more information.


Once you are in [EarthscapeHub][jhub-link], open a terminal and clone this repository using:

```
git clone https://github.com/ncsu-geoforall-lab/csdms-grass-2024.git
```


## Workshop Agenda

**Part 1 (10 min): _Quick Introductions_**
- What is GRASS and why use it

**Part 2 (50 min): _Getting Started with GRASS and LiDAR data_**

- [Notebook 1: Getting Started](./01_Getting_Started.ipynb)

- [Notebook 2: DEM Creation and Visualization](./02_Create_and_Visualize_DEMs.ipynb)

**Break (10 min)**

**Part 3 (50 min): _Deriving Shorelines, Dune Migration and Simple Inundation Modeling_**

- [Notebook 3: Deriving Shorelines](./03_Shoreline_Derivation.ipynb)

- [Notebook 4: Dune Migration](./04_Dune_Migration.ipynb)

- [Notebook 5: Simple Inundation Modeling](./05_Inundation.ipynb)


## Authors
<p float="left">
<img src="img/Pratikshya_Regmi.jpg" title="Pratikshya Regmi" width=150>&nbsp;&nbsp;
<img src="img/Caitlin_Haedrich.jpg" title="Caitlin Haedrich" width=150>
</p>

* Pratikshya Regmi, NCSU Center for Geospatial Analytics
* Caitlin Haedrich, NCSU Center for Geospatial Analytics

<img src="img/ncsu_cga.png" title="Center for Geospatial Analytics at NC State" width=400>

## License

This material is dual licensed under GNU FDL 1.3 and CC BY-SA 4.0.

## Acknowledgement

This workshop was developed and delivered with the support of the U.S. National Science Foundation, award [2303651](https://www.nsf.gov/awardsearch/showAward?AWD_ID=2303651).
