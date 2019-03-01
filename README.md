# Watson Studio GPU Notebook
Quick start guide to setting up a GPU powered notebook in Watson Studio and train a GAN.

Please download the `test.ipynb` or copy the `URL` to the notebook. We will need this to import this notebook to the Watson Studio Project.

## Getting Started:
Contact John Cohn, Amanda Mcclure and Yin Chen if you are interested in trying out the GPU enabled notebooks on Watson Studio (It is fantastic, you should give it a try!). As it is still in Beta you will need to get this sorted out before starting even if you have an IBM cloud account. 

Once you have access to the beta you will need to create/have an IBM cloud account. Start [here](https://www.ibm.com/cloud/watson-studio).

## Create a New Project
From the list of IBM cloud services, click on Watson Studio. I think it still says try Watson Studio.
On the next page simply create new `Standard` project. It will ask you some basic setup questions like name, description, COS storage (if needed) and the like. Hit create and you will be taken to the project dashboard page.

## Environment
The next step is to define your environment. For this you need to click on `New Environment Definition`. Here if you are registered for the beta you can choose GPU enabled environment. There are 2 choice of cards at the moment, K80 (Tesla) and V100. For the purpose of this tutorial K80 is okay.

## Notebook
Now you can go to the `Assets` tab and add a notebook. This is also where you can add your own data. We will cover this later during the tutorial. There are also community datasets, so go ahead and explore what datasets and tutorials are already there. 

Here you can actually pass the URL of the `test` notebook. The studio will download and instantiate your notebook automatically. That's it, you are good to go!

## Importing Data.
In order to get through this part of the tutorial please download the MNIST dataset from [here](http://yann.lecun.com/exdb/mnist/). Just the training dataset is needed with the labels. 

## `Important`
Please return to the enviroment tab after you are done and from the actions available for your resources please `STOP` the machines before leaving.

## Additional Links
1. https://dataplatform.cloud.ibm.com/docs/content/wsj/analyze-data/gpu-environments.html
2. https://medium.com/ibm-data-science-experience/working-with-ibm-cloud-object-storage-in-python-fe0ba8667d5f
3. The GAN model in the notebook is based on https://github.com/mafda/generative_adversarial_networks_101



__Akash Srivastava 03/01/2019__

