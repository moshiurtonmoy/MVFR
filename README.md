# MVFR: Multilingual Visual Font Recognition Synthetic Dataset
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT) <a target="_blank" href="https://colab.research.google.com/github/moshiurtonmoy/Bangla-Visual-Font-Style-Recognition-with-Lightweight-Convolutional-Autoencoder/blob/master/%5BQuantized%5D_Bangla_Visual_Font_Recognizer.ipynb"><img src="https://colab.research.google.com/assets/colab-badge.svg" alt="Open In Colab"/></a> 
[![DOI:10.1109/IEEEDATA.2024.3460768](https://zenodo.org/badge/DOI/10.1109/IEEEDATA.2024.3460768.svg)](https://doi.org/10.1109/IEEEDATA.2024.3460768) 
<hr/>

With the advancements of deep learning and computer vision-incorporated
applications, the Visual Font Recognition (VFR) field has evolved rapidly. From
browser extensions to mobile and web apps, several efficient systems now exist for
identifying fonts from images. However, progress in languages other than English has
been limited, largely due to insufficient data availability. To address this obstacle, we
have created a synthetic image dataset for VFR encompassing four different
languages: Bangla, Hindi, Russian, and Spanish. Each language is represented by a
dedicated folder, with 10 subfolders containing 5,000 images each, resulting in a
substantial corpus of 200,000 images overall. Furthermore, we have provided the
Python generator script used to create this dataset, which can be employed to
generate synthetic VFR image data for additional languages, furthering the progress of
the VFR field in languages with limited resources.

<ul>
  <li>The dataset has been published in <b><i>IEEE Data Descriptions</i></b> and the full article can be accessed publicly from <a target='_blank' href="https://ieeexplore.ieee.org/abstract/document/10680521"> IEEE Xplore</a></li>
  <li>Access the dataset directly from <a href="https://data.mendeley.com/datasets/cnd2wh65my/1">Mendeley Data</a></li>
</ul>

## Value of the Data

1. The MVFR dataset is a comprehensive synthetic dataset that can be a valuable resource
for researchers working on the Visual Font Recognition domain. Researchers and
developers can explore the use of deep learning architectures to effectively
recognize visual font styles by employing this dataset.
2. The dataset contains a total of 2,00,000 images of 4 different languages. For each
language, we employed 10 popular fonts and generated images of 5000 distinct
common words for each font, thus each language has 50,000 images. This large
collection can be utilized for benchmarking and comparing the performances of
different traditional to advanced deep learning models.
3. This is the first-ever large open-source VFR dataset on the respective languages.
Researchers can utilize this dataset for developing tools and applications for visual font
recognition of the respective language e.g. browser extensions, mobile apps, etc.
4. Apart from the VFR application, this dataset can also be utilized in other computer
vision applications as well, for instance, researchers can experiment with this dataset
for optical character recognition (OCR) from diverse font styles as well.

## Sample Data Instances

<img src="https://github.com/moshiurtonmoy/MVFR-Multilingual-Visual-Font-Recognition-Synthetic-Dataset/blob/master/sample_data/BN.jpg" alt="sample_data_BN"/>
<img src="https://github.com/moshiurtonmoy/MVFR-Multilingual-Visual-Font-Recognition-Synthetic-Dataset/blob/master/sample_data/Hindi.jpg" alt="sample_data_Hindi"/>
<img src="https://github.com/moshiurtonmoy/MVFR-Multilingual-Visual-Font-Recognition-Synthetic-Dataset/blob/master/sample_data/Russian.jpg" alt="sample_data_Russian"/>
<img src="https://github.com/moshiurtonmoy/MVFR-Multilingual-Visual-Font-Recognition-Synthetic-Dataset/blob/master/sample_data/Spanish.jpg" alt="sample_data_Spanish"/>


## Citation
```
@ARTICLE{10680521,
  author={Tonmoy, Moshiur Rahman and Adnan, Akhtaruzzaman and Saha, Aloke Kumar and Mridha, M. F. and Dey, Nilanjan},
  journal={IEEE Data Descriptions}, 
  title={Descriptor: Multilingual Visual Font Recognition Dataset (MVFR)}, 
  year={2024},
  volume={1},
  number={},
  pages={1-6},
  doi={10.1109/IEEEDATA.2024.3460768}}
```
<hr/>
