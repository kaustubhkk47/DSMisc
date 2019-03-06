Steps to work on any project

---Create and activate virtual environment for that project
virtualenv projectname
source projectname/bin/activate

---Install dependencies
pip install -r requirements.txt

--- Install jupyterlab extensions
jupyter labextension install @jupyterlab/toc
jupyter labextension install @krassowski/jupyterlab_go_to_definition


---Run jupyter and check path of python executable in notebook
import sys
sys.executable
---If path is incorrect,ie system path is being used, close notebook
---check jupyter kernel specs list
jupyter kernelspec list
---remove kernel.json from path of kernel and start again

