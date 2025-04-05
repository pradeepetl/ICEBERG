# Step-1:

## pip install poetry

# Step-2:

### Create a new directory for your project
## mkdir iceberg_pyspark_project
## cd iceberg_pyspark_project

### Initialize a new Poetry project
## cd iceberg_pyspark_project
## poetry init

# Step-3:

## Create a virtual environment.
### python -m venv .venv
### source .venv/bin/activate

# Step-4:

##  Add PySpark as a development dependency
### poetry add --group=dev pyspark ipykernel

# Step-5:

## Get python interpreter path,
### poetry env info
#### /workspaces/ICEBERG/iceberg_pyspark_project/.venv
## Change jupyter notebook kernal





