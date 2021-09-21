# Hybrid Pointer Networks
Sep, 2021
<img src="Resourses/TSP.gif" align="right" width = "350"/>
### Description
PyTorch implementation of "Hybrid Pointer Networks for Combinatorial Optimization Problems"<br>
Ahmed Stohy, Heba-Tullah Abdelhakam, Sayed Ali, Mohammed Elhenawy,  Abdallah A Hassan, Mahmoud Masoud ,Sebastien Glaser and Andry Rakotonirainy<br>
ArXiv : [https://arxiv.org/pdf/2103.03012.pdf](https://arxiv.org/pdf/2103.03012.pdf) <br>
<br>
<br>
<br>
<br>

### Benchmark
Sample instance form TSBLIB benchmark data fnl4461<br>
<img src="Resourses/fnl4461.jpg" align="right" width = "350"/> 

### Guidelines
1. Network Training (Tesla P100-PCIE-16GB) <br>
2. Network Testing <br>
TSPSmall : Run notebook hpn-smallsize-test.<br>
TSPLarge : Run notebook hpnlarge-test.<br>
3. The Checkpoint file beside each training notebook<br>
<br>
<br>
<br>
<br>
## Acknowledgements
Thanks to [pemami4911/neural-combinatorial-rl-pytorch](https://github.com/pemami4911/neural-combinatorial-rl-pytorch) for getting me started with the code for the Pointer Network.

This repository includes adaptions of the following repositories as baselines:
* https://github.com/MichelDeudon/encode-attend-navigate
* https://github.com/mc-ride/orienteering
* https://github.com/jordanamecler/PCTSP
* https://github.com/rafael2reis/salesman


