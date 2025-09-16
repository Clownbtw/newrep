# newrep
git clone https://github.com/USERNAME/REPO_NAME.git
cd REPO_NAME
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
pip install -r requirements.txt
pytest
cd docs
make html
open _build/html/index.html  # Windows: start _build/html/index.html
