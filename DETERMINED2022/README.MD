# DETERMINED 2022 

This folder contains the material for the lectures held at the DETERMINED 2022 summer school at the University of Ljubljana (financed by the European Project [PARENT](https://parenth2020.com)) held end of August 2022. Each folder contains material as presentations, code for the hands-on sessions and further reading material that students can consult even after the school has finished.

In the folder [Reading Material on Machine Learning](https://github.com/toelt-llc/MSCA-ITN-PARENT/tree/main/DETERMINED2022/Reading%20Material%20on%20Machine%20Learning) Arnaud Gucciardi has compiled a list of resources that he, as student, has used during his studies of Machine Learning and that will be useful to students that begins their work on machine learning. More material will be also added with time.

# Pedagogical Concept

The goal of the lectures is **not** to make students experts. This is not possible in such a short time frame. The goal is to make fundamentals in how to do research in machine learning clear. What are the best practices, what are the challenges, and so on. We hope that after this school, the students will be aware of the difficulties linked to use machine learning corretly, and thus will be careful when setting up their research project that have a machine learning component.

# Hands-on Jupyter notebooks

All the hands-on examples have been developed in [Jupyter notebooks](https://jupyter.org). For your convenience you will find below links to each one. They will open in [Google Colab](https://colab.research.google.com), an online environment where you can try the notebook without having to install anything on your laptop or desktop. 

To run the notebooks you will need a google account. You can get one for free [HERE](https://accounts.google.com/signup/v2/webcreateaccount?flowName=GlifWebSignIn&flowEntry=SignUp).

# Introduction to Model Validation and Unbalanced Datasets

In this lecture we will look at what is model validation and how to deal with unbalanced datasets (and what they are). A small programming experiment is available to see what happens when you use the Hold-out approach (see lecture) multiple times with different random number generator seeds.

- [Effect of splitting the dataset multiple times Hands-on Code](https://colab.research.google.com/github/toelt-llc/MSCA-ITN-PARENT/blob/main/DETERMINED2022/Introduction%20to%20model%20validation%20and%20unbalanced%20datasets/.ipynb_checkpoints/Metrics_Distributions_due_to_Datasetsplit-checkpoint.ipynb)

# Introduction to Python and scikit-learn

# Introduction to Neural Networks

This is mostly a thoretical lecture with some hands-on with online tools. No Python coding is strictly required. Nonetheless, I implemented a demo in Python of the Gradient Descent in one-dimension to try. It is useful to see how this optimizer (that by the way is not even available any more out of the box in TensorFlow Keras) works.

- [A demonstration of the gradient descent method in one-dimension](https://colab.research.google.com/github/toelt-llc/MSCA-ITN-PARENT/blob/main/DETERMINED2022/Introduction%20to%20Neural%20Networks/code/gradient_descent.ipynb)

# Introduction to TensorFlow Keras

For this lecture I prepared two notebooks that are very easy and can be tested in Google Colab without installing anything on your laptop. By clicking the links below an instance of Google Colab will open with the notebook ready for you to try.

- [Your first neural network with Keras](https://colab.research.google.com/github/toelt-llc/MSCA-ITN-PARENT/blob/main/DETERMINED2022/Introduction%20to%20TensorFlow%20Keras/code/Easy_Network_with_Keras.ipynb)

- [Your first Convolutional Neural Network with Keras](https://colab.research.google.com/github/toelt-llc/MSCA-ITN-PARENT/blob/main/DETERMINED2022/Introduction%20to%20TensorFlow%20Keras/code/First_Example_of_a_CNN_(CIFAR10).ipynb)
