# Sentiment Analysis of Restaurant Reviews

&nbsp;This repository contains a notebook and resources to perform sentiment analysis and topic modelling using customer reviews towards several type of restaurants. Main objective of the project is to determine for what reasons various types of cuisines are evaluated as positive or negative by customers. This will give an idea about which aspects of which cuisines are stronger and which aspects are open to improvement.

## About the Dataset

&nbsp;[Yelp Open Dataset](https://www.yelp.com/dataset) is used for this project. It contains nearly 7 million reviews on 150 thousand businesses. It is a subset of Yelp's data for use in connection with academic research available as JSON files. 


## Project Overview
&nbsp;This project was built using Apache Spark in Azure Synapse Analytics. All computations were performed on virtual machines provided by Azure, taking advantage of parallel computing, the core concept of Apacke Spark. The content of the project and all steps applied to the raw dataset are as follows:
- Importing Libraries
- Creating Spark Environment
- Data Preprocessing
    - I.  Cleaning of Busines Dataset
    - II. Cleaning of Review Dataset
    - III. Joining Datasets
    - IV. Feature Extraction
    - V. Text Processing
        - a. Text Cleaning
        - b. Stopword Removal
        - c. Tokenization
- Implementing Bag-of-Words
    - I. Building Vocabulary
    - II. Vectorizaion
    - III. Deriving Weights
    - IV. Creating the Bag-of-Words Matrix
    - V. Counting Frequencies
    - VI. Calculating Polarities
- Creating the Polarity Table
- Generating the Plot
- Function Definitions
- Implementation and Results
 

## Tools and Technologies Used
&nbsp;The project was carried out using Apache Spark's Python API, PySpark. The libraries and sub-packages used are as follows:

- NumPy
- Pandas
- Seaborn
- MatplotLib
- pyspark.sql
- pyspark.ml


## How to Use
&nbsp;ou can run the project by cloning it or downloading the files on your local machine. It is recommended to use a Python development environment such as Jupyter Notebook or Anaconda. By running the project files or examining the visualizations, you can learn more about the dataset.

```bash
git clone https://github.com/yusufkurubacak/PySpark-Yelp-Restaurant-Reviews-Sentiment-Analysis.git
```

## Contributing
&nbsp;If you would like to contribute to this project, please fork it and make your changes. Then submit a pull request to propose your changes. Any contributions and feedback are welcome.

## License
&nbsp;This project is licensed under MIT. For more information, see the LICENSE file.

## Contact
&nbsp;If you have any questions or feedback about the project, feel free to contact me at yusufkurubacakk@gmail.com.