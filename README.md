# Qiskit Fall Fest 2023

Welcome to the Qiskit Fall Fest! To successfully run the challenge notebooks, follow the instructions below:

## Using IBM Quantum Lab

You're ready to begin! Watch the video file for instructions on how to upload the notebooks and ensure your images are working properly.

## Running Locally

### Prerequisites:
- Python 3.10 or greater virtual environment

### Install:

1. Install the grader client, Qiskit, and Jupyter Lab by running one of the following commands in a terminal window in your Python virtual environment:

   - To install the grader client, Qiskit, and Jupyter Lab:
     ```bash
     pip install 'qc-grader[qiskit,jupyter]@git+https://github.com/qiskit-community/Quantum-Challenge-Grader.git'
     ```

   - If you already have Jupyter Lab in your Python virtual environment and only need to install the grader client and Qiskit:
     ```bash
     pip install 'qc-grader[qiskit]@git+https://github.com/qiskit-community/Quantum-Challenge-Grader.git'
     ```

   - If you already have Jupyter Lab and Qiskit (version 0.44.0 or greater) installed in your Python virtual environment and only need to install the grader client:
     ```bash
     pip install 'git+https://github.com/qiskit-community/Quantum-Challenge-Grader.git'
     ```

### Run:

1. From a terminal window in your Python virtual environment, change to the directory where all the Qiskit Fall Fest Challenges notebooks reside. For example:
   ```bash
   cd ~/Qiskit-Fall-Fest-Challenges-Notebooks
2. Launch Jupyter Lab:
    ```bash
    jupyter lab .
  This should launch your Jupyter Lab instance in a new browser window showing the Qiskit Fall Fest Challenges notebooks.