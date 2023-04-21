# Car Data Analysis with Docker and SQL
This is a sample Docker project for a data science project. The goal of this project is to load a CSV file containing car data into a PostgreSQL database and perform some SQL queries on it.

## Prerequisites
Before running this project, you need to have Docker installed on your machine. You can download and install Docker from the [official website](https://www.docker.com.)

## Getting Started

To run this project, follow these steps:  

1. Clone this repository to your local machine
2. Open a terminal window and navigate to the root directory of this project
3. Run the following command to start the Docker containers:
```
docker-compose up
```   
4. This will start the PostgreSQL database and Jupyter Notebook containers.
5. Open a web browser and go to http://localhost:8888. This will open Jupyter Notebook in your browser.
6. In Jupyter Notebook, open the data-analysis.ipynb file to view the SQL queries used in this project.
7. You can modify the SQL queries or add new ones to perform further analysis on the car data.

## Project Structure
This project contains the following files:
- <span style="color:red" > docker-compose.yml:</span> the Docker Compose file used to start the containers
- <span style="color:red" >car-sql-queries.ipynb:</span> a Jupyter Notebook containing SQL queries for analyzing the car data
- <span style="color:red" >cardata.csv:</span> [a public dataset](https://www.kaggle.com/datasets/athirags/car-data) used for data analysis in this project. The dataset contains information on used cars, including their selling price, year, mileage, and other attributes.
- <span style="color:red" >README.md:</span> this README file
cardata.csv: the dataset used for data analysis in this project. The dataset contains information on used cars, including their selling price, year, mileage, and other attributes.

## Acknowledgments
This project was created for learning purposes and is based on the tutorial Docker for Data Science by Harish Garg.

## License
This project is licensed under the MIT License - see the LICENSE.md file for details.