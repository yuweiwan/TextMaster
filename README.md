# TextMaster
Current function:  
- Extract meta data of scientific literature from savedrecs files of Web of Science  
- Automated opinion extraction and classification for scientific literature in materials science and related fields.  
  
Thanks for your attention. This is the source code (demo version) of our Nature Energy submission "Opinion Mining and Deep Learning Methods for Maximising Discoverability of Energy Materials".

Set up (Experimental environment)

1. Make sure you have python3.8 and the pip module installed. We recommend using conda environments.

2. After git clone this repository to local machine, navigate to the root folder of this repository and run `pip install --ignore-installed -r requirements.txt`. Note: if any packages files to be installed, you may need to install those packages manually by `pip install package_name`.

3. Run `python setup.py install` to install this module. This will also download the trained models and data.
If the download fails, manually download the [model](https://storage.googleapis.com/mat2vec/pretrained_embeddings), 
[word embeddings](https://storage.googleapis.com/mat2vec/pretrained_embeddings.wv.vectors.npy) and 
[output embeddings](https://storage.googleapis.com/mat2vec/pretrained_embeddings.trainables.syn1neg.npy) and put them in mat2vec/training/models.

Introduction of File meta_wos.ipynb

The file contains the trained models. Running an executable file in File "Demo", the results can be directly observed without further training.

Experimental Environment

Summer of Program

Parameters

Running Instance

Introduction of File demo.ipynb

The file contains the trained models. Running an executable file in File "Demo", the results can be directly observed without further training.

Experimental Environment

Summer of Program

Parameters

Running Instance



Introduction of  File Source

The file contains all source code for training. Utilizing the source codes in File "Source", a mature model can be obtained.

Experimental Environment
 
Summer of Program

Parameters

Running Instance



Note

Before using these codes, please get permission from the author, name, xxx@email.com 
