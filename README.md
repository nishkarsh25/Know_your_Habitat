# Difficulty viewing large code files?

If you're having trouble viewing large code files on GitHub, you may find it helpful to download a ZIP file containing the entire repository. To do so, follow these steps:

1. Click on the green "Code" button on the repository page.
2. Select "Download ZIP" from the dropdown menu.
3. Save the ZIP file to your computer.

This can be particularly useful if you're experiencing issues with GitHub's web interface or if you need to access the repository without an internet connection. If you have any questions or concerns, please don't hesitate to contact us. 
<img width="624" alt="image" src="https://user-images.githubusercontent.com/117291117/231703905-7469ae09-6d82-4f77-ad05-fa29142ac9a8.png">
# Know your Habitat (CNN)

Develop a platform (web/android) that performs a reverse image search and identifies the objects present in the image. The user will click an image or make a short video, and the platform will classify the content of the image or video based on different classes such as:

- Name of the plant/flower/bird
- Academic buildings/offices/infrastructure
- Location (Mandi/South campus/North campus)

The code trains a convolutional neural network (CNN) using the VGG19 architecture to classify images into different categories. The model is trained using a dataset of images and their corresponding labels. After training, the model is saved and can be used for prediction. 

The code also includes an example of how to use the trained model to predict the class of an input image.

# Training data
## A10 block
<img width="331" alt="image" src="https://user-images.githubusercontent.com/117291117/228691462-6b706944-6720-43ca-9be1-eaed12f86fdb.png">
<img width="331" alt="image" src="https://user-images.githubusercontent.com/117291117/228691782-ecbdcc19-abac-42b9-ab51-d0b22b14ecbe.png">


## Oak Mess
<img width="331" alt="image" src="https://user-images.githubusercontent.com/117291117/228691844-c195610f-8337-4e46-8c3b-1a0c854fe662.png">
<img width="331" alt="image" src="https://user-images.githubusercontent.com/117291117/228691892-4e8accd8-1809-4dfd-b139-a65981d80f0c.png">

## Flower1
<img width="331" alt="image" src="https://user-images.githubusercontent.com/117291117/228691972-62cabad5-d53c-49ad-bb59-758b0ba392ba.png">
<img width="331" alt="image" src="https://user-images.githubusercontent.com/117291117/228692013-9fec1fa3-6321-45e9-9cfd-3d2a94664247.png">

### Similarly trained for other 5 classes having multiple images.

# Testing data
<img width="331" alt="image" src="https://user-images.githubusercontent.com/117291117/228690716-1e303515-1d80-487b-a657-61011dc00378.png">
<img width="331" alt="image" src="https://user-images.githubusercontent.com/117291117/228690805-91372af7-8335-436f-ba78-f02a32b15af4.png">

# Output
<img width="331" alt="image" src="https://user-images.githubusercontent.com/117291117/228690910-5a45ad1e-dd71-4655-ad8d-2cc640764306.png">
<img width="331" alt="image" src="https://user-images.githubusercontent.com/117291117/228690946-0755b4c4-d5fc-43ca-b235-c2208cb07f10.png">

