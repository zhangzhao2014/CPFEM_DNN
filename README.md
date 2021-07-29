# Modeling micromechanics of polycrystalline metals by deep neural network
## Background
This code is a demo of paper Modeling micromechanics of polycrystalline metals by deep neural network. <br />
We presente DNN model to predict the stress-strain curves of polycrystalline SnSb alloy under uniaxial tensile conditions. Compared with traditional crystal plasticity finite element method, DNN can save up 99.8% computational time. <br />
 ![image](https://github.com/zhangzhao2014/CPFEM_DNN/blob/main/images/Runtime_comparison.png)<br />
Fig.1. Runtime comparison between CPFEM and DNN model
## Usage
Download DNN_Built_Version.ipynb and run it in Anaconda.<br />
Data folder is the data you should use to train the DNN models.<br />
Trained folder is the DNN model we have trained will.<br />
Loss folder is the training loss.<br />
Requirement.txt is the package you should install when you run the demo. <br /> 
## Requirements
Anaconda     =4.8.0 <br />
Python       =3.6<br />
Numpy        >= 1.19.5<br />
Pytorch      >= 1.8.1<br />
Matplotlib   >=3.1.1<br />
## Contributing
We appreciate all contributions. If you are planning to contribute back bug-fixes, please do so without any further discussion.<br />
If you plan to contribute new features, utility functions or extensions to the core, please first open an issue and discuss the feature with us. Sending a PR without discussion might end up resulting in a rejected PR, because we might be taking the core in a different direction than you might be aware of. <br />
Contact email:zhangzhao3725@163.com 

