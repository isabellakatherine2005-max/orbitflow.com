Orbit Analytics

A web application for campaign data analysis and performance monitoring.
Overview

Orbit Analytics is a client-side web application designed to process campaign mailing data and transform it into visual performance metrics.

The application allows users to upload campaign data, analyze delivery results, compare campaigns, and export reports.

Features

* Campaign data analysis through CSV files
* Dashboard with campaign performance metrics
* Delivery and failure status breakdown
* Campaign comparison
* Campaign history
* Campaign generator
* CSV export
* PDF report generation
* User profile management
* Authentication interface
* Responsive UI
* Light and dark mode

Data Processing

The application processes campaign data directly in the browser.

Supported data includes fields such as:

* CNPJ
* Branch
* Sales channel
* Customer name
* WhatsApp / phone
* Purchase value / revenue

The application normalizes column names and supports different header aliases when processing imported files.

## Metrics

The analysis provides metrics including:

* Total customers
* Successful deliveries
* Failed deliveries
* Delivered messages
* Sent messages
* Viewed messages
* Responses
* Undelivered messages
* Meta-related failures
* Generic failures

Campaign Comparison

The comparison module allows two campaign analyses to be evaluated through visual charts, including success rates and total volume.

Export

Analysis results can be exported in:

* CSV format
* PDF format

Tech Stack

Frontend**

* HTML5
* CSS3
* JavaScript

Libraries
Chart.js
jsPDF
SheetJS / XLSX

Architecture

The application performs data processing on the client side, allowing campaign files to be imported and analyzed directly in the browser.
The interface is organized into independent modules, including:

* Dashboard
* Campaign Analysis
* Campaign Generator
* History
* User Profile

Project Structure
The project is primarily composed of frontend assets and JavaScript modules responsible for:

* UI rendering
* File processing
* Data normalization
* Campaign analysis
* Chart generation
* Data export
* User interactions

Purpose

The project was developed to demonstrate practical skills in frontend development, data processing, visualization, and building interactive web applications.


