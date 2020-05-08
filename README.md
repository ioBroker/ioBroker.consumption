![Logo](admin/consumption.png)
# ioBroker.consumption

[![NPM version](http://img.shields.io/npm/v/iobroker.consumption.svg)](https://www.npmjs.com/package/iobroker.consumption)
[![Downloads](https://img.shields.io/npm/dm/iobroker.consumption.svg)](https://www.npmjs.com/package/iobroker.consumption)
[![Dependency Status](https://img.shields.io/david/bluefox/iobroker.consumption.svg)](https://david-dm.org/bluefox/iobroker.consumption)
[![Known Vulnerabilities](https://snyk.io/test/github/bluefox/ioBroker.consumption/badge.svg)](https://snyk.io/test/github/bluefox/ioBroker.consumption)

[![NPM](https://nodei.co/npm/iobroker.consumption.png?downloads=true)](https://nodei.co/npm/iobroker.consumption/)

**Tests:**: [![Travis-CI](http://img.shields.io/travis/bluefox/ioBroker.consumption/master.svg)](https://travis-ci.org/bluefox/ioBroker.consumption)

## consumption adapter for ioBroker
Calculates consumption for defined sensors and resources

## Structure of the stations
- Stations
  - Station01
    - energy (kWh / €)
        - sensor1
        - sensorX
        - price
    - heat (kWh / €)
        - sensor1
        - sensorX
        - price
    - water (L / €)
        - sensor1
        - sensorX
        - price    
    - whatever (Unit / €)
        - sensor1
        - sensorX
        - sensorX_price
        - price  
    
## Tasks
1. Generate all stations with all variables with enabled statistics and sql settings
2. Calculate actual prices for one station

## Update echarts
Go to https://www.echartsjs.com/en/builder.html 
Select:
- Chart: bar, line, pie, heatmap, 
- Coordinate Systems: grid
- Component: title, legend, tooltip, MarkPoint, MarkArea, VisualMap, Toolbox
- Others: SVG Renderer, Utilities, Code Compression


## Changelog
### 0.1.7 (2020-05-08)
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
