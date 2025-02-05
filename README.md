# Plant-Growth-Monitoring-System
### Group: Sparkling

This project aims to measure and analyze plant growth by detecting the area of plant leaves in images taken under different conditions (No Control and Water Controlled). The script utilizes Python libraries such as OpenCV, NumPy, OS, and Matplotlib to process and visualize plant growth data. The project is designed to be executed in a Jupyter Notebook within the Anaconda Navigator environment.

## Overview

This project consists of Python scripts that process images of plant leaves to:

- Count the number of green pixels representing plant area.
- Detect and measure the leaf area in the images.
- Compare plant growth under two different conditions: **No Control** and **Water Controlled**.

The script works by using image processing techniques such as color detection in the HSV color space to isolate the plant leaves and then measure their area.

## Installation

Before using this project, ensure that you have the following installed:

- **Anaconda Navigator**: Install Anaconda from [here](https://www.anaconda.com/products/distribution).
- **Jupyter Notebook**: It comes pre-installed with Anaconda, so no need to install it separately.
- **Dependencies**: Open a terminal in Anaconda Navigator and create a new environment or use an existing one. Install the necessary dependencies by running the following command in the terminal:

```bash
conda install opencv numpy matplotlib
```

**or** Alternatively, you can use the following **pip** command:

```bash
pip install opencv-python numpy matplotlib
```

## Usage

Clone the Repository: Clone or download the repository containing the project files to your local machine.

Open Jupyter Notebook:

- Launch Anaconda Navigator.
- Open Jupyter Notebook from the Anaconda Navigator interface.
- Navigate to the project folder in Jupyter Notebook.
- Open the Notebook: Open the .ipynb notebook file (e.g., plantCount.ipynb) in Jupyter Notebook.
- Run the Code: In the notebook, run each cell in sequence to process the images and visualize the plant growth data.

## Steps in Jupyter Notebook

- Import necessary libraries (cv2, numpy, os, matplotlib).
- Define and call functions to process the plant images.
- Display the growth data and plot graphs.

## Folder Structure
The folder structure should be as follows:

PlantSelected/
    ├── NoControls/
    │   ├── 01_Morning.jpg
    │   └── ...
    └── WaterControls/
        ├── 01_Morning.jpg
        └── ...

- **NoControls/:** Contains images of plants grown without any water control.
- **WaterControls/:** Contains images of plants grown under water-controlled conditions.