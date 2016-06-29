# Paper: "Fast Training of Triplet-based Deep Binary Embedding Networks"

##People
Bohan Zhuang, Guosheng Lin, Chunhua Shen and Ian Reid.
Code author: Bohan Zhuang
This code is provided for non-profit research purpose only; and is released under the GNU license. 
For commercial applications, please contact Chunhua Shen http://www.cs.adelaide.edu.au/~chhshen/.

__This is the implementation of the following paper. If you use this code in your research, please cite our paper__

@inproceedings{zhuang2016fast,
  title={Fast Training of Triplet-based Deep Binary Embedding Networks},
  author={Zhuang, Bohan and Lin, Guosheng and Shen, Chunhua and Reid, Ian},
  journal={arXiv preprint arXiv:1603.02844},
  year={2016}
}

## Overview
./step1/ includes the code for the binary codes inference step. 
./lib/ includes the necessary codes for the network training. We inplement it using Theano. 
./preprocessing is the data preprocessing toolbox. 

## Training

The code is based on Ubuntu 14.04.
The main function is the ./step1/train.m file and modify the paths in that file. 


