Natural Language Processing Algorithms Analysis
===

## Abstract
Part of Natural Language Processing (NLP) algorithms focuses on semantic analysis of text. This thesis analyses and compares algorithms for text classication. The main goal is to design and implement an application able to classify English text with use of Latent Dirichlet Allocation (LDA) and Latent Semantic Analysis (LSA) trained on Wikipedia data dump. Final software solution is verified by two experiments with help of Self-Organizing Maps and it is considered to be trained on a satisfactory level. This thesis results in the application which can be used for simple text classification via user interface or application interface.

## Installation
Please follow these instructions to install code of this thesis. Note that it was tested only on Linux system.

- Install [MongoDB](https://docs.mongodb.com/manual/administration/install-on-linux/)
- Install following Linux packages: NumPy, SciPy, Python devel, etc. (TBD)
- Install Python packages, it is NOT recommended to use virtualenv due to problems with some required Linux packages:

`pip install -r /path/to/requirements.txt` (TBD)
- Install frontend dependencies (verify that your node.js satisfies version in `frontend/package.json`):

`cd ./frontend && npm run install`

## How to Run
### MongoDB
To start mongodb:
`sudo mongod --config /etc/mongod.conf`

To see console:
`sudo mongo`

### Server
Python 3.5 is required to run server:
`python /path/to/backend/backendAPI.py`

Or use my favourite Python IDE [Pycharm](https://www.jetbrains.com/pycharm/).

### Frontend
To run frontend on the default port in development mode locally, use command:

`cd ./frontend && npm run dev`

Open your browser:
[localhost:8080](http://localhost:8080/)

