This note includes some important concepts confused me when I tried to understand Neural Network. I have the most interesting and helpful information here with references.

### 1. The essensial components of ML -- linearity 
---
**Linearity and linear algebra**  

Linearity is the simplist and most intuitively interpretable relationship/model between variables. And Linear algebra is the mathmatical tool to represent and study linear functions.  
This part gives an explaination of the significance and interpretations of dot product of vector and vector as well as vector and matrix in the context of machine learning regime.


**1. Dot product**  
Vector and vector-- line or hyperplane  
* Linear regression/classification  
` 1q


### Q1: Why to introduce non-linearity into model
----- 
**From linear to non-linear [[1]]**  

   _The linearity is a strong assumption._
   >Linearity implies that for whatever target value we are trying to predict, increasing the value of each of our inputs should either drive the value of the output up or drive it down, irrespective of the value of the other inputs.
   
   Sometimes this makes sense! Say we are trying to predict _whether an individual will or will not repay a loan_. We might reasonably imagine that all else being equal, an applicant with a _higher income_ would be _more likely to repay_ than one with a lower income. In these cases, linear models might perform well, and they might even be hard to beat.

   However, in the case of image classification, _increasing the intensity (value)_ of the pixel always just _makes it more white._
   >If we use a linear model, we’d basically be saying that for each pixel, increasing its value (making it more white) must always increase the probability that the image depicts a dog or must always increase the probability that the image depicts a cat.
That seems ridiculous because we all know that you cannot make sense out of an image without accounting for the **interactions among pixels.**  

### Q2: What is difference between regresssion and classification?

Similarity:
  * Supervised learning (inputs+labels)
  * Use a hyperplane:   
        Simplist case: linear regression, linear classification

















### Q2: How to introduce non-linearity into model_Activation function_ 
----
There are two enssecial ways to sovle the problem linearly non-separable.
This question could be answered from a range of interesting perspectives.  























[1]:http://d2l.ai/chapter_multilayer-perceptrons/mlp.html
[2]:https://towardsdatascience.com/multi-layer-neural-networks-with-sigmoid-function-deep-learning-for-rookies-2-bf464f09eb7f
