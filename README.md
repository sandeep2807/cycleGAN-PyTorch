# CycleGAN using PyTorch
CycleGAN is one of the most interesting works I have read. Although the idea behind cycleGAN looks quite intuitive after you read the paper: [Unpaired Image-to-Image Translation using Cycle-Consistent Adversarial Networks](https://arxiv.org/abs/1703.10593), the official PyTorch implementation of cycleGAN is difficult to understand(as the code has multiple things implemented together). I had to write cycleGAN to use it for some other work. So, I thought of making my version of cycleGAN  public for those who are looking for an easier implementation of the paper. 

## Requirements
- The code has been written in Python (3.5.2) and PyTorch (0.4.1)

## How to run
* To download datasets (eg. horse2zebra)
```
$ sh ./download_dataset.sh horse2zebra
```
* To run training
```
$ python main.py --training True
```
* To run testing
```
$ python main.py --testing True
```

## Results
Coming Soon
