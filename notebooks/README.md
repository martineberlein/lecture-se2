# SE2 Lecture 'GrammarBasedFuzzing' README

## Getting started

- Download [Python 3.10](https://www.python.org/downloads/) (You will need at least >= Python 3.10)
   
  Some variation of
  ```
  $ sudo apt-get install python3.10
  ```
- Install [Graphviz](https://graphviz.org/download/) for your operating system.
  
  Some variation of
  ```
  $ sudo apt install graphviz
  ```
- Make a virtual environment (recommended)
  ```
  $ python3 -m venv venv
  $ source venv/bin/activate
  ```
- Verify virtual environment
  ```
  $ which python3
  ```
  This should point to the just created location.

- Install [Jupyter](https://jupyter.org/).
  ```
  $ python3 -m pip install jupyter
  ```
- Install dependencies.
  ```
  $ python3 -m pip install fuzzingbook numpy alhazen-py 
  ```
- Start the Jupyter server in the repository directory
  ```
  $ jupyter-notebook
  ```
  This opens a browser window at http://localhost:8888/tree

### Start:

- Navigate the directory, and start the jupyter-notebook `GrammarBasedFuzzing.ipynb`.


### Package Requirements:

- pandas, numpy, ipynb
- fuzzingbook
- jupyter-notebook
- sci-kit learn
- graphviz

### Maintainer

- Martin Eberlein (martin.eberlein@hu-berlin.de)
