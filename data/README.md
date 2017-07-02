Place your coco in this dir, like
```buildoutcfg
./data
    ./coco
        ./train2014.zip
        ./val2014.zip
        ./instances_train-val2014.zip
        ./person_keypoints_trainval2014.zip
        ./captions_train-val2014.zip
```

After unzip and download resnet_v1_50, dir should be like:

```buildoutcfg
./data
    ./coco
        ./train2014
        ./val2014
        ./annotations
            captions_train2014.json
            captions_val2014.json
            instances_train2014.json
            instances_val2014.json
            person_keypoints_train2014.json
            person_keypoints_val2014.json
    ./pretrained models
        resnet_v1_50.ckpt
```
