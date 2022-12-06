# Environment Reproducability and Management

Here I describe how to download the code for this project and to reproduce the development deployment environments.

---

## Reproducibility

The simplest way to get the code for this Github repository is to:

1.  Navigate to the project [Guthub](https://github.com/davidcolton/mlzoomcamp-capstone-project-01) page
2. Click the `Code` button
3. Download a Zip of the code
4. Unzip the code to a location of your choice on your laptop.

Once you have the code and the environment setup you will be able to run all stages of the project from Notebooks to Docker files and beyond.

---

## Environment Management

The development and deployment environments assume the following are corrently install and configured on your machine:

* Python 3.10
* Docker
* Kebernetes
* Kind

Installing and confirguring these tools are out of scope for this project.

This project uses `pipenv`. If pipenv is not installed on your version of Python you can install it by running the following command in the root folder of the downloaded project source files:

> `pip install pipenv`

The required libraries can then be installed by running:

> `pipenv install`