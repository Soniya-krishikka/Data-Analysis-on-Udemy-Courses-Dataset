# Data-Analysis-on-Udemy-Courses-Dataset

This repository contains a Jupyter Notebook that performs an exploratory data analysis (EDA) on a dataset of Udemy courses. The dataset includes various attributes related to the courses, such as course ID, title, price, number of subscribers, number of reviews, number of lectures, course level, content duration, publication timestamp, and subject category.

## Table of Contents

- [Introduction](#introduction)
- [Features](#features)
- [Dataset](#dataset)
- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)

## Introduction

The Udemy Course Dataset Analysis project focuses on analyzing a dataset containing information about Udemy courses. The primary objectives include cleaning the data, exploring various attributes, and extracting meaningful insights about course popularity, pricing, and other factors.

## Features

- **Data Loading**: Load the Udemy course dataset using Pandas.
- **Data Cleaning**: Identify and handle missing values.
- **Data Exploration**: Inspect the dataset, including its structure, and display summary statistics.
- **Visualization**: Generate visualizations to understand the distribution and relationships of different attributes.

## Dataset

The dataset used in this analysis includes the following columns:
- `course_id`: Unique identifier for each course.
- `course_title`: Title of the course.
- `is_paid`: Boolean indicating whether the course is paid.
- `price`: Price of the course.
- `num_subscribers`: Number of subscribers enrolled in the course.
- `num_reviews`: Number of reviews given to the course.
- `num_lectures`: Number of lectures in the course.
- `level`: Difficulty level of the course (e.g., Beginner, Intermediate, Expert).
- `content_duration`: Duration of the course content.
- `published_timestamp`: Timestamp when the course was published.
- `subject`: Subject category of the course (e.g., Business, Music, Web Development).

## Installation

To run the notebook and perform the analysis, you'll need to have Python and Jupyter Notebook installed on your system. Additionally, you'll need to install the required Python libraries.

1. Clone this repository:
    ```bash
    git clone https://github.com/Soniya-krishikka/Data-Analysis-on-Udemy-Courses-Dataset.git
    ```
2. Navigate to the project directory:
    ```bash
    cd Data-Analysis-on-Udemy-Courses-Dataset
    ```
3. Install the required libraries:
    ```bash
    pip install pandas numpy matplotlib seaborn
    ```

## Usage

1. Open the Jupyter Notebook:
    ```bash
    jupyter notebook
    ```
2. In the Jupyter Notebook interface, navigate to the project directory and open `Project 7 - Udemy Course Dataset Analysis.ipynb`.
3. Run the cells in the notebook to perform the data analysis.

## Contributing

Contributions are welcome! If you have any suggestions, improvements, or bug fixes, please create a pull request or open an issue.
