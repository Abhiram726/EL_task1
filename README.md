# Netflix Data Cleaning Project

This project focuses on cleaning and preparing a dataset containing information about Netflix titles for further analysis. The dataset includes various attributes such as show IDs, titles, directors, cast, country, date added, rating, duration, listed in, and description.

## Project Structure

```
netflix-data-cleaning
├── data
│   └── netflix_titles.csv        # Dataset used for data cleaning
├── notebooks
│   └── task_1.ipynb              # Jupyter notebook for the data cleaning pipeline
├── requirements.txt               # Python dependencies required for the project
└── README.md                      # Documentation for the project
```

## Dataset

- **data/netflix_titles.csv**: This file contains the dataset used for the data cleaning process. It includes information about Netflix titles, such as:
  - show_id
  - title
  - director
  - cast
  - country
  - date_added
  - rating
  - duration
  - listed_in
  - description

## Jupyter Notebook

- **notebooks/task_1.ipynb**: This Jupyter notebook file contains the data cleaning pipeline for the Netflix dataset. It includes:
  - Importing necessary libraries
  - Loading the dataset
  - Cleaning the data (handling missing values, duplicates, and standardizing text)
  - Verifying the results of the cleaning process

## Requirements

To run this project, you need to install the required Python packages. You can do this by running:

```
pip install -r requirements.txt
```

## Running the Notebook

1. Ensure you have Jupyter Notebook installed. If not, you can install it using pip:

   ```
   pip install notebook
   ```

2. Navigate to the `notebooks` directory:

   ```
   cd notebooks
   ```

3. Start Jupyter Notebook:

   ```
   jupyter notebook
   ```

4. Open `task_1.ipynb` and run the cells to execute the data cleaning pipeline.

## Contributing

Contributions to improve the project are welcome. Please feel free to submit a pull request or open an issue for any suggestions or improvements.

## License

This project is licensed under the MIT License. See the LICENSE file for more details.