# IMDB Exploratory Data Analysis
![image info](resource/hero.jpg)
# Project by: Cain Seriph

## Overview
This repository provides a comprehensive analysis of IMDB entries using a datasets updated as of March 18, 2024. The data, sourced from the IMDB non-commercial collection. The analysis offers insights into content release trends, genre popularity,and more.

## Features Utilized for the project

  | Feature        | Description                           |
  |----------------|---------------------------------------|
  | Read TWO data files| Used 2 TSV files found via IMDB non-commercial release (download of fresh files commented out in Jupytper notebook.)|
  | Clean your data and perform a pandas merge with your two data sets, then calculate some new values based on the new data set.      | Cleaned my data and merged them with pandas. Then calculated stats from various data points |
  | Make 3 visualizations | Made various plots to show off my findings. |
  | Utilize a virtual environment      | Made a venv 'imdb' for this project. |
  | Create a Data Dictionary for your project | Created a Data Dictionary specific to this project. |
  | Notate your code with markdown cells in Jupyter Notebook | Included in my code, you will find clear notes describing each code block. |

## Dataset Source
[imdb](https://developer.imdb.com/non-commercial-datasets/) https://developer.imdb.com/non-commercial-datasets/

### Files
- `title.basics.tsv` : Dataset containing basic information, including content type, title, and genre.
- `title.ratings.tsv` : Dataset with rating and voting information.

## Development Environment
Microsoft Windows 11 Home X64 Version 10.0.22631 Build 22631
This project is written using version Python 3.13.0.
A Virtual environment titled imdb was used

## Dependencies 
 The following packages will be required to run the program: 
- requests
- gzip
- shutil
- os
- pandas 
- plotly  

## Getting Started
 
1. Fork the repository [github](https://github.com/cainseriph/IMDB-Qualitative-Data-Analysis.git) https://github.com/cainseriph/IMDB-Qualitative-Data-Analysis.git
2. Clone the repository to your Github account, download repository to local machine
3. Access the repository from your command line or preferred CMD software
4. Install a virtual environment. The command in Gitbash | python -m venv imdb, Mac/Linux | python3 -m venv imdb
5. Activate the virtual environment. The command in Gitbash | source imdb/scripts/activate, Mac/Linux | source imdb/bin/activate
6. Install the *requirements.txt* file to install necessary packages by running *pip install -r requirements.txt* 
7. Primary Jupyter Notebook for the project is 'IMDB_Movies.ipynb'. Additionally 'IMDB_dirty.ipynb' can be reviewed for the cleaning of the data and 'data_dictionary.ipynb' contains the Data Dictionary for the project.

## Virtual Environment Commands

| Command | Linux/Mac | GitBash |
|---------|-----------|---------|
| Create | `python3 -m venv imdb` | `python -m venv imdb` |
| Activate | `source imdb/bin/activate` | `source imdb/Scripts/activate` (PS)  `source imdb/Scripts/Activate.ps1` |
| Install | `pip install -r requirements.txt` | `pip install -r requirements.txt` |
| Deactivate | `deactivate` | `deactivate` |

## Analysis & Visualizations
This project includes several analyses and visualizations to explore different aspects of the Media Spectrum:

1. **Number of Releases by Genre**
Compares the number of title releases across genres.

2. **Top 10 Studios by production Success** --WIP further data needed
Identifies leading production studios based on the total earnings.

3. **Top 10 Genres by Production Saturation** 
Highlights which genres see the most production.

4. **Top 10 Titles with Highest Rating**
Showcases titles with the highest ratings.

5. **Top 10 Titles by Number of Votes**
Focuses on Titles that are highly recommended by vote count.

6. **Top 5 Languages Featured by Titles** --WIP further data needed
Displays languages with the most titles, indicating key markets for media distribution.

## Contributing
Contributions are welcome! Feel free to submit issues or pull requests.


## License

<a rel="license" href="LICENSE"><img alt="Creative Commons License" style="border-width:0" src="https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by-sa.svg" /></a>

- License: [Creative Commons Attribution-ShareAlike 4.0 International License](LICENSE)