# Recreating John Snow's Ghost Map
## Description
In 1854, Dr. John Snow (no, not the Game of Thrones's character) used a pre-computer method of spatial analysis by mapping patterns and occurrences of cholera outbreaks in Soho, London. He mapped the deaths in the neighborhood and determined that a vast majority occurred around one particular water well and that those that died used that well.

This is not only one of the earliest uses of data visualization, but by solving this problem, Dr. John Snow also founded spatial analysis and modern epidemiology. In this Python project, we will reanalyze the data and recreate his famous map.
## Usage
Clone this repository and open the Jupyter notebook file (`*.ipynb`) in a Jupyter environment with Python kernel support. Make sure to install the required packages such as `pandas`, `numpy`, `folium` and `bokeh`. You can do this by running the following commands in a code cell within the notebook:
```python
!pip install pandas numpy folium bokeh
```
Once the packages are installed, run the code cells in the notebook to generate the plots and analyses.

If you don't have a Jupyter environment set up, you can install Jupyter Notebook and the Python kernel using the following steps:

1. Install Jupyter Notebook by following the instructions on the [official Jupyter website](https://jupyter.org/install).

2. Ensure you have Python installed. If not, you can download and install Python from the [official Python website](https://www.python.org/downloads/).
## Contents
1. **Dr. John Snow:** Import the data that John Snow collected about the cholera epidemic.
2. **Cholera attacks!:** Check, rename columns, and describe the DataFrame.
3. **You know nothing, John Snow!:** Prepare and pre-process the data for plotting.
4. **The Ghost Map:** Loop through the pre-processed data to create a map.
5. **It's the pump!:** Recreate The Ghost Map.
6. **You know nothing, John Snow! (again):** Reanalyze the John Snow's data about the Cholera Outbreak.
7. **The picture worth a thousand words:** Visualize the data about the Cholera Outbreak using the Bokeh library.
8. **John Snow's myth & Did we learn something?:** True or false?
