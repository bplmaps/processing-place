---
title: Glossary
layout: glossary
order: 999
outputs:
  - html
theme_color_primary: "#cd3a95"
theme_color_secondary: "#cd3a95"
menu: true
---

##### Buffer

In geospatial analysis, a **buffer** is a area of a specified distance from a geographic feature. For instance, if you wanted to know whether there were any public parks within 500 feet of a highway, you might create a "buffer" layer measuring 500 feet in all directions from the highway.

##### Census tract

**Census tracts** are units of areal measurement, designed by the U.S. Census in the early twentieth century to make it easier to geographically compare different demographic variables at relatively fine-grained scales. Census tracts include between 1,200 and 8,000 people.

##### Electrostatic plotter

Popular for printing in the 1980s, **electrostatic plotters** (alson known as "drum plotters") print images by transferring electrically charged toner particles from a drum to a sheet of paper.

##### Encode

In the context of computers and computer mapping, **encoding** refers to transferring observations about the world into structured geospatial data.

##### FORTRAN

**FORTRAN** is a programming language developed by IBM in 1958 that required users to input physical "punch cards" to a computer. Between the 1960s and 1990s, computer cartographers often wrote FORTRAN code in order to make digital maps with geographic information systems software.

##### Index mosaic

In the context of aerial photography and satellite imagery, an **index mosaic** refers to a composite of all photos or images from a series.

##### Geocoding

Also known as "address matching," **geocoding** is the process of transforming descriptive geographical information—for example, a known address or a pair of latitude and longitude coordinates—into geospatial data like points, lines, or polygons.

##### Geographic coordinate pairs

**Geographic coordinate pairs**, or "latitude-longitude pairs," are pairs of numbers that locate a point on the surface of the Earth.

##### Geospatial

The term **geospatial** refers to structured, digital information about features on the surface of the Earth. Geospatial data is commonly encountered in either vector or raster format.

##### GIS (geographic information system)

First coined in the 1960s by Roger Tomlinson of the Canadian Land Survey, **GIS** refers to any software that can create, manipulate, analyze, and render geospatial data. Traditionally, GIS are self-contained software systems that can store geospatial information in structured databases and perform mathematical and geostatistical operations on them.

##### GPS (Global positioning system)

Initially funded by the Department of Defense in 1973, **GPS** is a satellite-based radio communication system that makes geolocation possible. GPS satellites contain atomic clocks that are synchronized with one another. They constantly transmit signals back and forth at the speed of light, and by measuring how long it takes for those signals to travel, computers can quickly determine geographic location in real time.

##### Hardware

In computing, **hardware** refers to the physical components of a computer. This includes things like computer chips used for memory, the monitor used to display information, and cooling fans that prevent the system from overheating. Older computers used hardware like punch card machines and magnetic tape readers.

##### Points, lines, and polygons

In the vector data model, features on the surface of the earth are encoded as either **points** (a latitude and longitude coordinate pair); **lines** (a series of connected points); or **polygons** (a series of lines that ends in the same place where it starts). The same feature in the real world could be encoded as either a point, line, or polygon, depending on the context of the data and the scale of the map. For example, in a map of Copley Square, you might want to represent the Boston Public Library (BPL) as a polygon, since you’re zoomed in fairly close. In a map of the entire city of Boston, that level of detail isn’t necessary, so you might just encode the BPL as a point.

##### Pixel

**Pixels** are the smallest unit of illuminated area on a display screen (such as a computer screen). By extension, they are also the smallest geographic unit in raster data. Since raster data can be generated at different scales, the pixels in one raster dataset could correspond to 1 meter, while the pixels in a different raster dataset could correspond to 100 meters.

##### Punched cards

Originally created in the late 19th century, **punched cards** were a common method in the 20th century for inputting structured data to a computer. 

##### Raster

The **raster** data model encodes geospatial data in a continuous grid of regularly sized pixels. Each pixel can contain a single value, or in the case of satellite imagery, multiple values that have been combined mathematically. Raster data layers may be the result of analytical processing, satellite imaging, or map digitization.

##### Remote sensing

**Remote sensing** describes technologies that can capture information about geographic features on the surface of the Earth at a distance. A remote sensing technology could be a modern-day satellite, or a balloon with a camera attached to the bottom.

##### Software

In computing, **software** refers to any digital program that is used by a computer. GIS programs like [QGIS](https://www.qgis.org/), as well as Python libraries like [GDAL](https://gdal.org/en/latest/), are examples of software.

##### Suitability analysis

In geographic research, a **suitability analysis** is a workflow that helps to determine whether a particular area is well-suited to a particular use. These kinds of analyses can be wide ranging, and could include a city government identifying the best location for a new park or a grocery store chain figuring out where to put their next store.

##### Table join

In geospatial theory, a table join is the process of correlating descriptive, tabular information (such as a spreadsheet) with corresponding vector data (such as points, lines, or polygons).

##### Urban renewal

Between the 1950s and the 1970s, the U.S. federal government gave money to municipal governments who wanted to demolish and rebuild so-called "slums" or "blighted" neighborhoods in their cities and towns. At the national scale, this program---commonly known as **urban renewal**---overwhelmingly displaced poorer people, immigrants, and people of color.

##### Variable

A **variable** is any characteristic or quality associated with a geographic feature. Variables can refer to qualitative (descriptive) or quantitative (countable) information.

##### Vector

The **vector** data model encodes geographic features as coordinate pairs or series of coordinate pairs. See **points, lines, and polygons** for a more detailed description of how.