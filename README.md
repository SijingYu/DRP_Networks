# DRP Program - Networks
Code done under Directed Reading Program about network/graph theory <br>
thanks to help from my mentor Brandon Alexander

Book used:
### Networks 2nd Edition by Mark Newman

Pdf of old version
http://math.sjtu.edu.cn/faculty/xiaodong/course/Networks%20An%20introduction.pdf

A paper by Newman to start: <br> 
### The structure and function of complex networks


Percolation achieves algorithm described in
A fast Monte Carlo algorithm for site or bond percolation https://arxiv.org/pdf/cond-mat/0101295.pdf
first with square lattice percolation, then percolation on a real graph by package Networkx. However, it is computational expensive being done iteratively. <br>

To run the code, in terms of assigning N = 10^n nodes, I recommend setting the probability of having an edge around or less than 10^(-n) considering runtime.
