# Lung-nodule-segmentation-and-classification-using-U-Net-and-Efficient-Net

Refer this paper:
https://thesai.org/Downloads/Volume14No7/Paper_81-Lung_Nodule_Segmentation_and_Classification_using_U_Net.pdf


An algorithm has been proposed to segment the lungs in images by using
watershed algorithm and classify the images using Efficient-net architecture.
Unlabelled dataset is labelled by using FPN with Resnet-50 as backbone.
FPN extracts features from labelled images and provides these features as
input into a neural network classifier. The classifier predicts the class of
unlabelled images and these images are added to the dataset for model
training.
This model typically involves a series of preprocessing steps, such as
Gaussian blur, thresholding, erosion and contouring, to enhance and segment
the objects in the images. The Gaussian blur function smoothens the image
and reduces noise, while thresholding converts the image to black and white,
simplifying it for further processing. Contouring then isolates the objects
within the image by drawing lines around them. The model uses the FPN
architecture to extract features from the images when preprocessing is
completed.
The EfficientNet model is a state-of-the-art deep learning architecture
that has achieved exceptional results in image classification tasks, making it
a powerful tool for object recognition.
