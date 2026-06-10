# Computational Linguistics – Assignment 04

Guide to running this project on **macOS**. Follow the steps in order.

## What's in here

- `Assignment_04.ipynb` — the assignment (a "notebook": text + runnable Python code).
- `requirements.txt` — the libraries the assignment needs.

## Run it

1. **Open the Terminal:** press `Cmd` + `Space`, type `Terminal`, press `Enter`.

2. **Go into the project folder** using `cd` followed by the path to the folder where this project lives, for example:

```bash
cd path/to/this/project
```

3. **Create the environment** (only the first time). This makes a private Python setup in a `.venv/` folder:

```bash
python3 -m venv .venv
```

4. **Activate the environment** (do this every new Terminal session):

```bash
source .venv/bin/activate
```

Your prompt now shows `(.venv)`.

5. **Install the libraries** (only the first time, or after `requirements.txt` changes):

```bash
pip install -r requirements.txt
```

6. **Open the notebook:**

```bash
jupyter notebook Assignment_04.ipynb
```

It opens in your browser, running locally on your computer.

7. **Run the code:** click a cell, press `Shift` + `Enter`. Run cells top to bottom, or use **Run → Run All Cells**.

> The first NLTK cell downloads some language data. This is normal and happens once.

## When done

- Save: `Cmd` + `S`.
- Stop Jupyter: in the Terminal press `Ctrl` + `C`.
- Optional: `deactivate` to turn off the environment.

## Troubleshooting

- **`command not found: jupyter`** — run `source .venv/bin/activate` first.
- **`No module named ...`** — run `pip install -r requirements.txt`, then retry.
- **Cell errors out of order** — run cells from the top (**Run → Run All Cells**).
- **Browser didn't open** — copy the `http://localhost:8888/...` link from the Terminal into your browser.
