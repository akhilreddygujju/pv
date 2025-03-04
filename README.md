# 1MW 1500V Solar Array Design and Simulation

## Overview

This project focuses on the design and simulation of a 1 MW solar array for Albany, NY. The array is designed to meet the power requirements while staying within the maximum allowable DC voltage of 1500V. The project explores the impact of shading on the performance of the solar array and compares different Maximum Power Point Tracking (MPPT) techniques.

## Key Features

* **1 MW Solar Array Design:** Developed a comprehensive design for a 1 MW solar array.
* **Temperature Analysis:** Incorporated temperature data for Albany, NY, to accurately model PV panel behavior.
* **Shading Simulation:** Simulated the array under various shading conditions (uniform and non-uniform).
* **MPPT Comparison:** Analyzed and compared the performance of Central MPPT, MPPT per string, and MPPT per module.
* **Detailed I-V and P-V Characteristic Plots:** Generated plots for various shading scenarios and MPPT configurations.

## Project Sections

### Section 1: PV Panel Circuit Model

* Developed a PV panel circuit model based on the "NES144/525-530 W F 35mm MBB Half-cell Mono solar cell" datasheet.
* Calculated the Open Circuit Voltage (Voc) at the lowest temperature (-8°C).
* Determined the Maximum Power Voltage (VMPP) and Maximum Power Current (IMPP) at the highest temperature (28°C).
* Calculated the maximum power at 28°C.
* Temperature data was pulled from: [https://weatherspark.com/y/24883/Average-Weather-in-Albany-New-York-United-States-Year-Round](https://weatherspark.com/y/24883/Average-Weather-in-Albany-New-York-United-States-Year-Round)
    * <p align="center"><img src="images/tempdata.png" alt="Temperature Data" style="display: block; margin: 0 auto;"></p>

### Section 2: Array Design

* Determined the total number of panels required for 1 MW power.
* Calculated the number of series modules required to meet the maximum voltage limit.
* Calculated the number of parallel strings required to meet the power demand.
    * <p align="center"><img src="images/arraycalcs.png" alt="Array Calculations" style="display: block; margin: 0 auto;"></p>

### Section 3: Shading Analysis

* Simulated the scaled-down model of the array under uniform and non-uniform shading conditions.
* Analyzed the impact of different percentages of shading (25%, 50%, and 75%) on the I-V and P-V characteristics of the array.
* Shading scenarios included:
    * Uniform Shading
        * <p align="center"><img src="images/uniformshading.png" alt="Uniform Shading Plots" style="display: block; margin: 0 auto;"></p>
    * Non-Uniform Shading
        * <p align="center"><img src="images/nonuniformshading.png" alt="Non-Uniform Shading Plots" style="display: block; margin: 0 auto;"></p>

### Section 4: MPPT Comparison

* Compared the performance of different MPPT techniques under various shading conditions.
    * Central MPPT
        * <p align="center"><img src="images/centralmppt.png" alt="Central MPPT Plots" style="display: block; margin: 0 auto;"></p>
    * MPPT per string
        * <p align="center"><img src="images/stringmppt.png" alt="String MPPT Plots" style="display: block; margin: 0 auto;"></p>
    * MPPT per module
        * <p align="center"><img src="images/modulemppt.png" alt="Module MPPT Plots" style="display: block; margin: 0 auto;"></p>
* Analysis included P-V plots for different shading percentages and MPPT configurations.

## Simulation Results

* Detailed I-V and P-V characteristic plots for various shading scenarios.
* Comparison of MPPT performance under different shading conditions.
* Analysis of the impact of shading on overall array performance.
* Documentation of the PV model and array design calculations.

## Usage

1.  Clone the repository.
2.  Review the `Final Project ES.pdf` for detailed project information.
3.  [Add instructions for running simulations or any other necessary steps here]

## Project Structure

* `Final Project ES.pdf`: Contains detailed calculations, plots, and analysis.
* `IECE513_project (2).pdf`: Project requirements and specifications.
* `images/`: Contains images for the README.
* [Add any code files, simulation files, or data files here]

## Acknowledgments

This project was completed as part of the ECE 513 course at the University at Albany.

## Contact

For any questions or further information, please contact [Your Email].

## Author

[Your Name]

## License

[Add License Information Here]
