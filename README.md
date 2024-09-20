# Running

## Poetry

I used poetry to create this project and manage the dependencies. To install the dependencies, run:

```bash
poetry install
```

Then a virtual environment will be automatically created and the dependencies will be installed.

After that, simply connect to the ipynb file and run the cells.

## Virtual Environment

Alternatively, you can create a virtual environment and install the dependencies manually. To do this, run:

```bash
python3 -m venv .venv
source .venv/bin/activate
pip install -r requirements.txt
```

Then, connect to the ipynb file and run the cells.

## Vanilla Python

If you don't want to use a virtual environment, you can install the dependencies globally. To do this, run:

```bash
pip install -r requirements.txt
```

Then, connect to the ipynb file and run the cells.

WARNING: this can cause conflicts with other projects that use the same dependencies.
