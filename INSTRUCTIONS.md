## For fine tuning 

```
python train.py --workers 8 --device 0 --batch-size 8 --data data/roadv2.yaml --img 640 480 --cfg cfg/training/yolov7-custom.yaml --weights 'yolov7_training.pt' --name yolov7-custom --hyp data/hyp.scratch.custom.yaml
```

## Issues 
- https://community.ultralytics.com/t/how-to-combine-weights-to-detect-from-multiple-datasets/38/54
- https://github.com/WongKinYiu/yolov7?tab=readme-ov-file
- 