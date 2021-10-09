# Human-Attention-in-Image-Captioning-Dataset-and-Analysis-ICCV-2019
## Introduction
This is the github page for our ICCV 2019 paper ([link](https://openaccess.thecvf.com/content_ICCV_2019/papers/He_Human_Attention_in_Image_Captioning_Dataset_and_Analysis_ICCV_2019_paper.pdf)).
We provide the link to the data collected in the paper:
![picture](/fg/data.png)
[capgaze1](https://drive.google.com/open?id=1qlOCr8TX6dmAxhlCob79X29riyQ_MRlq): contains 1000 images, and raw data (eye-fixations, verbal description as well as the transcribed text description) from 5 native English speakers. This part of data was used for the analysis. For data privacy reason, the voice of the verbal description was converted by a masking process (pitch modulation, the content was preserved).

[capgaze2](https://drive.google.com/drive/folders/1ghe3_7tdx2f3ejiKEnv6w_JJ39-9c9eB?usp=sharing): contains 3000 images, and processed data (we combined all the eye-fixations from different people for each image into a fixation map). This part of data was used for developing saliency prediction model under the image captioning task.

Also we give the code for extracting the information in the collected data in the demo folder (an example in the demo.ipynb).

# Contact
<senhe752@gmail.com>
