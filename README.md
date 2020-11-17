![Logo](admin/consumption.png)
# ioBroker.consumption

[![NPM version](http://img.shields.io/npm/v/iobroker.consumption.svg)](https://www.npmjs.com/package/iobroker.consumption)
[![Downloads](https://img.shields.io/npm/dm/iobroker.consumption.svg)](https://www.npmjs.com/package/iobroker.consumption)
[![Dependency Status](https://img.shields.io/david/bluefox/iobroker.consumption.svg)](https://david-dm.org/bluefox/iobroker.consumption)
[![Known Vulnerabilities](https://snyk.io/test/github/bluefox/ioBroker.consumption/badge.svg)](https://snyk.io/test/github/bluefox/ioBroker.consumption)

[![NPM](https://nodei.co/npm/iobroker.consumption.png?downloads=true)](https://nodei.co/npm/iobroker.consumption/)

## Consumption adapter for ioBroker
Calculates consumption for defined sensors and resources.

You can define different resources, like water, heating, electricity and make an analysis in vis with it.

4 different analysis types are implemented:
- Plan - Actual consumption in €/$ in this year compared with planned values and compared with previous year.
- Donut - Comparision between sensors or resources in form of pie/donut diagram
- Stack - Monthly consumption of every sensor and resource compared with data from previous year in form of stack bar diagram.
- Heat map - Hourly consumption in this year for resources 
- Table - Monthly consumption of every sensor and resource compared with previous year in form of table  

## Requirements
Adapter requires the my-SQL or postgres SQL DB and ioBroker.sql adapter to be installed (It will be automatically installed)
It should work with SQLite too, but it is not recommended because of performance.
 
MS-SQL is not yet supported, but could be easily implemented if required. 

**Adapter is yet beta.**
    
**Free edition supports only 4 sensors and only one station.** 
To support more sensors or stations you need a valid license. Request it under info@iobroker.com.   
    
## Update echarts (for developer)
Go to https://echarts.apache.org/en/builder.html
Select:
- Chart: bar, line, pie, heat-map, 
- Coordinate Systems: grid
- Component: title, legend, tooltip, MarkPoint, MarkArea, VisualMap, Toolbox
- Others: SVG Renderer, Utilities, Code Compression

## ToDo
- Export data as PDF
- More than one station.

## Changelog
### 0.4.7 (2020-11-16)
* (ioBroker) Implemented the combine by unit

### 0.4.3 (2020-09-11)
* (ioBroker) Fixed the layout in firefox

### 0.4.1 (2020-06-13)
* (ioBroker) Ignore nulls and zeros

### 0.3.4 (2020-06-05)
* (ioBroker) Added possibility to define the station

### 0.3.2 (2020-05-29)
* (ioBroker) Fixed the units for heat-map

### 0.3.0 (2020-05-18)
* (ioBroker) Calculate plan only in euro

### 0.2.7 (2020-05-16)
* (ioBroker) Set index for every sensor

### 0.1.6 (2020-05-03)
* (ioBroker) Implement planning start from 

### 0.1.4 (2020-05-03)
* (ioBroker) Make widget compatible with older devices
* (ioBroker) Added price for every sensor

### 0.1.2
* (ioBroker) finished

### 0.0.2
* (ioBroker) initial release

## License

Commercial license.

(c) Copyright 2020 Bluefox <dogafox@gmail.com>, all rights reserved.

This license is a legal agreement between you and ioBroker GmbH (“ioBroker”) for the use of ioBroker.consumption adapter (the “Software”).
By downloading of ioBroker.consumption adapter you agree to be bound by the terms and conditions of this license.
ioBroker GmbH reserves the right to alter this agreement at any time, for any reason, without notice.

## Permitted Use
One license grants the right to perform one installation of the Software.
Each additional installation of the Software requires an additional purchased license.
Basically, if you need one license for ExpressionEngine, you also need one license for the Software.
