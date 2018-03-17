# blockchain
My blockchain implementation as the learning outcome of [Learn Blockchain by Building One](https://hackernoon.com/learn-blockchains-by-building-one-117428612f46)

Blockchain technique is not an obscure technique. It is powerful but has many restrictions. They make the explaination of it complicated to flicker the people who are greedy and refuse to dig out the technical details.

## How to Run
Before running, make sure to have Python3 and install all the packages imported.
### Run a single node
```
$ export FLASK_APP=blockchain.py
$ flask run
```
### Run as a cluster in one machine with different ports
In terminal 1,
```
$ export FLASK_APP=blockchain.py
$ flask run
```
In terminal 2,
```
$ export FLASK_APP=blockchain.py
$ flask run --port=5001
```
## How it works as a 'blockchain'
TODO
