# Changelog for Redmine Reports

All notable changes to this project will be documented in this file.

The format is based on [Keep a Changelog](https://keepachangelog.com/en/1.0.0/),
and this project adheres to [Semantic Versioning](https://semver.org/spec/v2.0.0.html).

## 0.2.1 - 2023-08-18

### Fixed

* scaling and stacking as described in 0.1.2 by merging from there

## 0.2.0 - 2023-07-30

### Changed

* color scheme to meet the look & feel of the new omnia theme

## 0.1.2 - 2023-08-18

### Fixed

* scales to be displayed as integer
* lost stacking of bars

## 0.1.1 - 2023-04-06

### Changed

* loading of javascript lib for chart.js to support Redmine 5 and 4
* integration of tableau.ClassicCyclic13 color scheme

### Deleted

* javascript library chartjs-plugin-colorschemes v0.4.0 due to missing
  chart.js 3.x support

## 0.1.0 - 2021-10-11

### Added

* chartjs colorschemes plugin

### Changed

* horizontal bar charts to vertical bar charts
* chart layout into a two column layout having tow bar charts side by side
* the color scheme to tableau.ClassicCyclic13
