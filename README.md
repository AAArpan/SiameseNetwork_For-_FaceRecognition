# SiameseNetwork_For_FaceRecognition
Implemented a Siamese model for face recognition task. Used as one shot learning this model was trained on fewer training dataset. The code is almost self explanatory though a specific type of file system is required. Have a look BELOW-   
# Libraries
Install the libraries on python using - !pip install tensorflow==2.4.1 tensorflow-gpu==2.4.1 opencv-python matplotlib
# File system
There will be two main folder of name 'data' and 'application_data'
1. In 'data' folder create three sub-folders 'anchor', 'positive' and 'negative'.
2. Anchor folder will contain all your face images (>= 300).
3. Positive folder will also contain your face images.
4. Negative one will hold all other different faces not similar to yours. I downloaded the dataset of LFW(Labeled faces in the wild) and extracted it to this folder.
5. The other folder of 'application_data' will contain 2 sub folders 'input_image' and 'verification_images'. Keep 'input_image' folder empty and copy around 50 images from 'positive' folder and then paste it to 'verification_images' folder. These folders will be used in real time reognition task. 
# ABOUT
SIAMESE NETWORK are a type of neural network architecture that learn to compare two inputs and output a similarity score. They consist of two identical subnetworks that share the same weights and are trained on pairs of inputs (e.g., images). During training, the network learns to produce similar output embeddings for similar inputs and dissimilar embeddings for dissimilar inputs.

![95aaa61862bb921dc92f549d3a242f6a](https://user-images.githubusercontent.com/108794407/222981916-2dc397aa-4221-4eb3-bd58-21c2334ed027.png)




In a one-shot learning scenario, the siamese network is trained on a small dataset of examples of each class. Once the model is trained, it can be used to recognize new instances of the same classes from only one or a few examples. This is why the siamese network is often referred to as a one-shot learning model.

Special thanks to - https://www.youtube.com/@NicholasRenotte
