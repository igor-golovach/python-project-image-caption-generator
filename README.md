# Python Project Image Caption Generator
Python based project implementing CNN and LSTM.

Image caption generator is a task that involves computer vision and natural language processing concepts to recognize the context of an image and describe them in a natural language like English.

## Dataset
This dataset is built from the images pulled from different Flickr groups is used to pull this dataset. It is mainly categorized into two parts.
* Flickr 8k Photo Caption Dataset (Flickr8k_Dataset.zip, Flickr8k_text.zip)
* Flickr 30k Photo Caption Dataset (Flickr30k_Dataset.zip, Flickr30k_text.zip)

## Process Flow
Steps followed for the algorithm implementation
1. Data Collection
2. Data Cleaning
3. Data integration
4. Data Pre-processing of images
5. Data Pre-processing of Captions
6. Data Modelling
7. Model Evaluation

## How To Run
If you have installed, you should now be able to run the tutorials in the Python Notebooks:

````
> cd ~/development/python-project-image-caption-generator/  # Your installation directory.
> jupyter lab
````

This should start a web-browser that shows the list of tutorials. Click on a tutorial to load it.

## *Requirement*
		image==1.5.33
		load==2020.12.3
		keras==2.9.0
		matplotlib==3.5.2
		pillow==9.2.0
		numpy==1.23.0
		pandas==1.1.4
		tqdm==4.47.0 
		tensorflow==2.9.1 
		jupyterlab==3.4.3