# Machine Translation
This repository contains machine translation models based on seq2seq architecture. There are two models included: English to Spanish translation and English to French translation. Both models are trained on a large corpus of text data and are available for public use.

## English to Spanish Translation ##

The English to Spanish translation model is a relatively large model with ~23 million parameters. It achieves an accuracy of 97 percent on the test data. The model is based on a seq2seq architecture and uses an attention mechanism to focus on relevant parts of the input sentence.

To use the English to Spanish translation model, follow these steps:

1. Download the "English to Spanish" folder from the repository.
2. Download the pre-trained model stored in the releases section (right side of repo page).
3. Open the notebook and run the code.
## English to French Translation ##

The English to French translation model is a relatively small model with  ~1 million parameters that achieves an accuracy of 99 percent on its limited vocabulary. It is also based on a seq2seq architecture and uses an attention mechanism to focus on relevant parts of the input sentence.

To use the English to French translation model, follow these steps:

1. Download the "English to French" folder from the repository.
2. Open the notebook and run the code.

## Running the Notebooks on Google Colaboratory ##

Both models can be run on Google Colaboratory, a free online platform for running Jupyter notebooks. To run the notebooks on Google Colaboratory, follow these steps:

1. Upload the notebooks and files to your Google Drive.
2. Open Google Colaboratory and create a new notebook.
3. Mount your Google Drive to the notebook using the following code:
```javascript
from google.colab import drive
drive.mount('/content/drive')
```
4. Navigate to the folder where you uploaded the notebooks and files using the following code:
```shell
%cd /content/drive/MyDrive/your-folder-name
```
5. Run the code in the notebook.
