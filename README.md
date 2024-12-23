# 90s Netflix Movies
<center><img src="redpopcorn.jpg"></center>
This project involves exploratory data analysis (EDA) on a dataset of Netflix movies and series. The goal is to gain insights into movies released in the 1990s, which is particularly relevant for a production company specializing in nostalgic styles.

## Project Structure

- `netflix_data.csv`: The dataset containing information about Netflix movies and series.
- `notebook.ipynb`: A Jupyter notebook that contains the analysis and visualizations.

## Dataset

The dataset `netflix_data.csv` includes the following columns:

| Column          | Description                                                                 |
|-----------------|-----------------------------------------------------------------------------|
| `show_id`       | Unique ID for each show                                                     |
| `type`          | Type of content (Movie or TV Show)                                          |
| `title`         | Title of the show                                                           |
| `director`      | Director of the show                                                        |
| `cast`          | Main cast of the show                                                       |
| `country`       | Country where the show was produced                                         |
| `date_added`    | Date when the show was added to Netflix                                     |
| `release_year`  | Year when the show was released                                             |
| `rating`        | Rating of the show (e.g., PG, TV-MA)                                        |
| `duration`      | Duration of the show (e.g., 90 min for movies, 1 Season for TV shows)       |
| `genres`     | Genres or categories the show belongs to                                    |
| `description`   | Brief description of the show                                               |

## Getting Started

To get started with the project, follow these steps:

1. Clone the repository to your local machine.
2. Ensure you have Jupyter Notebook installed. If not, you can install it using pip:
   ```sh
   pip install notebook
   ```
3. Open the Jupyter Notebook:
   ```sh
   jupyter notebook notebook.ipynb
   ```
## Analysis
The analysis is performed in the notebook.ipynb file. It includes the following steps:

1. Loading the dataset.
2. Cleaning and preprocessing the data.
3. Performing exploratory data analysis (EDA).
4. Visualizing the results.
## Conclusion
This project provides insights into Netflix movies and series, with a focus on those released in the 1990s. Feel free to experiment further with the dataset and extend the analysis.
