# web-design-challenge

This project generates a website analyzing weather data visualizations and data generated in the [Python API Challenge](https://github.com/Jagjeet/python-api-challenge).

## Prerequisites

To run this project the following tools are needed:

* Web browser
* Python (tested with v3.85, earlier versions may work as well, but have not been tested)
* Jupyter Notebooks and/or Jupyter Labs
* Anaconda is recommended though library dependencies can be installed individually as well.
* Node/npm

## Usage

* Clone the respository
* Open index.html in a web browser
* Explore the world of latitude vs other weather phenomenon

### Font Awesome

FontAwesome dependencies are included in the repo. To optionally upgrade:

* Run `npm install` to install the latest Font Awesome icons
  * Copy `node_modules/fontawesome-free/css/all.css` to `css/all.css`

### Pandas

CSV Data can be upgraded using the Jupyter notebook in `Resources/data/CSVDataExporter.ipynb`. It can then be copied into `data.html` overwriting the existing data. Note some styling may need to be readded to avoid any issues.


* Run `npm install` to install the latest Font Awesome icons
  * Copy `node_modules/fontawesome-free/css/all.css` to `css/all.css`


## Known Issues

* Currently FontAwesome files have to manually be copied from node_modules to the css directory. This could be integrated into a build process.
* Data table scrolling is not currently functioning on smaller screens

## References

* [Bootstrap 5 documentation](https://getbootstrap.com/docs/5.0/getting-started/introduction/)
* [Lorem Picsum used for placeholder images during development](https://picsum.photos/)
