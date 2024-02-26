# PostgreSQL Database Tables Excel Exporter
Class (module) to connect to any PostgreSQL database and export all tables from a given schema to Excel format for information visualization.

---
## Installation requirements

| Name                   | Installer                                                                                                                                                                                                                     |
|:-------------------------|:-------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------| 
| `Compiler`             | [Python](https://www.python.org/downloads/release/ "Python")                                                                                                                                                      |
| `IDE`    | [Visual Studio Code](https://code.visualstudio.com/ "Visual Studio Code"), [Sublime Text](https://www.sublimetext.com/ "Sublime Text"), [Pycharm](https://www.jetbrains.com/es-es/pycharm/download/#section=windows "Pycharm") |
| `Database engine` | [PostgreSQL](https://www.enterprisedb.com/downloads/postgres-postgresql-downloads "PostgreSQL") |

## Installation steps:

#### 1) Unzip the project into a folder on your operating system.

#### 2) Create a virtual environment to later install the project's dependencies.

For Windows:

```bash
python -m venv venv 
```

For Linux:

```bash
virtualenv venv -ppython
```

#### 3) Activate the project's virtual environment.

For Windows:

```bash
cd venv\Scripts\activate.bat 
```

For Linux:

```bash
source venv/bin/active
```

#### 4) Install all the libraries required for the project's successful execution.

```bash
pip install -r requirements.txt
```

#### 5) Configure environment variables in the .env file to facilitate necessary communication with PostgreSQL.

```bash
YOUR_DATABASE_HOST=localhost
YOUR_DATABASE_PORT=5432
YOUR_DATABASE_USER=xxxxx
YOUR_DATABASE_PASSWORD=xxxxx
YOUR_DATABASE_NAME=xxxxx
YOUR_FILENAME=xxxxx
YOUR_DATABASE_SCHEMA_NAME=xxxxx
```
#### 6) Run the main script.

```bash
python main.py
```
