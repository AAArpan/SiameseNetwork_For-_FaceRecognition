# SiameseNetwork_For_FaceRecognition
Implemented a Siamese model for face recognition task. Used as one shot learning this model was trained on fewer training dataset. The code is almost self explanatory though a specific type of file system is required. Have a look BELOW-   
There will be two main folder of name 'data' and 'application_data'
In data folder create three sub-folders 'anchor', 'positive' and 'negative'.
Anchor folder will contain all your face images (>= 300).
Positive folder will also contain your face images.
Negative one will hold all other different faces not similar to yours. I downloaded the dataset of LFW(Labeled faces in the wild) and extracted it to this folder.
The other 'application_data' folder will contain 2 sub folders 'input_image' and 'verification_images'. Keep 'input_image' folder empty and copy around 50 images from 'positive' folder and then paste it to 'verification_images' folder. These folders will be used in real time reognition task. 

SIAMESE NETWORK are a type of neural network architecture that learn to compare two inputs and output a similarity score. They consist of two identical subnetworks that share the same weights and are trained on pairs of inputs (e.g., images). During training, the network learns to produce similar output embeddings for similar inputs and dissimilar embeddings for dissimilar inputs.


