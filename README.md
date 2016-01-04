Chinese Tracker
===============

Based on synox's [open life tracker](https://synox.github.io/open-life-tracker/app/)

`#`Hashtags with `:values` enable tracking progress:

    Spoke #chinese:2hr with my wife
    
    Spoke #chinese:1hr in a meeting today
    
Changes made between synox's original and mine:
- Removed delete all funciton - don't want someone to come along and wipe my data!

---

From the original README:

Try the [Demo Application](https://synox.github.io/open-life-tracker/app/)
## Installation
1. Copy the `app` directory to your webspace. 
2. Make sure the file offline.appcache is served with mime-type `text/cache-manifest`. There is a `.htaccess` file for apache.
3. Access with a modern mobile or desktop browser. 

## Status
This software is still under development. Be safe and export your entries every few weeks or month. 

## Build and test
If you make changes, that's how you build it. [npm](https://nodejs.org/download/) installation required.

    npm install
    npm test
    ./build

## Features
- Hashtags with values using `:` or `=` example: `#distance:15km #coolness=55`
- Chart with zooming (thanks to https://github.com/n3-charts/line-chart/)
- Responsive design, mobile first
- Local storage, not sync
- Import/Export with json or base64

To do: 
- more unit tests
- test with large number of entries
  
## Used JS libraries
Base:
 * http://angularjs.org/
 * http://getbootstrap.com/
 * http://jquery.com/
 
Data handling:
 * https://github.com/lodash/lodash

Charts:
 * https://github.com/n3-charts/line-chart
 * http://d3js.org/



# License

GPLv3
