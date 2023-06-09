# Brain Tumor Classifier

The Brain Tumor Classifier is an application of deep learning techniques for the classification of brain tumors from magnetic resonance imaging (MRI) scans. This model has been developed to identify four major classes of brain tumors: meningioma, glioma, pituitary adenoma, and acoustic neuroma. The goal is to provide an automated and accurate solution for brain tumor diagnosis.

## Dataset

To train the Brain Tumor Classifier, a large dataset of correctly labeled brain MRI images was utilized. The dataset includes representative samples of the four types of brain tumors under consideration. The images were preprocessed to ensure data quality and reduce noise.

## Methods and Experiments

### Data Preprocessing

Prior to training, the dataset images underwent several preprocessing stages. One of the methods employed was Contrast Limited Adaptive Histogram Equalization (CLAHE), which enhanced the contrast of the images and made important features more prominent for classification.

### CNN from scratch

A convolutional neural network (CNN) architecture was developed from scratch to train the brain tumor classification model. This CNN consists of convolutional layers, pooling layers, and fully connected layers. The network was trained using the labeled image dataset.
Several experiments were conducted using the CNN trained from scratch. Various hyperparameters were tuned to optimize the model's performance. The obtained results were evaluated using standard evaluation measures such as accuracy, precision, and recall.

### CLAHE experiments

Experiments were also conducted using the CLAHE method to evaluate its impact on the model's performance. Different configurations of CLAHE parameters were adjusted to find the optimal combination.

### Pretrained models

In addition to the CNN from scratch, pretrained models such as VGG16, ResNet50, and InceptionV3 were also employed. These models were imported and adapted for brain tumor classification. The pretrained weights were frozen, and only the final layers were trained using the dataset.

## Explainability

To gain a better understanding of the model's decision-making, explainability analyses were performed. Intermediate activations and heatmaps were generated to highlight the relevant regions of the images that contributed to the classification.

### Intermediate Activations

Intermediate activations represent the responses of the intermediate layers of the neural network. These activations can be visualized to gain deeper insights into how the model processes the images and identifies brain tumors.

### Heatmaps

Heatmaps were generated to highlight the areas of the images that had the most influence on the brain tumor classification. Specific heatmaps were produced for glioma tumors and for images without tumors to compare the results.

## Conclusions

The Brain Tumor Classifier is a deep learning-based model for brain tumor classification. The achieved results demonstrate the effectiveness of the model in accurately recognizing and classifying brain tumors into the specified four categories. The explainability analyses provide a greater understanding of the model's decisions and can be beneficial for healthcare practitioners in interpreting the results.
