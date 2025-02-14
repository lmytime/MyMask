# MyMask - Interactively Mask Your Data.

An interactive tool for masking spectrum (any x-y) data using Matplotlib and PyQt5. This tool allows users to visually mask and unmask points on a spectrum, providing an easy way to manipulate data for further analysis.

<img src="mymask.gif" alt="Example"/>

## Features
- Load spectrum data from FITS or CSV files.
- Select which columns to use as X and Y for visualization.
- Interactively mask points by clicking on them (left-click to mask, right-click to unmask).
- Automatically save masked data to new CSV or FITS files.
- Visualize spectrum data in a user-friendly interface with zoom and pan capabilities.

## Installation
To install the Interactive Spectrum Mask Tool, use `pip`:

```sh
pip install mymask
```

## Usage
To run the application after installation, use the command:

```sh
mymask
```

### Loading Data
- Click on the "Load Data" button to load your spectrum data.
- You can load either a CSV file or a FITS file.
- Once the file is loaded, use the dropdown menus to select the appropriate columns for X and Y.

### Masking and Unmasking Points
- Left-click on a point in the plot to mask it.
- Right-click on a masked point to unmask it.
- The masked points will appear in red, while unmasked points will appear in blue.

### Saving Data
- Click on the "Save Mask" button to save your mask.
- A new `.csv` file will be created with a suffix `_mask` containing the mask, including a `mask` column indicating which points are masked.

## Dependencies
The tool requires the following Python packages:
- `numpy`
- `pandas`
- `astropy`
- `PyQt5`
- `matplotlib`

These dependencies will be automatically installed when you install the tool using `pip`.

## Example
Here is a simple example of how to use the tool:

1. Run the tool using the command:
   ```sh
   mymask
   ```
2. Click "Load Data" to load a CSV or FITS file.
3. Select the columns to be used as X and Y for plotting.
4. Interactively mask/unmask data points as needed.
5. Click "Save Masked Data" to save your modifications.

## License
This project is licensed under the GPL License - see the LICENSE file for details.

## Contributing
Contributions are welcome! Please open an issue or submit a pull request on the [GitHub repository](https://github.com/lmytime/mymask).

## Contact
For any issues or questions, please contact [lmytime@hotmail.com](mailto:lmytime@hotmail.com).

---

Enjoy using the Interactive Data Masking Tool to easily analyze and manipulate your data!