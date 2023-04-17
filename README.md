# Speech to Text Modality Conversion on MELD Dataset
This repository contains code for the paper "Modality Conversion from Audio to Text for Emotion Recognition from Speech" written by [Author Name] and [Author Name] from [University Name].

## Paper Summary
The paper proposes a modality conversion method from audio to text to improve the performance of emotion recognition from speech. The proposed method has been experimented on the MELD dataset which is a dataset for daily speech, and achieved a 44% WF1 score on this dataset.

The method consists of two steps:

1. Using an ASR API named VOSK to convert speech to text.
2. Using a BERT-based classifier to classify the converted text to one of the specified emotions.

## Repository Content
The repository contains two Jupyter notebooks:

`ASR_Section.ipynb`: Contains the code for downloading the MELD dataset and the modality conversion. The notebook uses Vosk to convert speech to text.

`Text_Emotion_Recognition.ipynb`: Contains the code for the BERT-based emotion classifier.

The CSV files containing the converted versions of speeches are also included in the repository along with the notebooks.

## Usage
To use this code, you will just need to run the jupyter notebooks cell by cell. All the dependencies and packages will be installed by running the first cells of each notebook.

## Citation
If you use this code for your research, please cite our paper:

mathematica
Copy code
[Insert Citation Here]
## Contact
If you have any questions or suggestions, please feel free to contact us at [Email]. We would be happy to hear from you!
