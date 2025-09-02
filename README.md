# Sign Language to Text Conversion using CNN and Biogeography-Based Optimizer (BBO)

# Problem Statement:
Communication barriers faced by the hearing- and speech-impaired community can be reduced using intelligent sign language recognition systems. The aim of this project was to develop an automated system that translates sign language gestures into readable text.

#Dataset & Preprocessing:
Collected a dataset of static sign language images representing different alphabets and gestures.
Preprocessing steps included resizing, normalization, and augmentation (rotation, flipping, scaling) to improve generalization.

# Model Development:
Implemented a Convolutional Neural Network (CNN) for feature extraction and classification of hand gesture images.
Integrated Biogeography-Based Optimizer (BBO) for hyperparameter tuning (learning rate, batch size, number of filters, dropout rates), improving convergence and performance.

# System Workflow:
User uploads an image of a sign language gesture.
The trained CNN model processes the image, classifies it, and outputs the corresponding text representation in real time.

# Results:
Achieved 99% accuracy with the base CNN model before optimization.
After applying BBO optimization, the model achieved 100% accuracy on the test dataset.
Demonstrated robust recognition performance across different sign gestures.

# Key Contributions:
Built an image-to-text conversion pipeline for sign language recognition.
Showcased the effectiveness of metaheuristic optimization (BBO) in boosting deep learning performance.
Provided a foundation for assistive technologies that bridge the communication gap between hearing-impaired individuals and the general population.
