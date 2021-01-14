# pypi-poc

1) Create a package build
  
	python manage.py sdist


2) Upload package on pypi

	twine upload --repository-url https://upload.pypi.org/legacy/ dist/*
