# Dash App for Data Visualization

## Requirement

### Create a virtual enviorment (Optional)

To make virtual enviornment first install the `virtualenv` module of python by,

```console
pip install virtualenv
```

Open terminal in the current working directory and write,

```console
virtualenv <enviornment name>
```

Activate the enviornment by running the following command in the very same working directory.

```console
source <enviornment name>/bin/activate
```

First install the required modules by running the following command in the terminal of the directory.

```console
pip install -r requirement.txt
```

or run these commands in the terminal

```console
pip install pathlib
pip install pandas=1.4.2
pip install numpy=1.22.3
pip install dash=2.4.1
pip install plotly=5.8.0
```

## How to run?

Run the following command in the terminal

```console
python app.py
```

After this a local host link will appear in the terminal, that would look like this,

`http://127.0.0.1:8050/`

Open this link in browser and play with the maps.
