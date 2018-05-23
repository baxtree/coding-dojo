test: test_main.py main.py
	python -m pytest test_main.py

test_main.py: test_main.ipynb
	jupyter nbconvert test_main.ipynb --to python

main.py: main.ipynb
	jupyter nbconvert main.ipynb --to python

clean:
	rm -f test_main.py main.py
