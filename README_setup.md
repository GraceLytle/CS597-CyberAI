# CS597-CyberAI-P1

## Getting Started

### 1. Install Anaconda
   - Download and install [Anaconda](https://www.anaconda.com/products/distribution) for your operating system.

### 2. Create an Anaconda Environment
   To create a new Conda environment using the settings provided in the `environment.yml` file:
   - Open a terminal or **Anaconda Prompt** and navigate to the project directory:
     ```bash
     cd C:\<Your LocalRepo>\CS597-CyberAI-P1
     ```
   - Create the environment by running the following command:
     ```bash
     conda env create -f environment.yml
     ```
   - This will install all the necessary dependencies (like Python, Jupyter, pandas, etc.) as listed in the environment file.
   - Activate the environment:
     ```bash
     conda activate cs597-cyberai-p1
     ```

### 3. Download Data Files Ignoring DVC for Now
Download all of the dataset files from kaggle and put them in data folder.

### 4. Running Jupyter Notebooks
   Once the data is downloaded, you can start Jupyter Notebook to work with the notebooks:
   - Run the following command to launch Jupyter Notebook:
     ```bash
     jupyter notebook
     ```
   - This will open the Jupyter interface in your default web browser, where you can navigate to the `notebooks/` folder and start analyzing data.

### 5. Managing Dependencies
   If you need to install any additional Python packages, ensure that you do so within the **cs597-cyberai-p1** environment by running:
   ```bash
   conda install <package-name>
   ```

### 6. Updating the Environment
 If new dependencies are added to the project, the environment file (environment.yml) may be updated. In that case Update your local environment by running:

```bash
 conda env update --file environment.yml
```
### Troubleshooting
If there are any issues with running the scripts or the environment, ensure that you have activated the correct Conda environment:
    ```bash
    conda activate cs597-cyberai-p1
    ```
If the environment becomes corrupted, you can remove and recreate it
    ```bash
    conda remove --name cs597-cyberai-p1 --all
    conda env create -f environment.yml
    ```


