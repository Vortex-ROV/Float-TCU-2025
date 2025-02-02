# Vertical Profiling Float TCU Software

This repository houses the code that powers the Vertical Profiling Float’s Topside Control Unit (TCU). It handles sensor data acquisition, graphing, and communication, ensuring precise water-column profiling, efficient data collection, and smooth competition operations.

---

## Table of Contents

- [Introduction](#introduction)
- [Installation](#installation)
- [Repository Structure](#repository-structure)

---

## Introduction

The **Vertical Profiling Float** is designed to collect essential data from various sensors as it traverses different depths in the water column. The TCU is the topside interface that processes sensor readings, provides real-time graphing for quick analysis, and communicates with other control systems. It enables competition teams and research groups to monitor underwater environments accurately and efficiently.


## Installation

1. **Clone the Repository**  
   ```bash
   git clone https://github.com/YourOrg/VerticalProfilingFloat-TCU.git
   cd VerticalProfilingFloat-TCU
   ```
2. **Create and Activate a Virtual Environment:**

   It's a good practice to use a virtual environment to manage dependencies. Run the following commands to create and activate one:

   - On macOS/Linux:
     ```bash
     python3 -m venv venv
     source venv/bin/activate
     ```
   - On Windows:
     ```bash
     python -m venv venv
     venv\Scripts\activate
     ```
3. **Install Packaged Dependencies:**
   ```bash
   pip install .
   ```
4. **Run the TCU Software:**
   ```bash
   python main.py


## Repository Structure

- **`/src`:** Core source code for communication, control, and data processing.
- **`/tests`:** Test cases to validate the software's functionality and performance.
- **`main.py`:** Main script used to launch the TCU.
- **`pyproject.toml`:** Configuration file for packaging TCU code.
