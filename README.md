# OMR-transformer
CNN + transformer model

## Preferences
Edit it hparams.py

Put the training images files in train/images/

Put the training text files in train/words/

## Training
Run python ocr.py -r t

## Prediction
Run python ocr.py -c resnet50_trans_last.pt -d ./data/

*resnet50_trans_last.pt come from ##Training result
