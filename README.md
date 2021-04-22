Requirements:
- Install Python 3+ (I used 3.9 64bit) and add its path to the system environment
- use pip script to install the following packages: (ex .: python -m pip install networkx)
    - networkx
    - matplotlib
    - jupyter

To Run:
- Open a terminal and navigate to the project root folder
- then run jupyter using "jupyter notebook" command
- Click on the double play icon (>>) to code get executed.

Add Test case:
I have added two test cases for demonstration. If you want to add another test case:
- create a text file in the project root directory
- in the first line type starting node
- in the next line add topology in JSON format, for example:

A
{"A": [0,1,2], "B": [1,0,0], "C": [2,0,0]}

A, B, C are our nodes, and the list in front of them are their wights ordered by the English alphabet. 0 means there is no connection.

Limitation:
- number of nodes is limited to a maximum of 26 (English alphabets)
- input validation has not been implemented
