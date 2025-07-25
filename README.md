# SSP_Example

This repository contains notebooks and supporting files used to run the
**SISEPUEDE** model on mitigation scenarios. All modeling resources
reside in the `ssp_modeling` folder described below.


## Instructions: Setting Up the SISEPUEDE Environment

### 1. **Create a Conda Environment from the `.yml` File**

In your terminal, navigate to the directory containing your `environment.yml` file, then run:

```bash
conda env create -f environment.yml
```

This will create a new Conda environment with the name ssp_env.

---

### 2. **Activate the Environment**

After installation, activate your new environment with:

```bash
conda activate ssp_env
```

---

### 3. **Done!**

Your environment is now ready to use, with all dependencies (including those installed via pip) preconfigured.

---

## Project Structure

The most relevant files are inside the `ssp_modeling` directory:

- `input_data/` – Input CSV files.
- `notebooks/` – Jupyter notebooks that manage the modeling runs.
- `ssp_run_output/` – Output folders created after executing a run.
- `transformations/` – CSVs and YAML files describing the transformations and strategies applied by the model.
- `output_postprocessing/` – R scripts used to rescale model results and
    generate processed outputs.

