# Breast-Cancer-Detection-Using-Machine-Learning-and-CNN-
Introduction
Deep learning, particularly Convolutional Neural Networks (CNNs), has revolutionized medical technology by offering powerful tools for diagnostics. However, the limited availability of large and diverse datasets poses challenges in effectively training CNNs for breast cancer detection.

Objective
This project aims to enhance breast cancer detection through cutting-edge technology, leveraging the transformative potential of CNNs and transfer learning methodologies. By addressing the challenges posed by dataset size limitations, the goal is to contribute significantly to early and precise breast cancer detection, ultimately improving healthcare outcomes.

Approach
Utilizing transfer learning techniques, the project adapts pre-trained models like RetinaNet for the subtle task of binary mass and non-mass classification crucial for accurate breast cancer identification. The integration of advanced image processing methods enhances data quality and reduces noise in medical images, further refining the sensitivity and reliability of cancer discovery.

Experiment Results
After a set number of training epochs, the machine learning model achieved an impressive accuracy of 97%. This underscores the effectiveness of the model in training, convergence, and generalization from data. However, constant monitoring is essential for real-world application, considering variations in the significance of accuracy across different issue areas.

Impact
This project's innovative approach offers promising advancements in breast cancer diagnostics. By seamlessly integrating sophisticated image processing techniques with state-of-the-art CNN technologies, it bridges critical gaps in cancer detection, empowering healthcare professionals with dependable tools for early diagnosis and effective treatment. Ultimately, this contributes to the global efforts against breast cancer, promising better healthcare outcomes and improved patient care.

Repository Structure
Code: Contains Python scripts for model training, evaluation, and inference.
Datasets: Includes sample breast biopsy image datasets used for training and testing.
Documentation: Provides detailed documentation on project methodology, experimental setup, and results.
Models: Contains pre-trained models and model checkpoints for reproducibility and further experimentation.

To use this project:

You'll need python3 to run the program

I've included the preprocessed image data. You can download it from here. Now place the 5 files that you just downloaded with the folder with the .py file

Use pip install package-name to install the below packages

You need to have the following python packages installed

keras
tensorflow (Both CPU or GPU version should do)
PIL
numpy
You can modify the default hyparameters by modifying the variables between the # in the first few lines line

To run the program, navigate to the folder in command line and use the following command,

python BreastCancer.py
I've also included a pretrained model. To test your own image or one of the samples using it, paste the image in the folder with the .py file and rename it as my_image.jpg, then during execution choose to test your own image by following the on screen commands
