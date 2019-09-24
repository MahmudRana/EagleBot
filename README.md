# EagleBot

System Requirement: For running EagleBot we have used Ubuntu 18.04.

Step 1: Download the code from https://drive.google.com/drive/folders/1qj-Ye6C9PD4pMZwvrfpxxPQ9fqh-qgYm

Step 2: Install anaconda3 with python 3 (64 bit version) (https://askubuntu.com/questions/505919/how-to-install-anaconda-on-ubuntu) by running these command below

# wget https://repo.anaconda.com/archive/Anaconda3-5.3.1-Linux-x86_64.sh
# bash Anaconda3-5.3.1-Linux-x86_64.sh
# source ~/.bashrc 

Step 3: Creating a python 3.7 conda environment by using the command below 
# conda create -n python3.7 python=3.7 

Then activate the environment by using 
# conda activate python3.7

Step 4: Install all the requirements for running Eaglebot (Please follow the below commands from this file https://docs.google.com/document/d/17KJokO4Lo23yRBTnoqJBmdDYIyUVvEFlBbcyIiTZ8bI/edit) 

Step 5: Download BERT-base model from their GitHub repo (BERT-Base, Uncased: 12-layer, 768-hidden, 12-heads, 110M parameters)
Link: https://github.com/google-research/bert

Step 6: Start Bert-serving-server by running 
# bert-serving-start -model_dir /tmp/english_L-12_H-768_A-12/ -num_worker=4
(after model_dir put the bert model address)
Please follow bert-as-service’s github link for details (https://github.com/hanxiao/bert-as-service)

Step 7: Download ElasticSearch

Step 8: Download ngrok

Step 9: Once all the setup is done, follow the starting eaglebot server file 
(https://docs.google.com/document/d/1RIbsYnRU13YSHT-TGICgG5st35neuZHoEtdS5asIcyA/edit)



