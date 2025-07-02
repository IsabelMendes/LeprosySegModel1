# 1. Create a new virtual environment (env)
## If you have Python 3.11 installed:
python3.11 -m venv hanseniase_env_311

## Or specify the Python version when creating the environment:
python -m venv hanseniase_env_311 --python=python3.11



# 2. Make sure your virtual environment is activated
## On Windows:
hanseniase_env_311\Scripts\activate
## On macOS/Linux:
source hanseniase_env_311/bin/activate

# 3. Create a new kernel
pip install ipykernel

python -m ipykernel install --user --name hanseniase_env_311 --display-name "Hanseniase Python 3.11"

# 4. Select the new kernel 
a) Open your notebook

b) Click on "Kernel" in the menu

c) Select "Change kernel"

d) Choose "Hanseniase Python 3.11"

##Deactivate your current env:
deactivate