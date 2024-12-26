# SPOT
Medical Image Diagnosis Model via Neural Networks 

Install the images here: https://www.kaggle.com/datasets/kmader/skin-cancer-mnist-ham10000 

The SPOT Acronym…

S - Smart Technology 
P - Pioneering Healthcare Solutions
O - Open Access for All
T - Transformative Impact

When doctors analyze medical images, different doctors may arrive at different conclusions. This variability may occur with different doctors on the same situation (inter-observer variability) or even with the same doctor in different situations (intra-observer variability). The effects of these differences on patients can be harmful, as these variables can cause over-diagnosis or under-diagnosis. To solve this, we utilized modern technologies to create a software that can aid physicians in their diagnosis of patients’ conditions, which could mean better, more accurate medical diagnoses.

We aimed for our software to:

Reduce variability in physician-based diagnosis.
Be accurate
Be easily adaptable different conditions
Provide a good UI/UX for the user’s satisfaction

We used the HAM10000 dataset, a large collection of “multi-source dermatoscopic images of common pigmented skin lesions.”
We used Python techniques in order to modify our data, creating multiple variations of them. This process is called data augmentation, and played a key role in our model’s training.
We built a neural network model using Google’s machine learning API, called TensorFlow.


<img width="1088" alt="Screenshot 2024-12-21 at 7 57 52 PM" src="https://github.com/user-attachments/assets/a2260bcc-fe93-4e72-a23c-87d9a221caa9" />

Our model demonstrates high levels of accuracy and adaptability, being able to detect many different types of skin cancers using images of skin lesions. Though we trained the SPOT model on a dermatology dataset for the purposes of this presentation, our model can be easily trained on any sufficient imaging data, such as CT scans of the brain or mammographic images. Our model that uses 21st century cutting edge technology, was created using proper software development objectives, development, implementation, and testing.

Credits:

[1] Noel Codella, Veronica Rotemberg, Philipp Tschandl, M. Emre Celebi, Stephen Dusza, David Gutman, Brian Helba, Aadi Kalloo, Konstantinos Liopyris, Michael Marchetti, Harald Kittler, Allan Halpern: "Skin Lesion Analysis Toward Melanoma Detection 2018: A Challenge Hosted by the International Skin Imaging Collaboration (ISIC)", 2018; https://arxiv.org/abs/1902.03368

[2] Tschandl, P., Rosendahl, C. & Kittler, H. The HAM10000 dataset, a large collection of multi-source dermatoscopic images of common pigmented skin lesions. Sci. Data 5, 180161 doi:10.1038/sdata.2018.161 (2018).
