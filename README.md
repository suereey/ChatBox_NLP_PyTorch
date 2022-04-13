# Deployed a Chat Bot With PyTorch - NLP And Deep Learning 

## Installation
- Create environment
```
conda create --name myenv
```

- install pytorch on windows. Find detail comment [here](https://pytorch.org/)
```
conda install pytorch torchvision torchaudio cudatoolkit=10.2 -c pytorch-lts

conda activate pytorch 
```
- activate pytorch and install [nltk](https://www.nltk.org/)

```
pip install nltk
```

## Run training
- Run. Result will be saved in data.pth file.
```
python train.py
```

Then run
```
python chat.py
```

## Result
- run in commend

![runincommend](https://raw.githubusercontent.com/suereey/ChatBox_NLP_PyTorch/main/screen_shot/Result.PNG)

- AI Chatbot with GUI

![gui](https://raw.githubusercontent.com/suereey/ChatBox_NLP_PyTorch/Lei_GUI/screen_shot/GUI.PNG)
## Resource.
- I learned this chat box project from: https://www.youtube.com/watch?v=RpWeNzfSUHw&list=PLqnslRFeH2UrFW4AUgn-eY37qOAWQpJyg&index=1
- Built chatbox GUI application: https://www.youtube.com/watch?v=RNEcewpVZUQ&list=PLqnslRFeH2UrFW4AUgn-eY37qOAWQpJyg&index=5