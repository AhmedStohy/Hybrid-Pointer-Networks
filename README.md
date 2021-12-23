
[![PWC](https://img.shields.io/endpoint.svg?url=https://paperswithcode.com/badge/hybrid-pointer-networks-for-traveling/traveling-salesman-problem-on-tsplib)](https://paperswithcode.com/sota/traveling-salesman-problem-on-tsplib?p=hybrid-pointer-networks-for-traveling)

# Hybrid Pointer Networks
Sep, 2021
<img src="Resourses/TSP.gif" align="right" width = "350"/>
### Description
PyTorch implementation of "Hybrid Pointer Networks for Traveling Salesman Problems Optimization"<br>
Ahmed Stohy, Heba-Tullah Abdelhakam, Sayed Ali, Mohammed Elhenawy,  Abdallah A Hassan, Mahmoud Masoud ,Sebastien Glaser and Andry Rakotonirainy<br>
PLOSONE : [https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0260995](https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0260995) <br>
<br>
<br>
<br>
<br>

## Dependencies
* Python >= 3.7.10
* NumPy
* [PyTorch](http://pytorch.org/) == 1.7.1
* Matplotlib (optional, only for plotting)

## Benchmark
Sample instance form TSBLIB benchmark data fnl4461<br>
<img src="Resourses/fnl4461.jpg" align="right" width = "350"/> 

### Guidelines
1. Network Training (Tesla P100-PCIE-16GB) <br>
   For training TSP50 : Run notebook hpn-smallsize-sumagg inside small folder
2. Network Testing <br>
TSPSmall : Run notebook hpn-smallsize-test.<br>
TSPLarge : Run notebook hpnlarge-test.<br>
3. The Checkpoint file besides each training notebook<br>
<br>
<br>
<br>
<br>

## Acknowledgements<br>
Thanks to [qiang-ma/graph-pointer-network](https://github.com/qiang-ma/graph-pointer-network) for getting me started with the code for the Graph Pointer Network.

This repository contains [xbresson/TSP_Transformer](https://github.com/xbresson/TSP_Transformer) adaptations, and I'd like to thank you for making your code available.


