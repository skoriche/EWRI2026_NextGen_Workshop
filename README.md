# 2026 World Environmental & Water Resources Congress - EWRI Technical Workshop: Application of NOAA Next Generation Water Resource Modeling Framework for Hydrological Modeling

[![Workshop](https://img.shields.io/badge/Workshop-EWRI--Congress%20Technical%20Workshop-blue?labelColor=555)](https://www.cuahsi.org/summer-institute)
[![NextGen](https://img.shields.io/badge/NextGen-Framework-green.svg)](https://github.com/NOAA-OWP/ngen)
[![NOAA](https://img.shields.io/badge/NOAA-CIROH-2496ED.svg)](https://ciroh.ua.edu/)
[![NGIAB](https://img.shields.io/badge/NGIAB-Ecosystem-2496ED.svg)](https://ngiab.ciroh.org/)

* **📅 Date**: Sunday, April 26, 2025
* **⏰ Time**: 01:00 – 5:00 pm CT
* **📍 Location**: Mobile Convention Center | 1 South Water Street, Mobile, AL 36602 | Room: 203 A

---

## 👥 Instructors

This `GitHub repository`, which serves as the central hub for all workshop materials, tools, detailed instructions, pre-conference and other relevant information, was prepared and is maintained by [Sifan A. Koriche](https://github.com/skoriche) and [Josh Cunningham](https://github.com/JoshCu).

---

## 🎯 Workshop Purpose

This comprehensive, half-day workshop provides a deep dive into the Next-Generation Water Resources Modeling Framework (NextGen), a model-agnostic and standards-based software tool that facilitates model interoperability. The workshop is split into two parts: an exploration of the broader NextGen Framework and a hands-on session on hydrological model calibration within the NextGen In a Box (NGIAB) ecosystem. This workshop is highly relevant to professionals and students interested in US operational hydrological forecasting pipelines. You'll gain practical experience using open-source tools with pre-configured datasets.

### What You'll Learn

- ✅ **Model Calibration Fundamentals** - Theory and practice of improving hydrological model accuracy
- ✅ **Hands-on NextGen Experience** - Complete calibration workflows using real tools and data
- ✅ **Parameter Management** - Share and collaborate on calibrated parameters effectively
- ✅ **Best Practices** - Learn from experts and discuss real-world challenges

<details>
  <summary>
    <h2>Workshop Workflow</h2>
  </summary>

![Workshop Workflow](./Information/figures/Workflow-Figure.png)

*Figure 1: End-to-end visual representation of the NextGen In A Box (NGIAB) ecosystem's hydrological simulation workflow, detailing phases for data preparation, model simulation, parameter calibration, and output analysis steps. 1) Python CLI data preparation modules for NGIAB, 2a) NGIAB Docker image, 2b) NGIAB-cal Docker image + Python CLI for Calibration, and 3) TEEHR evaluation + visualizer*

*[graphics by Sifan A. Koriche]*

</details>

## 🛠️ Prerequisites

**Data**
- Download workshop data:
    - Choctawhatchee River Near Newton, AL (USGS-02361000) -- [Click Here to Download](https://ciroh-awi-ewri-data.s3.us-east-1.amazonaws.com/EWRI26_USGS_02361000.tar.gz)
    - Sipsey Fork Near Grayson, AL (USGS-02450250) -- [Click Here to Download](https://ciroh-awi-ewri-data.s3.us-east-1.amazonaws.com/EWRI26_USGS_02450250.tar.gz)
    - Provo River Near Woodland, UT (USGS-10154200) -- [Click Here to Download](https://ciroh-awi-ewri-data.s3.us-east-1.amazonaws.com/EWRI26_USGS_10154200.tar.gz)
 - Or Create your own using this command `uvx ngiab-prep -i gage-02450250 --start 2007-10-01 --end 2016-09-30 --source aorc -sfr -o EWRI26_USGS_02450250`


**Minimum Requirements:**
- [Docker](https://docs.docker.com/engine/install/) (for running containerized tools)
- [UV](https://docs.astral.sh/uv/getting-started/installation/) (Python package manager)

> 📋 **For complete setup instructions and requirements**: [Pre-Workshop Checklist](../../wiki/Pre-Workshop-Checklist)


---

## 📚 Workshop Resources

- [NGIAB Website](https://ngiab.ciroh.org)
- [NGIAB 101 Training Module](https://docs.ciroh.org/training-NGIAB-101/)
- [Development Setup](../../wiki/Development-Setup) - Modify and extend tools

<details>
  <summary>
<h2>🧩 The NGIAB Ecosystem</h2>
  </summary>


| Tool | Purpose | Type |
|------|---------|------|
| [**NGIAB-Data-Preprocess**](https://github.com/CIROH-UA/NGIAB_data_preprocess/tree/a6dd733f637cb56ce42a43204db69e3cefa2a61a) | Prepare hydrofabric and forcing data | Python CLI |
| [**NGIAB-Cal**](https://github.com/CIROH-UA/ngiab-cal/tree/19d5ded2ae365f333b0ac6a971c2e7028c7014a4) | Configure and run calibration | Python CLI |
| [**NGIAB**](https://github.com/CIROH-UA/NGIAB-CloudInfra/tree/41570096a5273393f2e3a0121d02e643bc6ce34d) | NextGen framework container | Docker Image |
| [**NGEN-Cal**](https://github.com/CIROH-UA/ngen-cal/tree/f450a9d2e992adf0e110711c559551623b73932d) | Calibration algorithms and analysis | Docker Image |

> 🔧 **Learn more**: [Tools and Modules](../../wiki/Tools-and-Modules)  

</details>


---


## 🤝 Getting Help

- **During the Workshop**: Ask instructors and assistants
- **Common Issues**: See [Troubleshooting Guide](../../wiki/Troubleshooting)
- **Questions/Bugs**: [Open GitHub Issues](https://github.com/skoriche/EWRI2026_NextGen_Workshop/issues)
- **Email**: [sakoriche@ua.edu](mailto:sakoriche@ua.edu), [jcunningham8@ua.edu](mailto:jcunningham8@ua.edu)
