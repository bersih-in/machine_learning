
# Bersih.in Machine Learning Development

This part contain several file to building 2 model that we created using CNN to verify the authenticity of the taken picture of the garbage piles(garbage detection model). In addition, we will also build a model using CNN to determine the severity and urgency of the garbage pile in the reported location(garbage severity model).


## Authors

- [@alifabdulrauf](https://github.com/AlifAbdulRauf)
- [@feliciaaustin](https://github.com/Feliciaaustin)
- [@graceaprilia](https://github.com/GraceAprilia)



## Installation

To replicate our project, you can follow the steps below. 

- Open your google colaboratory and Google Drive
- Download the notebook .ipynb file for each model and upload it to your google colaboratory 
- Download the dataset for each model and upload it to google drive
- Change the code on each notebook by adjusting the dataset path on your Google Drive 
- Run the .ipynb file on your google colaboratory
- Download the model that has been saved from the google colaboratory directory

If there are libraries that are not installed, you can follow the following command

```bash
  pip install "package_name"

```
check on the link below :

[How to use pip install](https://pip.pypa.io/en/stable/installation/)

    
## Result 

### Model Accuracy

The following are the results obtained accuracy we got after the training process.

#### Garbage Detection(Model 1)
```plaintext
Train Accuracy: 0.95
Validation Accuracy : 0.95
``` 

#### Garbage Severity(Model 2)
```plaintext
Train Accuracy: 0.95
Validation Accuracy : 0.91
