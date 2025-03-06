# Project Setup and Usage

Follow these steps to set up and use the project.
## Step 1: Set up a Virtual Environment

To create a virtual environment and isolate your dependencies, run the following command:
```bash
python -m venv .venv
.venv\Scripts\activate 
```
## Step 2: Install Dependencies
Install the required Python libraries using pip:

```bash
pip install -r requirements.txt
```
## Step 3: Populate the Database
To populate the database with initial data, execute:

```bash
python populate_database.py
```
## Step 4: Query Data
To query data, use the following command:

```bash
python query_data.py "your_question"
```
Replace "your_question" with the query you wish to run.
