# Examining repercussions of Audio-Effects in Modality-Aware AVVP
We add effects on audio which keeps audio still perceptible and analyse the effect on the Modality-Aware AVVP architecture

We also remove cross-modal audio attention from visual modality to save the visual modality from noise added by HAN.

We use a subset of train dataset (3181 videos) validation and test sets are same as the original paper (649 and 1200 videos resp.)

## Audio Effect & features
we added echoed audio effect .wav files are at [link](https://drive.google.com/drive/folders/1QdZk5WKu_9T3Ld3_zFqyXHwhKZqScnHU?usp=sharing) and features from VGGish are at [link](https://drive.google.com/drive/folders/12h6sHHtHLSq2jQHPUwKqHBykn0KEAFk6?usp=sharing)

Another effect we tried has .wav files stored at [link](https://drive.google.com/drive/folders/1-0U7UO1XopH9sPEiV9miu3sqsqWLwZAF?usp=sharing) and features from VGGish are at [link](https://drive.google.com/drive/folders/1J32nXv-VXK49myCz4cUagEXvfHTYaLsy?usp=sharing)

Original audio .wav files at stored at [link](https://drive.google.com/drive/folders/1-2wU9ZNNvG8KHvtPLRZGGJSbEq_IN-HX?usp=sharing) and original audio and visual features are at [link](https://drive.google.com/file/d/10CeaI1G9uIyz5dKnd7XTeH9-qOehC7CL/view)



## Run 
To run download code base (BASE) from [link](https://github.com/Yu-Wu/Modaily-Aware-Audio-Visual-Video-Parsing)

### Base code 
Replace files in BASE with the files in base_code directory

### MA-Variant
Cross-modal attention from visual modality is removed

Replace files in BASE with the files in MA_variant directory

VS_base_ASR_Project Notebook has commands to add audio effect, extractor features, and train models, please replace path wherever needed.

Comments are also placed in the notebook.

## Results are shown in slide
slide [link](https://docs.google.com/presentation/d/1kGu5utwpC9OzkTf1_3BagzvQ_nQC8j8rvd8GuME_C4o/edit?usp=sharing)

## Team J.A.R.V.I.S(APS)
213050059 Arun Babu P T 

213050069 Pasi Piyush Singh Umesh Chandra

21Q050002 Sai Teja Kuchi
