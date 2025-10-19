## Run Example

```
python sbsn.py --dataset_name house1to10 --device cuda:0 --val_epoch 1000 --epoch 200000
```

## Run Example

```
python generate.py --dataset_name house1to10 --device cuda:0
python post.py --dataset_name house1to10 --device cuda:0 --val_epoch 10 --epoch 400
```

Train on large dataset:
1.Download raw dataset file
2.Put in correspond folder in ./experiments-data
3.Run process.py and segmentation.py