```bash
python3 -m venv venv
source venv/bin/activate
pip install ipykernel
python3 -m ipykernel install --user --name=venv
pip install -r requirements.txt
```

```bash
# check which python env is being used:
which python3
# check which version of pip is being used and from where
python3 -m pip --version
# source de venv created
source venv/bin/activate
# then just install the requirements
pip install -r requirements.txt
```

### nice article about venv and pip

https://packaging.python.org/en/latest/guides/installing-using-pip-and-virtual-environments/
