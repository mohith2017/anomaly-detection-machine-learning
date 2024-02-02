# Normalyze Technical Challenge

## Description

* This project is about Anomaly detection of a Log based dataset with reasons behind why a certain record constitutes an anomaly using IsolationForest Machine learning model

## Important File Descriptions

* `Code/anomaly-detection.ipynb`: Anomaly Detection pipeline script in Python
* `Code/data-etl.ipynb`: Data ETL pipeline script in Python
* `Data/Input.csv`: The input file for the anomaly detection using IsolationForest model
* `Data/output.csv`: The output file from the anomaly detection using IsolationForest model
* `Anomaly description.docx`: The description of the factors for determining a data point as an anomaly

## How to Run Locally

1. Step 1: First, you need to install the required dependencies. Uncomment the first block of code in the Jupyter Notebook. Then, restart the kernel.

2. Step 2: Then, clone the repository
`git clone <Repository name>`

3. Step 3: Run the Data ETL and Anomaly detection pipelines
`pip install jupyter`

## Running Jupyter Notebooks from the Command Line

There are several ways to run Jupyter notebooks from the command line:

### Running the Jupyter Notebook Server

Start the Jupyter notebook server from the command line using the `jupyter notebook` command. This will open the Jupyter notebook interface in your default web browser.

```bash
jupyter notebook
```

If you want to open a specific notebook, you can provide its filename as an argument:

```bash
jupyter notebook notebook.ipynb
```

If you want to start the Jupyter notebook server without opening a browser, use the `--no-browser` option:

```bash
jupyter notebook --no-browser
```

## Executing Notebooks Using nbconvert

The `nbconvert` tool can execute Jupyter notebooks from the command line. To execute a notebook and overwrite it with the most recent computations, use the following command:

```bash
jupyter nbconvert --execute --to notebook --inplace your-notebook.ipynb
```

If you want to execute a notebook and save the most recent version in a new `.ipynb` file, use the following command:

```bash
jupyter nbconvert --execute --to notebook your-notebook.ipynb
```

