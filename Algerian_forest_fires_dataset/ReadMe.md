# Algerian Forest Fires Dataset Project

This project explores and analyzes the Algerian Forest Fires dataset using Python and machine learning techniques.

## Project Setup

### 1. Clone the repository

```bash
git clone <your-repo-URL>
cd Algerian_forest_fires_dataset
```

### 2. Create the Conda environment

The project uses a Conda environment located in `./env`. To create and activate it:

```bash
conda create --prefix ./env python=3.10
conda activate ./env
```

> Note: On some systems, you may need `conda activate ./env` with the relative path.

### 3. Install dependencies

All required packages are listed in `environment.yml`. To install them:

```bash
conda env update --prefix ./env --file environment.yml
```

Alternatively, you can install packages using pip:

```bash
pip install -r requirements.txt
```

> If you don’t have a `requirements.txt`, you can generate it from the environment:
>
> ```bash
> pip freeze > requirements.txt
> ```

## Usage

After activating the environment:

```bash
python main.py
```

Replace `main.py` with the entry point of your project.

## Dependencies

- Python 3.10
- Flask 3.1.1
- NumPy 2.2.6
- Pandas 2.3.1
- scikit-learn 1.7.1
- SciPy 1.15.3
- Other dependencies listed in `environment.yml`

## Notes

- The Conda environment is located at `./env`.
- `MLProjects` is ignored in the parent repository `ML_Universe` to allow independent version control.
