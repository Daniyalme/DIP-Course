# Change Detection with Spectral Imaging

### Keywords

 **Change Detection** &nbsp;&nbsp;|&nbsp;&nbsp; **AVIRIS Hyperspectral Sensor** &nbsp;&nbsp;|&nbsp;&nbsp; **RGB Spectral Composite**  
 **Advanced Spectral Analysis** &nbsp;&nbsp;|&nbsp;&nbsp; **Remote Sensing Technology** &nbsp;&nbsp;|&nbsp;&nbsp; **Environmental Transformation Monitoring**  
 **Hyperspectral Imaging Systems**

## Overview

Change detection in spectral images is a vital tool with diverse applications across various domains, including:

- Agriculture
- Environmental monitoring
- Urban planning
- Disaster management
- Defense

This method involves analyzing images captured at different times to identify and assess changes in the scene. By leveraging these techniques, we can gain critical insights into dynamic processes and temporal trends, which are crucial for **decision-making** and **resource management**.

The dataset utilized in this project consists of **multi-temporal hyperspectral images**, making it an excellent resource for advancing research in change detection and its practical applications.

---

## Dataset Information

The provided dataset includes **multi-temporal hyperspectral images** collected using the **AVIRIS sensor**. These images provide deep insights into environmental changes over time and consist of two specific datasets:

1. **Santa Barbara Scene**:
   - **Year**: Acquired in 2013 and 2014
   - **Region**: Santa Barbara, California
   - **Dimensions**: 984 x 740 pixels
   - **Spectral Bands**: 224

2. **Bay Area Scene**:
   - **Year**: Acquired in 2013 and 2015
   - **Region**: Patterson, California
   - **Dimensions**: 600 x 500 pixels
   - **Spectral Bands**: 224

These datasets enable robust analysis of **temporal changes**, facilitating a deeper understanding of phenomena such as **environmental degradation**, **urbanization**, and **ecosystem shifts**.

---

## Methodology

This project implements **change detection** techniques using hyperspectral imaging. The process involves:

1. **Data Preprocessing**: 
   - Loading hyperspectral image data.
   - Normalizing spectral bands to ensure consistent analysis.

2. **Change Detection**:
   - Comparing spectral data across different time frames.
   - Using spectral indices and composite images to highlight significant differences.

3. **Analysis and Visualization**:
   - Visualizing the changes with RGB composites and spectral band plots.
   - Interpreting results to identify key trends in the observed regions.

---

## Requirements

To get started, ensure you have the following dependencies installed:

- Python 3.x
- NumPy
- Matplotlib
- OpenCV
- scikit-learn

Install the required libraries with:

```bash
pip install numpy matplotlib opencv-python scikit-learn
```

---

## Getting Started

1. **Download the Dataset**  
   Access the dataset from [Change Detection Dataset](https://gitlab.citius.gal/hiperespectral/ChangeDetectionDataset).

2. **Set File Paths**  
   Update the file paths in the script to match your local setup:
   ```python
   original_file_path = "/path/to/original_image"
   changed_file_path = "/path/to/changed_image"
   ```

3. **Visualize Results**  
   Run the `change-detection.ipynb` cells and view the detected changes and analyze spectral data through generated plots.

---

## Results

The results include:

- RGB composite images highlighting areas of significant change.
- Spectral band visualizations to pinpoint shifts in specific wavelengths.
- Quantitative metrics that summarize the extent of changes.

---

## Applications

This change detection approach can be applied to:

- **Monitoring crop health** in agriculture.
- **Assessing damage** from natural disasters.
- **Tracking urban development** over time.
- **Analyzing environmental shifts** due to climate change.

---

## References

For more information, visit the [AVIRIS Project Website](https://aviris.jpl.nasa.gov/) or refer to the official [Change Detection Dataset](https://gitlab.citius.gal/hiperespectral/ChangeDetectionDataset).

---

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.
