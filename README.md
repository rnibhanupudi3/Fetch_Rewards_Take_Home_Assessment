# Fetch_Rewards_Take_Home_Assessment

Submission for the Fetch Rewards ML Apprentice Take-Home Assessment

## Getting Started:

### Using `requirements.txt`

This project uses `pip` for dependency management.  To set up your environment using `requirements.txt`, follow these steps:

1.  **Install Python:** Ensure you have Python 3.11 or later installed on your system. You can download it from [python.org](https://www.python.org/downloads/).

2.  **Create a virtual environment (recommended):**
    ```bash
    python -m venv <env_name>
    ```
    Replace `env_name` with a name for your virtual Python environment.

3.  **Activate the virtual environment:**
    * **On Windows:**
        ```bash
        venv\Scripts\activate
        ```
    * **On macOS and Linux:**
        ```bash
        source venv/bin/activate
        ```

4.  **Install the dependencies:**
    ```bash
    pip install -r requirements.txt
    ```
    This command reads the `requirements.txt` file and installs all the listed packages and their dependencies.

### Using `conda environment.yml`

For those using the Conda package manager, an `environment.yml` file is provided.  This file allows you to create a Conda environment with all the necessary dependencies.

1.  **Install Conda:** If you don't have Conda installed, you can download and install either Anaconda or Miniconda from [anaconda.com](https://www.anaconda.com/download/).

2.  **Create the Conda environment:**
    ```bash
    conda env create -f environment.yml
    ```
    This command creates a new Conda environment with the name specified in the `environment.yml` file (or you can provide a name with `-n <env_name>`).

3.  **Activate the Conda environment:**
    ```bash
    conda activate <env_name>
    ```
    Replace `<env_name>` with the actual name of the environment (`new_env` by default).

## Project Structure

All materials for the submission are attached in the folder for this repository. All programming tasks are completed in the Jupyter notebook. Justification and technical write-up are attached in the PDF file.

## Usage

Activate your virtual environment and install all packages. Then, run either of the following commands:

 ```bash
 jupyter notebook
 ```
 ```bash
 jupyter lab
 ```
The command will automatically open Jupyter in your default web browser on localhost port 8888. Select your virtual environment as the Jupyter Kernel and hit `Shift + Enter` to execute cells.

