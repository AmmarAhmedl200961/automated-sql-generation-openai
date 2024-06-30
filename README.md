# Automated SQL Generation with OpenAI

This repository contains a project titled "Automated SQL Generation with OpenAI", which leverages OpenAI's GPT models to automatically generate SQL queries based on natural language questions. The core functionality is encapsulated in a Jupyter Notebook, making it a self-contained solution for generating SQL queries for various tasks.

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

### Setup

1. **Clone the Repository**

   ```bash
   git clone https://github.com/yourusername/automated-sql-generation-openai.git
   cd automated-sql-generation-openai
   ```

2. **Install Dependencies**
   
   Open the `Ammar Ahmed.ipynb` notebook and run the `Libraries Setup` cell to install the required Python libraries.
3. **Configure OpenAI API Key**

    Create a file named `api.txt` in the project directory and paste your OpenAI API key in it.
4. **Run the Notebook**
   
   Open the `Ammar Ahmed.ipynb` notebook in Jupyter and run the cells to generate SQL queries based on natural language descriptions.

   ## Usage

The notebook is designed to be straightforward:

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