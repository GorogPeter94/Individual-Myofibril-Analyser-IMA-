# Individual Myofibril Analyser (IMA): A Tool for Automated Sarcomere Measurement
**IMA** is a Python-based software designed to streamline and standardize the measurement of sarcomere length and width from microscopic images. It offers automated, semi-manual, and manual modes to accommodate diverse image conditions and user preferences.

Required python version 3.12.8 and the following packeges: Pandas (version 2.2.3 tested), Matplotlib (version 3.9.3 tested), Numpy (version 2.2.0 tested), Opencv-python (version 4.10.0.84 tested), Aicsimageio (version 4.14 tested), aicspylibczi (version 3.2.0 tested), openpyxl (version 3.1.5 tested 3.2.0 doesn't work at the moment)

# Key Features:

1. Automated Analysis: Automatically identifies Z-discs, generates splines, extracts histograms, and fits Gaussian curves to calculate sarcomere length.
2. Width Calculation: Provides both automated and manual options for determining sarcomere width.
3. Multi-format Support: Handles TIFF, LIF, and CZI image formats.
4. Visual Output: Generates informative images and histograms to visualize the analysis process.
5. Data Export: Compiles results into an Excel spreadsheet for convenient data management.

# Usage:
Our software provides a streamlined workflow for analyzing sarcomere structures in fluorescence microscopy images. Users can import images, select specific channels for length and width measurements, and choose between automatic, semi-manual, or manual analysis modes. With a simple interface, the software efficiently evaluates sarcomere dimensions and generates detailed output data, including processed images and measurement reports. Designed for precision and flexibility, this tool supports researchers in studying muscle development and structural organization with ease. Detailed information and instructions can be found in the User guide within the repository.

# License
This program is free software: you can redistribute them and/or modify them under the terms of the GNU General Public License as published bythe Free Software Foundation.

# Contributors
Ima was created by Novák Tibor and Péter Görög ,and it is currently maintained by Péter Görög
