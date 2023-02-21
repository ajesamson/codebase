# Python Codebase

### Virtual Environment - Python
Using python venv
1. Create virtual environment
   ```bash
   python3 -m venv .venv
   ```
2. Activate virtual environment
   ```bash
    source .venv/bin/activate
   ```
    Result => (.venv) [samson]$
3. Install libraries
   ```bash
   pip3 install requests
   ```
4. Deactivate virtual environment
   ```bash
   deactivate
   ```
5. Export installed libraries
   ```bash
   pip freeze > requirements.txt
   ```
    Install on remote system
    ```bash
    (my-environment) $ pip install -r requirements.txt
    ```


### Virtual Environment - [Conda](https://docs.conda.io/en/latest/)
Using miniconda, download and install package as appropriate for your environment (windows, macosx, linux). This is mostly appropriate when doing data science and installation of library is required for testing.
1. Create virtual environment
   ```bash
   conda create --name python3916 python=3.9.16
   ```
2. Activate virtual environment
   ```bash
    conda activate python3916
   ```
    Result => (python3916) [samson]$
3. List conda environments
   ```bash
   conda env list
   ```
4. Deactivate virtual environment
   ```bash
   conda deactivate
   ```
5. Export conda settings
   ```bash
   conda list --explicit > conda-requirements.txt
   ```

Check here for [command list](https://docs.conda.io/projects/conda/en/4.6.0/_downloads/52a95608c49671267e40c689e0bc00ca/conda-cheatsheet.pdf)
