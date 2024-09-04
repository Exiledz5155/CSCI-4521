# CSCI-4521

This repository is a boilerplate/template for classwork in CSCI 4521.

## Setup Instructions

1. **Install Python 3.12 or newer**:

   - Download and install Python from the [official Python website](https://www.python.org/downloads/).
   - Ensure to check the option to 'Add Python to PATH' during installation. (Don't mess this up, man!)

2. **Clone the Repository and Create a Virtual Environment**:

   - Skipping the cloning step here; y'all got it.

   - Create a virtual environment:
     ```bash
     python -m venv venv
     ```

3. **Activate the Virtual Environment**:

   - **For Windows**:

     ```bash
     .\venv\Scripts\activate
     ```

   - **For Linux/macOS**:
     ```bash
     source venv/bin/activate
     ```

   Remember, you'll need to activate the virtual environment each time you open a new terminal session.

4. **Install Dependencies**:

   ```bash
   pip install -r requirements.txt
   ```

## Jupyter Notebook

This repository includes three folders you can use as templates for the class:

- **Exercises**: For in-class exercises.
- **Homework**: Contains a `.py` files since it assumes assignments won't require a Jupyter Notebook at least for the development part (we might need to convert to notebook to turn in).
- **Lectures**: For provided lecture stuff.

Feel free to reorganize files or add a `.ipynb` file to any folder you create as needed.

### Running Jupyter Notebook

To start Jupyter Notebook, run:

```bash
jupyter notebook
```

## Cloning vs. Forking

If you plan to push your code to GitHub, I recommended you **fork** this repository and then make it private (for obvious reasons).

If you don't care to push anything and plan on saving things locally, **cloning** the repository should be good enough.
