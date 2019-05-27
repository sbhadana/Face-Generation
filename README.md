# Face Generation

In this project, i have defined and trained a DCGAN on a dataset of faces. The goal is to get a generator network to generate new images of faces that look as realistic as possible!

The project is broken down into a series of tasks from loading in data to defining and training adversarial networks. At the end of the notebook, i was able to visualize the results of my trained Generator to see how it performs; the generated samples looks like fairly realistic faces with small amounts of noise.

Final Project [Notebook](/dlnd_face_generation.ipynb)


## 1. Installation

Download Anaconda

**Install** [Anaconda](https://docs.anaconda.com/anaconda/install/) (windows)on your machine. Detailed instructions:

## 2. Create and Activate the Environment

Please go though this [doc](https://conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html) before you creating an environment.
After that create a environment using following command

```
conda create --name dcgan
```

Then activate the environment using following command

```
activate dcgan
```

#### Git and version control
These instructions also assume you have `git` installed for working with Github from a terminal window, but if you do not, you can download that first with the command:
```
conda install git
```

**Now, you can create a local version of the project**

1. Clone the repository, and navigate to the downloaded folder. This may take a minute or two to clone due to the included image data.
```
git clone https://github.com/sbhadana/Face-Generation.git
cd TV-Script-Generation
```

2. Install PyTorch and torchvision; this should install the latest version of PyTorch.

	- __Linux__ or __Mac__:
	```
	conda install pytorch torchvision -c pytorch
	```
	- __Windows__:
	```
	conda install pytorch -c pytorch
	pip install torchvision
	```

3. Install a few required pip packages, which are specified in the requirements text file (including OpenCV).
```
pip install -r requirements.txt
```

4. Now run the project using following command, check you default browser and open dlnd_face_generation.ipynb file

```
jupyter notebook
```
