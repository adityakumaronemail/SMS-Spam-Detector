This projet requires Python 3.x to run.

How to install:

open command prompt with python install and type:

"pip install requirements.txt"

This step will download all the python libraries required to run the image steganography tool.

Refer to Video Demo.mp4 to see how to use the tool.

The Code folder stores all the code for both SMS Spam Detection Model and Image Steganography Tool

	spam.csv is the dataset used in this project.

	Spam Detection.ipynb is Jupyter Notebook containing the code and mentions the steps for building the SMS Spam Detection model

	model.pkl and vectorizer.pkl files are pickle files needed to run the tool.

	detector.py imports model.pkl and vectorizer.pkl and is used for Image Steganography Tool

	steg.py is the Steganography Tool and imports the detector.py file.

	Sample Images folder contains sample images that can be used for Image Stegangraphy tool