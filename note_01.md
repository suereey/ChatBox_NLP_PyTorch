# Chat Bot With PyTorch - NLP And Deep Learning - Python

## Concept
- Tokenization: splitting a string into meaningful unit. Example
    - "what would you do with $1000?"
        ["what", "0", "would", "you", "do", "with", "$1000?", "?"]
- Stemming: generate the root form of the words. Crude heuristic that chops of the ends off of words
    - "universe", "university"
        ["univers", "univers"]
- Summary:
    ![screenshot_01](https://raw.githubusercontent.com/suereey/ChatBox_NLP_PyTorch/main/screen_shot/NLP_Pipline.PNG)
## Set up environment
- Lei conda, build new enviornment in terminal: Lei_April2022
- install pytorch
- conda activate pytorch
- pip install nltk

## Coding
- ultk_utils.py: 3 functions: tokenize, stem, and bag of words

- train.py: creat training dataset
    - open intents.json file
    - tokenize allw words. create all_words as x and tags as y
    - create x_train, y_train
    - create class ChatDataset(Dataset)

- model.py: create feedforawd nn with 2 hidden layers using Relu as the activation function

- go backto train.py train the models