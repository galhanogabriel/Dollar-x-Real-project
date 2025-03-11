# Dollar x Real

Exploring the USD/BRL Exchange Rate: A Technical Demonstration of Data Retrieval and Processing Using the FRED API

The purpose of this project was to contextualize the values achieved by the dollar in relation to the Real since the currency came into effect in 1995.

## Project Structure

```
├── .gitignore         # Files and directories ignored by Git
├── environment.yml    # Dependencies required to reproduce the analysis environment
├── LICENSE            # Open-source license (MIT)
├── README.md          # Main README for developers using this project
|
├── notebooks/         # Jupyter Notebooks with analysis
│
|   └── src/           # Source code for this project
|      │
|      ├── __init__.py  # Makes it a Python module
|      ├── config.py    # Basic project configurations
|
├── references/        # Data dictionary
```

## Setting Up the Environment

1. Clone the repository:

    ```bash
    git clone https://github.com/your-username/your-repo.git
    ```

2. Create a virtual environment:

  ```bash
  conda env export > environment.yml
  ```

## More About the Dataset

[Click here](references/01_data_dictionary.md) to see the data dictionary.

## Results

This project successfully generated two key visualizations to illustrate the USD/BRL exchange rate from 1995 to the present, based on data retrieved from the FRED API (series ID: "DEXBZUS").

The first visualization replicates the time series plot available on the FRED website, enhanced with colored shading to delineate the periods of each Brazilian presidential term. This approach provides a clear visual distinction of the exchange rate trends across different administrations, facilitating an understanding of how the dollar's value fluctuated under each president’s tenure.

The second visualization divides the data into multiple smaller subplots, each corresponding to an individual presidential term. This segmented representation allows for a detailed examination of the USD/BRL exchange rate behavior within the specific timeframe of each administration, highlighting variations and patterns unique to those periods.

Both visualizations effectively contextualize the historical exchange rate data, aligning with the project’s objective of demonstrating the retrieval, processing, and presentation of economic data using Python tools such as Pandas and Matplotlib.