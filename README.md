# Vejle Flood Risk Analysis
## About the Project
This project investigates flood vulnerability and urban development in Vejle, Denmark between 1925 and 2025 using spatial analysis in R.
The analysis combines Danish BBR building data, elevation raster data, and GIS-based hotspot analysis to examine whether newer urban development has increasingly expanded into flood-prone areas.
This project is developed as part of the Spatial Analytics course examination at Aarhus Univers

### Built with
* R
* sf
* terra
* dplyr
* ggplot2
* tidyr
* httr

## Getting Started
To run the project locally, clone the repository and run the scripts in the `src/` folder.

Required software:
* R
* RStudio

Required R packages:
```r
install.packages(c(
  "sf",
  "terra",
  "dplyr",
  "ggplot2",
  "tidyr",
  "httr"
))
```

### Installation
1. Clone the repository
```sh
git clone https://github.com/YOUR_USERNAME/vejle-flood-risk-analysis.git
```

2. Open the project in RStudio

3. Run the scripts located in the `src/` folder in the following order:

   1. `preprocessing_bbr.Rmd`
   2. `preprocessing_municipalities_polygon.Rmd`
   3. `preprocessing_elevation.Rmd`
   4. `final_analysis.Rmd`

4. Processed datasets will automatically be saved in the `data/` folder, while generated maps, tables, and figures will be saved in the `out/` folder.

## License
Distributed under the MIT License. See `LICENSE.txt` for more information.

## Contact
Line Sandby - 202205032@post.au.dk

Project Link: [https://github.com/YOUR_USERNAME/vejle-flood-risk-analysis](https://github.com/LineSandby/vejle-flood-risk-analysis)
