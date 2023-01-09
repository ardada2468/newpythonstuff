https://www.geeksforgeeks.org/command-line-scripts-python-packaging/


python3 setup.py install
python3 setup.py sdist bdist_wheel
twine upload dist/*

pip install
