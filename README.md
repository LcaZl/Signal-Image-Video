# Project: Signal, Image & Video

## Overview
This project focuses on tracking human movements within an environment using video sequences and generating spatio-temporal heatmaps. These heatmaps represent the probability of occupancy in different areas over time.

## Dataset
The dataset consists of videos recorded from a ceiling-mounted camera in a corridor at the University of Trento, Povo 2. Due to its size and the privacy of the recorder people, any related data to this project is not included in this repository. It's anyway possible to use new videos, inserting them in *\dataset* folder.

## Project Structure
- **Section 1**: Defines necessary modules, helper functions for output visualization and file system navigation. It also includes an analysis of the dataset to determine available videos and suitable time ranges.
- **Section 2**: Introduces two methodologies for computing heatmaps.
- **Section 3**: Visualizes the heatmaps and evaluates the results.


## Usage

To run the project:

0. Optionally, create and activate a virtual environment:
   ```bash
   python -m venv venv
   source venv/bin/activate  # On macOS/Linux
   venv\Scripts\activate    # On Windows

1. Clone this repository:
   ```bash
   git clone <repo_url>
   cd <repo_name>
   ```
2. Install dependencies (if required):
   ```bash
   pip install -r requirements.txt
   ```
3. Use the Jupyter Notebook

## Model
This project utilizes the **YOLOv4-tiny** model for object detection and tracking, enabling efficient person tracking in video sequences. YOLOv4-tiny is a lightweight version of the YOLOv4 model developed by **Alexey Bochkovskiy et al.** and is optimized for real-time applications. 

For more information, visit the official repository:
[YOLOv4 on GitHub](https://github.com/AlexeyAB/darknet)