# subMFL: Compatible subModel Generation for Federated Learning in Device Heterogeneous Environment

* This repository contains the [Flower](https://flower.dev/) and [PyTorch](https://pytorch.org/) official implementation for the "[_subMFL: Compatible subModel Generation for Federated Learning in Device Heterogeneous Environment_
](https://link.springer.com/chapter/10.1007/978-3-031-48803-0_5)" paper. 

* __The authors:__ [Zeyneddin Oz](https://www.linkedin.com/in/zeyneddin-oz/), [Ceylan Soygul Oz](https://www.linkedin.com/in/ceylansoygul/), [Abdollah Malekjafarian](https://www.linkedin.com/in/abdollah-malekjafarian-39854210/), [Nima Afraz](https://www.linkedin.com/in/nimaafraz/), and [Fatemeh Golpayegani](https://www.linkedin.com/in/fatemeh-golpayegani-07373937/).

* [_Euro-Par: 29th International European Conference on Parallel and Distributed Computing - RAW 2023: 2nd Workshop on Resource Awareness of Systems and Society._](https://link.springer.com/chapter/10.1007/978-3-031-48803-0_5)


[Please click here to watch the presentation](https://www.youtube.com/watch?v=oXe3DuhHaq0&t=33s)

If you find it useful, you can cite this work as follows:

@inproceedings{oz2023submfl,
  title={subMFL: Compatible subModel Generation for Federated Learning in Device Heterogeneous Environment},
  author={Oz, Zeyneddin and Soygul Oz, Ceylan and Malekjafarian, Abdollah and Afraz, Nima and Golpayegani, Fatemeh},
  booktitle={European Conference on Parallel Processing},
  pages={52--64},
  year={2023},
  organization={Springer}
}

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

__Note:__ Due to some random behaviours in experiments such as the distribution of datasets, the outputs may not be exactly the same as it was in the paper. The main point needed to be focused on is despite preserved good metrics how participation can be increased by generating a list of submodels, while the pruning stage is completely on the server side without the need for any data instance. Besides, the main reason behind potential accuracy improvement on sparsed models is actually the over-parameterised of the dense model causes lesser performance. For more detail, please read the research paper. It will be shared after the presentation.

For feedback or more information, please do not hesitate to contact me.

### Contact:
* Zeyneddin Oz: zeyneddinoz@gmail.com


__Stay with science!__
