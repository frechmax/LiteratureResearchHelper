# Usage

1. Put your query in the query variable.

2. Play with Data.

# Setting Up a the LiteratureResearchHelper

Follow these steps to create and use a Python virtual environment (`venv`) for your `.ipynb` notebooks:

## 1. Create a Virtual Environment

Open a terminal in your project directory and run:

```sh
python -m venv .venv
```

## 2. Activate the Virtual Environment

- **Windows:**
    ```sh
    .venv\Scripts\activate
    ```
- **macOS/Linux:**
    ```sh
    source .venv/bin/activate
    ```

## 3. Install Required Packages

Install Jupyter and any other dependencies:

```sh
pip install notebook ipykernel pandas requests
```

## 4. Add the Virtual Environment as a Jupyter Kernel

```sh
python -m ipykernel install --user --name=venv-literature-helper
```

## 5. Use the Kernel in Your Notebook

- Open your `.ipynb` file in VS Code or Jupyter Notebook.
- Select the kernel named `venv-literature-helper` from the kernel picker.

---

**Tip:** Always activate your virtual environment before running or editing your notebook to ensure dependencies are managed correctly.