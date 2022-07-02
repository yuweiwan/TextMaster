# TextMaster

Current function:  
- Extract meta data of scientific literature from savedrecs files of Web of Science (`meta_wos.ipynb`).  
- Automated opinion extraction and classification for scientific literature in materials science and related fields (`demo.ipynb`).  
  
This is the source code (demo version) of our Nature Energy submission "Opinion Mining and Deep Learning Methods for Maximising Discoverability of Energy Materials". We use `.ipynb` to show the running results directly (Click the `.ipynb` file and you will see running results of each cell. You can also set up environment in your local machine and try out our functions with your own data). We will develop a more packaged api version of this project later.  
Thanks for your attention. 

## Set up
1. Make sure you have python3.8 and the pip module installed. We recommend using conda environments.  
2. After git clone this repository to local machine (if you don't have git, you can also create a folder in local machine and download the files), navigate to the root folder of this repository and run `pip install --ignore-installed -r requirements.txt`. Note: if any packages fail to be installed, you may need to install those packages manually by `pip install package_name`.  
3. Stay in the root folder, manually download the models and data [data.zip](https://drive.google.com/file/d/1sOjwKw_y1WoUfSklIqw4UCOWHC8D7j7V/view?usp=sharing) and unzipped. 

## Introduction of code file meta_wos.ipynb  
The analysis is based on savedrecs files from Web of Science. The running results shown in this file are based on 22752 perovskite related publications. To get your own savedrecs files, you can search papers on [Web of Science](https://www.webofscience.com/wos/woscc/basic-search) by keywords and the search results should be exported as plain text files.  

We provide following functions:  
- extract mata data as a json file 
- visualization of publishers, journal names, publishment by year, data types, categories

## Introduction of code file demo.ipynb

## Note  
Before using these codes, please get permission from the author WAN Yuwei, email: yuweiwan2-c@my.cityu.edu.hk 
