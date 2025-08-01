# Fenton Growth Charts (2025)

This project provides an interactive visualization of the Fenton Third-generation Growth Charts (2025) for preterm infants, including interpolated data for all percentiles (1%-100%).

## Features

- **Comprehensive Data**: Includes data for boys and girls across Weight (kg), Head Circumference (cm), and Length (cm).
- **Interpolated Percentiles**: Provides data for all percentiles from 1% to 100% by interpolating between the original 3%, 10%, 50%, 90%, and 97% curves.
- **Interactive Visualization**: An `index.html` file allows users to:
    - Switch between boy and girl data.
    - Toggle between Weight, Head Circumference, and Length charts.
    - Choose to display only the default key percentiles (3%, 10%, 50%, 90%, 97%) or all interpolated percentiles (1%-100%).
- **Performance Optimization**: The default view shows only key percentiles for better performance, with an option to display all percentiles.

## Files

- `src/`: Contains all project files
  - `index.html`: Interactive web-based chart visualization
  - `boys_weight.json`: Boys weight data
  - `boys_head_circumference.json`: Boys head circumference data
  - `boys_length.json`: Boys length data
  - `girls_weight.json`: Girls weight data
  - `girls_head_circumference.json`: Girls head circumference data
  - `girls_length.json`: Girls length data

## Usage

1. Open `src/index.html` in a web browser
2. Use the gender tabs to switch between boys and girls data
3. Use the metric tabs to switch between Weight, Head Circumference, and Length
4. Toggle the switch to display all percentiles (1%-100%) or just the default key percentiles

## Data Source

Based on the Fenton Third-generation Growth Charts (2025) for preterm infants, with linear interpolation applied to generate complete percentile coverage.

## Notes

- Gestational age range: 22-50 weeks
- Data points available for each week within the range
- Linear interpolation used between known percentiles (3%, 10%, 50%, 90%, 97%)
