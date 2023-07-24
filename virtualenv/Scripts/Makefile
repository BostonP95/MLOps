install:
	pip install --upgrade pip 
	pip install -r requirements.txt

lint:
	pylint --disable=R,C code_ex.py

test:
	python -m pytest -vv --cov=code_ex test_code_ex.py