PyTorch Code for the paper at ICLR2020:
**Title**: *DivideMix: Learning with Noisy Labels as Semi-supervised Learning*



**Experiments**

Run the dataloader_cifar.ipynb file experiment directly in jupyter Notebook.

or

First, please create a folder named *checkpoint* to store the results.
`mkdir checkpoint`
Next, run 
`python Train_cifar.py --data_path --dataset` 



We also have made some changes for cifar-10:

`python Train_cifar_refinement_for_low_noise.py ` 

`python Train_cifar_refinement_with_CNN.py ` 



