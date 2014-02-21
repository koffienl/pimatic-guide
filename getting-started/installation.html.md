---
title: Installation
layout: guide
tags: ['guide', page']
guideOrder: 10
---
First you need to install [node.js](http://nodejs.org) that comes with the package manager 
[npm](https://npmjs.org/). Then you can run

    mkdir pimatic-app
    npm install pimatic --prefix pimatic-app

to install the pimatic framework.

Copy the default config file:

    cd pimatic-app
    cp ./node_modules/pimatic/config_default.json ./config.json

You should end up with this in your `pimatic-app` directory:

<table class="table file-listing">
<tr><td>`config.json`</td>				       <td>the config file</td></tr>
<tr><td>`node_modules`</td>				       <td>directory for the framework and plugins</td></tr>
<tr><td>`node_modules/pimatic`</td>			   <td>the pimatic framework files</td></tr>
</table>