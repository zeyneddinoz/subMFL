# subMFL: Compatible subModel Generation for Federated Learning in Device Heterogeneous Environment

* This repository contains the [Flower](https://flower.dev/) and [PyTorch](https://pytorch.org/) official implementation for the "_subMFL: Compatible subModel Generation for Federated Learning in Device Heterogeneous Environment_
" paper. 

* __The authors:__ Zeyneddin Oz, Ceylan Soygul Oz, Abdollah Malekjafarian, Nima Afraz, and Fatemeh Golpayegani.

* _Euro-Par: 29th International European Conference on Parallel and Distributed Computing - RAW 2023: 2nd Workshop on Resource Awareness of Systems and Society._

## Dependencies:

{"flwr": "0.19.0", 
"torch": "1.13.1+cu117", 
"torchvision": "0.14.1+cu117", 
"numpy": "1.24.1", 
"pandas": "1.5.3", 
"json": "2.0.9", 
"matplotlib": "3.6.3"}

For the flower library first install:

sudo pip install -U flwr["simulation"]

Then:

sudo pip install -U flwr==0.19.0


## Usage:

* Run the juypter notebooks files separately in different folders. The required libraries will be installed and results will be saved automatically. 

__Note:__ Due to some random behaviours in experiments such as the distribution of datasets, the outputs may not be exactly the same as it was in the paper. The main point needed to be focused on is despite preserved good metrics how participation can be increased by generating a list of submodels, while the pruning stage is completely on the server side without the need for any data instance. Besides, the main reason behind potential accuracy improvement on sparsed models is actually the over-parameterised of the dense model causes lesser performance. For more detail, please read the research paper.

For feedback or more information, please do not hesitate to contact me.

### Contact:
* [Zeyneddin Oz](https://www.linkedin.com/in/zeyneddin-oz/): zeyneddin.oz@ucdconnect.ie or zeyneddinoz@gmail.com

__Stay with science!__
