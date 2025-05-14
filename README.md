# Image-caption-generator

------------------------------------------------------------------------------------------
Image caption generation system.

### Source code
https://drive.google.com/drive/folders/1PZfpOvPtCvy_a0zOqmHHrp_3kZNq4a68?usp=drive_link

### Technologies
- PIL image manipulation.
- Tensorflow - keras for image and text processing.
- Tensorflow - keras for building and training deep learning models.

### Project file structure:
- Data:
  - Flicker8k_Dataset – Dataset folder which contains 8091 images.
  - Flickr_8k_text – Dataset folder which contains text files and captions of images.
- models – It contains trained models.
- models_2 - It contains the final trained models.
- `descriptions.txt` – This text file contains all image names and their captions after preprocessing.
- `features.p` – Pickle object that contains an image and their feature vector extracted from the Xception pre-trained CNN model.
- `tokenizer.p` – Contains tokens mapped with an index value.
- `preprocessing.ipynb` - Python file to preprocess and extract features for images.
- `training.ipynb` - Python file to process text and build image caption generator.
- `testing.ipynb` – Python file for generating a caption of any image.
- `testing.py` - Python file to execute the image caption generator.

### Usage
First, access and download the folder from Drive.

### Requirements
- Modules and dependencies in `requirements.txt`
- Run `pip install -r requirements.txt`

### Image caption generator
- To run the `testing.py` script, use the following command in the terminal or command prompt:
- `python testing.py -i <image_path>`
  (image from "Data/Flicker8k_Dataset")

### Example
![image](https://github.com/user-attachments/assets/160ee9c8-0eac-4ebe-a68e-9747eb6f9270)




