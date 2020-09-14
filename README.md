# OCR-net
PyTorch based OCR involving CTPN (detection) and CRNN (recognition)

## Requirements
*   Python-3.6
*   pytorch-0.4.1+
*   torchvision-0.2.1
*   opencv-3.4.0.14
*   numpy-1.14.3

## Detection
Detection is based on [CTPN](https://arxiv.org/abs/1609.03605)

## Recognition
Recognition is based on [CRNN](http://arxiv.org/abs/1507.05717)

## Test
Download pretrained models from [gdrive link](https://drive.google.com/open?id=1hRr9v9ky4VGygToFjLD9Cd-9xan43qID)
into checkpoints folder
```bash
python3 demo.py
```

## Implementation References
*   [pytorch_ctpn](https://github.com/opconty/pytorch_ctpn)
*   [crnn.pytorch](https://github.com/meijieru/crnn.pytorch)
