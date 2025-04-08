# Retail Customer Segmentation Using K-Means Clustering

## Description

This project performs customer segmentation for a retail business using unsupervised machine learning. The goal is to identify distinct groups of customers based on purchasing behavior using the K-Means clustering algorithm. This allows businesses to tailor marketing efforts and improve customer relationship strategies. The project includes data cleaning, exploratory data analysis (EDA), feature selection, model training, and visualization of cluster results.

---

## Getting Started

### Prerequisites

To run this project, you need to have the following tools and libraries installed:

- Python 3.7 or higher
- Jupyter Notebook or JupyterLab
- Required libraries:
  - `pandas`
  - `numpy`
  - `matplotlib`
  - `seaborn`
  - `scikit-learn`

Install the dependencies using pip:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

### Installing

1. Clone this repository or download the `Project 2.ipynb` notebook file.
2. Open the notebook in Jupyter Notebook or JupyterLab:

```bash
jupyter notebook Project\ 2.ipynb
```

3. Run the notebook cells in order to reproduce the results and visualizations.

---

## Running the Tests

### Breakdown of Tests

Although formal unit tests are not included, the notebook includes the following validation steps:

- **Data Inspection**: Uses `.head()`, `.info()`, and `.describe()` to examine data structure and summary statistics.
- **EDA**: Visual exploration of customer features using `seaborn` and `matplotlib`.
- **Optimal Clusters**: Applies the Elbow Method to determine the ideal number of clusters.
- **Clustering Evaluation**: Visualizes customer clusters based on selected features using 2D plots.

---

## Deployment

This project is designed for exploratory analysis and runs in a Jupyter Notebook environment. For production or business applications, you could:

- Convert the notebook into modular Python scripts
- Integrate the model into a web interface using tools like Flask or Streamlit
- Automate data input/output pipelines

---

## Author

**SANJU JOSEPH** 

---

## License

This project is licensed under the MIT License. See the `LICENSE` file for more details.

---

## Acknowledgement

- Inspired by real-world customer segmentation use cases.
- Thanks to the open-source Python community for developing and maintaining the libraries used in this project.
