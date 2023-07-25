# ADVERSARIAL-NEURAL-CRYPTOGRAPHY

Link to the research paper : [LEARNING TO PROTECT COMMUNICATIONS
WITH ADVERSARIAL NEURAL CRYPTOGRAPHY](https://arxiv.org/pdf/1610.06918.pdf)
- install libraries in requirements.txt

- checkpoints are stored in the path ./lib/checkpoints. No need to remember the path, it will be created and loaded automatically by calling load function.

paper.ipynb:
- It is implemented as described in the research paper
- Some experiments with changing hypermaters are also done in this notebook and can be checked for the result.
- Inorder to train the model, we need to call train function with required parameters. (size of plaintext)
- Inorder to load the trained model use the load function. (size of plaintext = 16 , cant be changed)

only_fc.ipynb
- It is implemented by using neural networks with only fully connected linear layers.

only_convul.ipynb
- it is implemented by using neural networks with only convulusional layers.

paper_cnn_modified.ipynb
- It is implemented with same network structure as described in the paper but CNN layers are modified to have different kernel sizes , input channels and output channels.

RNN, LSTM, GRU codes can be accessed through this link : 
-> download the models from https://iiitaphyd-my.sharepoint.com/:f:/g/personal/akash_c_research_iiit_ac_in/EqsqE4MQFCdJkxVu8mpyxKgBH927RoEtoLLL2tNIO26omQ?e=Giz3Gh and put in the folder ./model 
->Change the config file to switch hyperparameters and base_model('LSTM','RNN','GRU')
-> python train.py to train the model
-> you can login from your wandb account to see the result
