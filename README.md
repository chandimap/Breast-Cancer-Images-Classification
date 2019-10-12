Invasive Ductal Carcinoma (IDC), also known as Infiltrating Ductual Carcinoma is a cancer that began growing in a milk duct and has invaded the fibrous or fatty tissue of the breast outside the duct.

IDC is the most common form of breast cancer, representing 80% of all breast cancer diagnosis.

This dataset consists of 5547 of breasst histology images of size 50 X 50 X 3.

Cancerous Images (IDC: Invasive Ductal Carcinoma) VS Non-IDC Images were classified.

VGG16 architecture was used for transfer learning. 

New images were generated by rotations, translations and zoom to prevent overfitting the model to the training data.

90% / 10% split for the training and validation data. 

An accuracy of 80% on the validation data was achieved from traning the model for 40 epochs with data augmentation.
