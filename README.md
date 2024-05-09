```bash
python3 -m venv venv
source venv/bin/activate
pip install ipykernel
python3 -m ipykernel install --user --name=venv
pip install -r requirements.txt
```