# twinNeuralNets
## Implementation of Twin Neural Networks for classification
##### Himanshu Pant, Jayadeva,Mayank Sharma, Sumit Soman
###### Department of Electrical Engineering, Indian Institute of Technology, Delhi, India

### Paper Abstract:
Twin Support Vector Machines (TWSVMs) have emerged as an efficient alternative to Support Vector Machines (SVM) for learning
from imbalanced datasets. The TWSVM learns two non-parallel classifying hyperplanes by solving a couple of smaller sized
problems. However, it is unsuitable for large datasets, as it involves matrix operations. In this paper, we discuss a Twin Neural Network (Twin NN) architecture for learning from large unbalanced datasets. The objective functions of the networks in the Twin NN are designed to realize the idea of the Twin SVM with non-parallel decision boudaries for the respective classes, while also being able to reduce model complexity. The Twin NN optimizes the feature map, allowing for better discrimination between classes. The paper also discusses an extension of the Twin NN for multiclass datasets. This architecture trains as many neural networks as the number of classes, and has the additional advantage that it does not have any hyper-parameter which requires tuning. Results presented in the paper demonstrate that the Twin NN generalizes well and scales well on large unbalanced datasets.

full manuscript https://www.sciencedirect.com/science/article/pii/S0925231219301602
###### An initial version of this manuscript is available on arXiv : https://arxiv.org/abs/1705.00347



Code author: Himanshu Pant
Code Version: 1.0.0
Code metadata:
{ "anaconda-cloud": {}, "kernelspec": { "name": "python3", "display_name": "Python 3", "language": "python" }, "language_info": { "name": "python", "version": "3.6.5", "mimetype": "text/x-python", "codemirror_mode": { "name": "ipython", "version": 3 }, "pygments_lexer": "ipython3", "nbconvert_exporter": "python", "file_extension": ".py" } }
