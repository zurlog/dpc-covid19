# Exploratory Analysis of COVID-19 Italian Data

[![Made withJupyter][jupyter-shield]][jupyter-url]
[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Issues][issues-shield]][issues-url]
[![LinkedIn][linkedin-shield]][linkedin-url]




As a Master's student, I am conducting an exploratory analysis of COVID-19 italian data to serve as the foundation of my Master's Thesis. The thesis aims to investigate the impact of the pandemic on businesses' bankruptcies in the Emilia-Romagna region.

In this analysis, I will explore the available COVID-19 data from the [official GitHub page]((https://github.com/pcm-dpc/COVID-19)) of the Italian Civil Protection Department. The Civil Protection Department is a government agency in Italy responsible for handling emergency situations and protecting the population from natural disasters, accidents, and other hazards.

The analysis includes data cleaning, data manipulation, and visualization to aid in further analysis and enhance the research with informative and helpful figures. Given that the Emilia-Romagna region is the subject of my thesis, special attention will be devoted to it: in this repository you will find filtered datasets to lay the groundwork for further research into the virus's economic consequences in the region.

</br>



## Data
***
The COVID-19 data used in this project is publicly available from the Italian Government's GitHub repository under CC-BY-4.0 licence. Population data<sup>[1](http://dati.istat.it/Index.aspx?DataSetCode=DCIS_POPRES1#)</sup> and *shapefiles*<sup>[2](https://www.istat.it/it/archivio/222527)</sup> are provided by the Italian National Institute of Statistics ISTAT.

## Usage
***
To run the analysis, you must have Python 3.x and the required libraries installed. The required libraries are listed and imported in the [`setup.ipynb`](https://github.com/zurlog/dpc-covid19/blob/master/scripts/setup.ipynb) notebook. 

The `dpc-covid19` repository contains the following folders:
* `scripts` that contain `Python` scripts and jupyter notebook files
* `conf`, if necessary, that contains configuration files used in scripts or jupyter notebook files
* `data`, that contains input files in the `.csv` format
* `results` that contains output files, usually in the `.csv` format 
* `figures` that contains plot files
* `reference` that contains any possibly referenced resource.


<br>
<br>


## Acknowledgments
***
*References, Inspiration, Code Snippets, etc.*

* [**DPC** - Italian COVID-19 DATA](https://github.com/pcm-dpc/COVID-19/blob/master/README_EN.md)
* [**ISTAT** - Resident Population at January 1<sup>st</sup>](http://dati.istat.it/Index.aspx?DataSetCode=DCIS_POPRES1#)
* [**ISTAT** - Boundaries of Administrative Units as of January 1<sup>st</sup>](https://gist.github.com/PurpleBooth/109311bb0361f32d87a2)



<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/zurlog/dpc-covid19.svg?style=for-the-badge
[contributors-url]: https://github.com/zurlog/dpc-covid19/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/zurlog/dpc-covid19.svg?style=for-the-badge
[forks-url]: https://github.com/zurlog/dpc-covid19/network/members
[issues-shield]: https://img.shields.io/github/issues/zurlog/dpc-covid19.svg?style=for-the-badge
[issues-url]: https://github.com/zurlog/dpc-covid19/issues
[license-shield]: https://img.shields.io/github/license/zurlog/dpc-covid19.svg?style=for-the-badge
[license-url]: https://github.com/zurlog/dpc-covid19/blob/master/LICENSE.txt
[linkedin-shield]: https://img.shields.io/badge/-LinkedIn-black.svg?style=for-the-badge&logo=linkedin&colorB=555
[linkedin-url]: https://www.linkedin.com/in/zurlogiovanni/
[product-screenshot]: images/screenshot.png
[jupyter-shield]: https://img.shields.io/badge/Made%20with-Jupyter-orange?style=for-the-badge&logo=Jupyter
[jupyter-url]: https://jupyter.org/try








