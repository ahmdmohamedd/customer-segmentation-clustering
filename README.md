# Customer Segmentation Using Clustering Techniques

## Overview
This project utilizes clustering techniques to perform customer segmentation based on the World Happiness Report dataset. By analyzing various factors that contribute to happiness across countries, we aim to identify distinct groups of countries and understand their characteristics.

## Dataset
The dataset used in this project is the **World Happiness Report**, which includes the following columns:

- **Overall Rank**: The rank of the country based on the happiness score.
- **Country or Region**: The name of the country or region.
- **Score**: The happiness score of the country.
- **GDP per Capita**: The economic factor measured by GDP per capita.
- **Social Support**: The perceived level of social support in the country.
- **Healthy Life Expectancy**: The average healthy lifespan of individuals in the country.
- **Freedom to Make Life Choices**: The degree of freedom individuals feel they have in making life choices.
- **Generosity**: The measure of generosity in the country.
- **Perceptions of Corruption**: The level of corruption perceived by individuals in the country.

## Clustering Techniques Used
1. **Agglomerative Clustering**: A hierarchical clustering method that builds clusters step by step.
2. **Mean Shift Clustering**: A non-parametric clustering technique that identifies clusters based on the density of data points.

## Installation
To run this project, make sure you have the following packages installed:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn
```

## Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/ahmdmohamedd/customer-segmentation-clustering.git
   cd customer-segmentation-clustering
   ```

2. Open the Jupyter notebooks to execute the analysis:
   ```bash
   jupyter notebook
   ```

## Results
The project includes visualizations and summaries of the clusters formed by each clustering technique, providing insights into the characteristics of different groups based on their happiness scores and other contributing factors.


## Acknowledgments
- [World Happiness Report](https://worldhappiness.report/) for providing the dataset.
- The libraries used for data analysis and visualization.
