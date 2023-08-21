## Setup instructions

This Python course requires a computer that is set up with the appropriate software and tools. This document provides the steps in order to prepare your own computer. 

## What tools will we be using?

The core tools are:

* Python 3.6+ (for new installations we will use 3.9) 
* Anaconda Distribution
* Jupyter Lab/Notebook

We will also use a large collection of third-party Python packages and libraries. A full list can be found in the [`environment.yml`](https://github.com/TiesdeKok/acctg-579b/blob/master/environment.yml) file. 

---

## A few common questions:

> But I already have Python installed on my computer, I surely don't need to do all this?

I'd like everyone to complete the steps, even if you already have Python set up on your computer. Doing so will make sure that everyone has the same setup, this makes solving technical issues a lot more managable. You can have multiple Python installations / Conda environments on your computer, so you don't need to uninstall your current setup. 

One exception is if you already have a Python 3.6+ version of Anaconda installed on your computer, in that case you can skip step 1.

> Do I have to use Jupyter? I'd much rather use tool .... 

There are many ways to write Python code and ultimately I recommend you to use whatever you want. However, I'd prefer if you could use Jupyter Lab or Jupyter Notebooks during this Python course. This makes it easier for everyone to work together and also makes it easier to solve technical problems as they arise. The material is not specific to Jupyter so after the course you switch back to whatever tool you prefer without problems.

> I keep getting errors?! What do I do... 

Some of you might encounter problems when following the steps below, but don't worry, I am here to help! Please email me and I will come to your rescue as soon as possible! :) 

> Everything that you show is on Windows, but I am on Mac OS / Linux? 

All of my demonstrations will be on Windows, however, I'll try to include pointers in cases where I know there are differences between Windows and Unix (i.e. Mac OS and Linux). You should be able to following along with any operating system without too much trouble. 

> How long should it take me to complete these steps?

On a decent computer it shouldn't take more than 30 to 45 minutes to get everything set up. Installing Anaconda and the Conda environment will take some time, but besides that everything should be relatively quick. This is, however, conditional on you not running into any problems. 

**I strongly recommend to try and complete these steps as soon as possible, this gives us time to resolve any problems before the course starts.**  

---

## Setup steps:

###  **Step 0:** watch my primer on using the command line / terminal: 

> How to change directory using the command line or terminal:  
> 
> [How to change directory using the command line or terminal](https://youtu.be/1rUFqkRQkok)

###  **Step 1a:** install the Anaconda Distribution with Python 3.9.

**NOTE:** The video mentions Python 3.7, however, you are encouraged to install whatever the most current version of Anaconda is (3.9 at the time of writing).

> How to install the Python Anaconda Distribution:  
> 
> [How to install the Python Anaconda Distribution](https://youtu.be/_hsPV5ZZoJo)

###  **Step 1b:** learn how to interact with the Anaconda Distribution.

> How to interact with Python Anaconda Distribution:  
> 
> [How to interact with Python Anaconda Distribution](https://youtu.be/pu2vVRUUVao)

###  **Step 2:** download the acctg-579b Github repository

The `ACCTG-579B` GitHub repository includes the `environment.yml` file that you need for step 3. So make sure to create a local copy of this repository: [repository](https://github.com/TiesdeKok/acctg-579B)  

> How to create a local copy of a Github repository:  
> 
> [How to create a local copy of a Github repository](https://youtu.be/lnAAw97hVk0)

###  **Step 3:** create the `researchPython` conda environment

> **Note:** the `environment.yml` in the video is slightly different as the one will install. Just follow the steps in the video but anytime there is a mention of `limpergPython` replace it with `researchPython`. The steps are exactly the same (just the name and `environment.yml` are different). 
> 
> How to create and use a Python Conda environment:  
> 
> [How to create and use a Python Conda environment](https://youtu.be/CsqHyPMDSnc)

### **Step 4:** test environment by starting a Jupyter Lab session

> **NOTE:** anytime there is a mention of `limpergPython` replace it with `researchPython`.
> 
> How to start a Jupyter Notebook or Jupyter Lab server:  
> 
> [How to start a Jupyter Notebook or Jupyter Lab server](https://youtu.be/pHvIGIRhFM8)

### **Step 5:** run the test notebook to make sure everything is working

> **Steps:**
>
> 1. Make sure you have Jupyter Lab open with the `researchPython` activated (follow Step 4)  
> 2. In Jupyter Lab, find and open the notebook called `setup_test.ipynb` (should be in the folder you downloaded in step 2)  
> 3. Run all the cells in this notebook and check for any errors.  
> 4. Follow the steps provided in the notebook if you experience problems (or contact me if you get stuck).  
>
> _Note:_ we will get more familiar with Jupyter in our first class, but for now, you can run everything by clicking `run` in the top bar and then `run all cells` (or `cell` -> `run all` if you use Jupyter Notebook instead of Lab). 
