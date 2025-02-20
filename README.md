# Automated SQL Generation with OpenAI
![GitHub last commit](https://img.shields.io/github/last-commit/AmmarAhmedl200961/automated-sql-generation-openai)
![GitHub issues](https://img.shields.io/github/issues/AmmarAhmedl200961/automated-sql-generation-openai)
![GitHub stars](https://img.shields.io/github/stars/AmmarAhmedl200961/automated-sql-generation-openai?style=social)
![GitHub forks](https://img.shields.io/github/forks/AmmarAhmedl200961/automated-sql-generation-openai?style=social)

This repository contains a project titled **"Automated SQL Generation with OpenAI"**, which leverages OpenAI's GPT models to automatically generate SQL queries based on natural language questions. The core functionality is encapsulated in a Jupyter Notebook, making it a self-contained solution for generating SQL queries for various tasks. **This project was made possible with the collaboration of Aroz.**

GitHub Repository: [Aroz's Repository](https://github.com/arozgithub/automated-sql-generation-openai/blob/main/README.md)

## Table of Contents

- [Automated SQL Generation with OpenAI](#automated-sql-generation-with-openai)
  - [Table of Contents](#table-of-contents)
  - [Features](#features)
  - [Getting Started](#getting-started)
    - [Prerequisites](#prerequisites)
    - [Setup](#setup)
  - [Usage](#usage)
  - [Example Table Data](#example-table-data)
  - [Contributing](#contributing)
  - [License](#license)

## Features

- **SQL Query Generation**: Automatically generates SQL queries from natural language descriptions of the data retrieval task.
- **Self-Contained Notebook**: All necessary Python libraries can be installed directly within the notebook via a dedicated setup cell.
- **API Key Configuration**: Users can configure their OpenAI API key by creating an `api.txt` file in the project directory.
- **Result Display**: The notebook includes functionality to execute generated SQL queries against a database and display the results.
- **Query Optimization**: Utilizes OpenAI's capabilities to suggest optimizations for the generated SQL queries.

## Getting Started

### Prerequisites

- Python 3.6 or later
- Jupyter Notebook or JupyterLab
- An active OpenAI API key
  
![Python](https://img.shields.io/badge/Python-3776AB.svg?logo=python&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626.svg?logo=jupyter&logoColor=white)
![OpenAI](https://img.shields.io/badge/OpenAI-412991.svg?logo=openai&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-150458.svg?logo=pandas&logoColor=white)
![PrettyTable](https://img.shields.io/badge/PrettyTable-grey?style=for-the-badge&logo=PrettyTable)

### Setup

1. **Clone the Repository**

   ```bash
   git clone https://github.com/AmmarAhmedl200961/automated-sql-generation-openai.git
   cd automated-sql-generation-openai
   ```

2. **Install Dependencies**
   
   Open the `Ammar Ahmed.ipynb` notebook and run the `Libraries Setup` cell to install the required Python libraries.

3. **Configure OpenAI API Key**

    Create a file named `api.txt` in the project directory and paste your OpenAI API key in it.

4. **Run the Notebook**
   
   Open the `Ammar Ahmed.ipynb` notebook in Jupyter and run the cells to generate SQL queries based on natural language descriptions.

## Usage

The notebook is designed straightforward:

1. **Run the Setup Cell**: This installs all the necessary libraries.
2. **Set Up Your API Key**: Ensure `api.txt` is present and contains your valid OpenAI API key.
3. **Use the Provided Functions**: The notebook contains functions to generate SQL queries, execute them, and display results and optimizations.

## Example Table Data

The project works with a hypothetical `employees` database. Here's an example of the table schema used for generating and executing SQL queries:

```plaintext
Table: employees
Columns:
- ID INT
- FirstName VARCHAR
- LastName VARCHAR
- Department VARCHAR
- Salary INT
```

This schema is used within the notebook to illustrate how SQL queries are generated and executed based on natural language questions.

## Contributing

Contributions to the `automated-sql-generation-openai` project are welcome. Please feel free to fork the repository, make your changes, and submit a pull request.

## License

This project is open-source and available under the MIT License. See the LICENSE file for more details.

