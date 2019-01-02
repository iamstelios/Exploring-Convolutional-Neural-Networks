# Exploring Convolutional Networks
### Part of [Machine Learning Practical (University of Edinburgh)](https://www.inf.ed.ac.uk/teaching/courses/mlp/) coursework

## [**Report**](https://github.com/iamstelios/Exploring-Convolutional-Neural-Networks/blob/master/Exploring%20Convolutional%20Networks.pdf)

### **Abstract:**

Convolutional Neural Networks (CNN) are considered state-of-the-art for analyzing visual imagery. However for machine learning beginners can seem intimidating. First, CNN's two main components: Convolutional Layers and Pooling Layers, are explained in an implementation centric context, that also discusses underlying memory and efficiency issues. Then context expanding methods: striding, dilating and pooling are explored more deeply.

Their hyperparameters are investigated, together with other questions researched. Using the EMNIST dataset we train and evaluate a number of different models. Convolution with none of the context expanding methods, performs at much slower than the rest, indicating that the methods are indeed helpful for CNN. The number of filters affecting the performance of each method directly. The Average Pooling seems to outperform Max pooling unlike most of the latest trends. Striding has the lowest performance when compared to the other methods. Dilation generally outperforms the other trained models. Finally, a new pooling layer that combines max and average pooling was introduced and shows promising results.

### **Measurements:**
The measurement results from the experiments refered in the article can be found in the measurements folder in a *csv* form.