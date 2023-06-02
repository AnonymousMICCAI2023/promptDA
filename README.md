# promptDA
This is the 3DUNet version promptDA for infant tissue segmentation.

## Prpare data
```
python prepare_hdf5_cutedge.py 
python hdf5_for_unlabel.py
```

## Training(After add dataset path in the code)
```
python train_v1.py           #baseline
python train_onlyprompt.py   #only prompt
python train_adv.py          #only adversarial train
python train_v2.py           #combine prompt and adv
```
