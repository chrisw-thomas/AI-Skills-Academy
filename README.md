# AI-Skills-Academy

In this lab we will build a machine learning model that is able to recognise handwritten numbers. We will use a popular dataset for this known as MNIST (see: http://yann.lecun.com/exdb/mnist/), a collection of labelled images of handwritten digits.

## Prerequisities:
- Watson Studio account

## Step 1: Create a new project in Watson Studio
Navigate to your Watson Studio instance and create a new "Data Science" project.

If we have time at the end of the lab or if you want to experiment more in your own time there is another exercise that uses the Watson Machine Learning service to tackle the same problem using GPU acceleration.

Name your project e.g. *mnist-classifier* and create it.

## Step 2: Working with the Jupyter notebook
Within your new Data Science project, select the "Add to project" button and then select a "Notebook" asset. 

Select "From URL" from the tabs along the top, and insert the URL to the Jupyter notebook in this repository. 

`https://github.com/chrisw-thomas/Test/blob/master/machine_learning_v1.1.ipynb`

Selecting the "Default Python 3.5 Free (1 vCPU and 4GB RAM)" option will provision a virtual machine to run your Jupyter notebook from. 

**Note:** The dialogue may change in the future. Simply select the free vCPU option.

If you have any problems loading the notebook from the URL simply download the notebook to your laptop and use the "From file" option.

Before you start working through the lab select the Kernel->Reset & Clear Output menu option to ensure you start with a clean notebook.

## Step 3: Work through the lab
Work your way through the lab in the notebook by running each cell and following the suggestions in the notebook.

## Further exercise - time permitting
If you have time after completing this lab you can run through the exercise documented at the following URL which will take you through the process of building a model using the Watson Machine Learning service.

`https://github.com/FarrandTom/wml-tf-mnist-classifier`

__Note:__ if you do this additional exercise then, at the appropriate point, you should create a new set of Cloud Object Storage credentials with the HMAC option selected and use those. The credentials created for you by default will not work.
