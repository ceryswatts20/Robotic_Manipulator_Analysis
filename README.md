# Robotic_Manipulator_Analysis

Mathematical analysis of robotic manipulators

## Setup

- Have Python 3.12 and MATLAB installed.

### 1. Open a terminal

- On Windows, use PowerShell (run as administrator).
- On Linux/macOS, use your regular shell.

### 2. Navigate to project folder

Example

```powershell
cd "C:\Users\<YourName>\path\to\project\Robotic_Manipulator_Analysis"
```

### 3. Create a virtual enviroment and install required packages

- This creates a folder called `.venv` inside your project, activates it and installs the required packages.

```powershell
python3.12 -m venv .venv
.\.venv\Scripts\activate.ps1
pip install -r requirements.txt
```

### 4. Install the MATLAB Engine API

From inside your virtual environment go to where MATLAB is installed, navigate to the python engine and install it.

```powershell
cd "C:\Program Files\MATLAB\<your version>\extern\engines\python"
python -m pip install .
```

### 5. Verify the installation

```powershell
python -c "import matlab.engine; print('MATLAB Engine installed successfully')"
```

If no error appears, the engine is installed.

## To Run


## Useful commands

- When adding or removing python packages, update requirements.txt with `pip freeze > requirements.txt`
- To deactivate venv when done run `deactivate` in powershell.
