# Read me

This repository is part of the educational project for the "bpEXA" course at the Faculty of Bioinformatics, Leiden University of Applied Sciences.

## Description

The script in this repository is an adapted copy of the [basic tutorial for query-to-reference mapping using expiMap](https://docs.scarches.org/en/latest/expimap_surgery_pipeline_basic.html). The primary purpose of the script is to train a model to minimize batch effects in bioinformatics data.

## Requirements

To run the script with **scArches version 0.6.1**, you will need:

- A development environment with **Python 3.12**.

### Important Note

Starting from January 2025, errors may occur when installing **scArches** due to updates to its dependency libraries. Therefore, it is strongly recommended to use the `requirements.txt` file included in this repository to set up a virtual development environment and install all necessary dependencies.

## Installation

1. Ensure that Python 3.12 is installed on your system.
2. Create and activate a virtual environment:
    
    ```bash
    python3.12 -m venv venv
    source venv/bin/activate  # for Linux/MacOS
    venv\Scripts\activate  # for Windows
    ```
    
3. Install the dependencies from `requirements.txt`:
    
    ```bash
    pip install -r requirements.txt
    ```
    
