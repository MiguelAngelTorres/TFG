# TFG: Una estrategia para bolsa basada en algoritmos evolutivos y su implementación en una plataforma de trading

Bacherlor's Thesis at University of Granada (UGR) about evolving algorithm for prediction on stock market.

The algorith is based on genetics programming, that means that a population (some decision trees with stock indicators) is evaluated on a period (with the framework backtrader) an, depending of the score, crossover and mutation are made. The process is iterated a variable number of times.

Further information can be found on TFG.pdf

## Requirements 

This project has been developed on Ubuntu. Using it with other SO could fail. First at all, you need to ensure you have installed python3 and pip3 as they are the main tools used for this project. For test them run:

python3 -V
pip3 -V

If you have not installed any of them, you can do it by writting the command:

sudo apt-get install python3
sudo apt-get install python3-pip

## Installation

The source code can be download with:

git clone https://github.com/MiguelAngelTorres/TFG

Once downloaded, go into the main folder. You should activate a python enviroment for protect you older packages with:

source env/bin/activate

Now, install all dependences with pip3:

pip3 install -r dependencies.txt

## Usage

The code is placed at the folder named genetreec. The main file is genetreec.py. You will need to import this to use the algorithm. An example is given in exec_test.py. You can run it by writtin:

genetreec/exec_test.py <number of trees> <number of iterations> <symbol> <start train date> <end train date> <start test date> <end test date>

For example:



