# Image-caption-generator

------------------------------------------------------------------------------------------
Hệ thống tạo chú thích (caption) cho hình ảnh.

### Source code
https://drive.google.com/drive/folders/1PZfpOvPtCvy_a0zOqmHHrp_3kZNq4a68?usp=drive_link

### Công nghệ sử dụng
- Thao tác với hình ảnh PIL.
- Tensorflow - keras để sử lý hình ảnh và văn bản.
- Tensorflow - keras để xây dựng và huấn luyện mô hình học sâu.

### Project file structure:
- Data:
  - Flicker8k_Dataset – Dataset folder which contains 8091 images.
  - Flickr_8k_text – Dataset folder which contains text files and captions of images.
- models – It contains trained models.
- models_2 - It contains the final trained models.
- descriptions.txt – This text file contains all image names and their captions after preprocessing.
- features.p – Pickle object that contains an image and their feature vector extracted from the Xception pre-trained CNN model.
- tokenizer.p – Contains tokens mapped with an index value.
- preprocessing.ipynb - Python file to preprocess and extract features for images.
- training.ipynb - Python file to process text and build image caption generator.
- testing.ipynb – Python file for generating a caption of any image.
- testing.py - Python file to execute the image caption generator.

### Sử dụng
Đầu tiên, truy cập và tải folder từ Drive.

### Requirements
- Modules and dependencies in `requirements.txt`
- Run `pip install -r requirements.txt`

### Image caption generator
- Để chạy script testing.py, sử dụng lệnh sau trong terminal hoặc command prompt:
- python testing.py -i <image_path>
- (image from "Data/Flicker8k_Dataset")

### Example
![image](https://github.com/user-attachments/assets/160ee9c8-0eac-4ebe-a68e-9747eb6f9270)




