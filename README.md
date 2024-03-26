# ChromAsym
ChromAsym is an R package designed to calculate the asymmetry factor for chromatographic peaks. This package provides a tool to analyze peak shapes in chromatography data, offering insights into the efficiency of separation processes.

## Installation

You can install the latest development version of PeakAsymmetryFactor from GitHub with:

    install.packages("devtools")
    devtools::install_github("dbalgoma/ChromAsym")

## Usage

To use PeakAsymmetryFactor, first, load the package:

    library(ChromAsym)

Calculate the asymmetry factor of a peak by using the function 'ChromAsym':
    
    scantime <- chrom_1[,1]
    intensity <- chrom_1[,2]
    ChromAsym(scantime, intensity)

## Features
   Asymmetry Factor Calculation: Provides a simple function to calculate the asymmetry factor, an important metric in chromatography for peak evaluation.    
   Visualization: Offers plotting functions to visualize chromatographic peaks and their asymmetry.

## License

PeakAsymmetryFactor is released under the GNU General Public License Version 3. See the LICENSE file for more details.

For questions and feedback, please open an issue on the GitHub issue tracker.
