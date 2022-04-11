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

This will dump data.pth file. And then run

python chat.py