## Description🔎
This repository contain notebook that used to train Chatbot Model that deployed using flask on <a href='https://github.com/marveltimothyy/Chatbot_Deploy'>Chatbot Deploy with Flask<a> <br>

## Main Library 📚
• <a href="https://pytorch.org/">Pytorch</a> 
<br>

## Dataset💾
•Chatbot Model are trained with preprocessed <a href='https://www.cs.cornell.edu/~cristian/Cornell_Movie-Dialogs_Corpus.html'>Cornell Movie-Dialogs Corpus<a><br>
•All dataset version (raw and formatted) can be found in this <a href='https://drive.google.com/drive/u/0/folders/1QKqp7wuFOOV2TtLsVkhlBQltioE_Qx92'>Drive<a>

## Model 🤖
This chatbot used sequence-to-sequence architecture wich have Encoder and Decoder in it. Bidirectional Gated Recurrent Unit (GRU) are implemented in Encoder while Vanilla GRU in Decoder.
In additon to improve chatbot performance i'm using <a href="https://arxiv.org/abs/1508.04025">Luong Attention Mechanism</a> that implemented in Decoder. <br> <br>

## How to Install🔧
There are several tools that i used on this notebook:<br>
• <a href="https://www.anaconda.com/products/distribution">Anaconda Installation</a><br>
• Chatbot Environment Installation -> Follow this <a href="https://docs.conda.io/projects/conda/en/latest/user-guide/tasks/manage-environments.html#creating-an-environment-from-an-environment-yml-file">Guide</a> with using **chatbot_env.yml** from this repository


## How to Run🏃‍♂️
•Open notebook on local or <a href="https://colab.research.google.com/notebooks/intro.ipynb#recent=true">GoogleCollabs</a><br>
•**You can skip this step if using GoogleCollabs**. Activate the imported environment with <br> `conda activate chatbot_env` in terminal<br>
•Run each cell step by step<br>
•On the mounting cell you need to connect your notebook with Google Drive account which has the required dataset on correctly path<br>
