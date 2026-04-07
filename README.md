# Cloning
Firstly clone the project to your own local:
```bash
git clone https://github.com/oskarpiibar/Data-Security-and-Privacy.git
```

## Create and activate virtual environment
```bash
python -m venv venv
```

**Activate the venv**
```bash
venv\Scripts\activate
```

## Install dependencies
```bash
pip install -r requirements.txt
```

---

## Running the Notebook Locally (VSCode)

Install the Jupyter and Python extensions in VSCode from Microsoft, then register the venv as a Jupyter kernel:
```bash
pip install ipykernel
python -m ipykernel install --user --name=venv --display-name "Python (venv)"
```

Then in VSCode:
1. Open the project **as a folder** (`File → Open Folder`)
2. Open the `.ipynb` file
3. Click the **kernel picker** in the top-right corner
4. Select **Python Environments** → **Python (venv)**

> If the venv doesn't appear in the list, click **Enter interpreter path** and point it to `venv\Scripts\python.exe` (Windows)
