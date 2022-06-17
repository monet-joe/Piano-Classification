# AlexNet-Piano-Classification

Classify piano acoustic fidelity by AlexNet

<!-- [![license](https://img.shields.io/github/license/george-chou/AlexNet-Piano-Classification.svg)](https://github.com/george-chou/AlexNet-Piano-Classification/blob/master/LICENSE)
[![Python application](https://github.com/george-chou/AlexNet-Piano-Classification/workflows/Python%20application/badge.svg)](https://github.com/george-chou/AlexNet-Piano-Classification/actions)
[![Github All Releases](https://img.shields.io/github/downloads-pre/george-chou/AlexNet-Piano-Classification/v1.2/total)](https://github.com/george-chou/AlexNet-Piano-Classification/releases) -->

## Dataset

Download at <https://github.com/george-chou/AlexNet-Piano-Classification/releases/download/v0.1/audio.zip>

Extract it into the project directory

## Usage

### Download

```
git clone https://github.com/george-chou/AlexNet-Piano-Classification.git
cd AlexNet-Piano-Classification
```

### Train

```
python train.py
```

### Draw training curves

```
python plotter.py
```

### Predict

```
python evaluate.py --target ./test/KAWAI.wav
```

## Results

| <img src="./results/loss.png"/> |  <img src="./results/acc.png"/>  |
| :-----------------------------: | :------------------------------: |
|           Loss curve            | Training and validation accuracy |
