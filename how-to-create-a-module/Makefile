run: ../venv
	../venv/bin/ansible-playbook playbook.yaml

../venv:
	python3 -m venv ../venv/
	../venv/bin/pip install -U pip
	../venv/bin/pip install -r requirements.txt

clean:
	rm -rf ../venv/
