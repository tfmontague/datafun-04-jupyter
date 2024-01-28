# datafun-04-jupyter Project 4 Jupyter Notebook - Data Analysis with Jupyter: Iris Dataset

## Overview

This repository contains a Jupyter Notebook for exploratory data analysis (EDA) of the Iris dataset. The analysis includes a series of steps to visualize, understand, and prepare the data for further statistical analysis or machine learning modeling.

## Project Structure
- `README.md`: Provides an overview of the project and instructions for setting up the environment and running the notebook.
- `requirements.txt`: Lists all the Python packages required for the project.
- `tmontague_eda.ipynb`: The Jupyter Notebook containing the EDA for the Iris dataset.

## Environment Setup and How to Install and Run the Project

a. Install Dependencies
-  install packages on one line with this command in VS Terminal: **py -m pip install jupyterlab numpy pandas matplotlib seaborn scipy**

b. Freeze Dependencies
-  after installing packages, freeze dependencies to the requirements.txt file: **py -m pip freeze > requirements.txt**

c. Start Jupyter: Do both methods. Both methods must be available.
- Method 1: Start Jupyter in VS Code: Open project folder in VS code, Install Jupyter extension in VS code (if not already installed), Open VS Code Terminal window, and run **jupyter lab** in integrated terminal.
- Method 2: Start Jupyter in Native Terminal (without VS Code): Open machine terminal in project folder, Start Jupyter Notebook server by running: **jupyter lab**; Default brower will open to Jupyter Notebook interface.

## Data Analysis Workflow
The Jupyter Notebook follows a structured approach to EDA, consisting of the following steps:

1. **Data Acquisition**: Loading the Iris dataset into a pandas DataFrame.
2. **Initial Data Inspection**: Exploring the dataset's basic properties.
3. **Descriptive Statistics**: Summarizing the central tendency, dispersion, and shape of the dataset's distribution.
4. **Data Distribution Analysis**: Visualizing the distribution of data through histograms and count plots.
5. **Data Transformation and Feature Engineering**: Enhancing the dataset with additional features and transformations for better analysis.
6. **Visual Analysis**: Using various plots such as pairplots and heatmaps to visualize relationships between features.
7. **Storytelling and Presentation**: Narrating the data story based on insights derived from the visual analysis.
8. **Conclusion**: Summarizing the findings and the potential for further analysis.

## Contributing
We welcome contributions to this project. If you have suggestions to improve the analysis or encounter issues, please open an issue or submit a pull request.

## References & Acknowledgments
Special thanks to [OpenAI](https://openai.com/) for assistance with project design and coding structure. Additional references used for this project include:

- [JUPYTER.md](https://github.com/denisecase/datafun-04-spec/blob/main/JUPYTER.md) for Jupyter Notebook keyboard shortcuts.
- [MARKDOWN.md](https://github.com/denisecase/datafun-04-spec/blob/main/MARKDOWN.md) for Markdown syntax.
- [Tutorialspoint: Plotting graph For IRIS Dataset Using Seaborn And Matplotlib](https://www.tutorialspoint.com/plotting-graph-for-iris-dataset-using-seaborn-and-matplotlib)
- [Seaborn Tutorial](https://seaborn.pydata.org/tutorial.html)

