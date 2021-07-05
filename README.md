# yolo3_pytorch_simplify
- 训练之后的权重文件及其配置文件在runs/train文件夹下生成的exp文件夹中
- 测试结果在runs/test文件夹下生成的exp文件夹中
- 推理结果在runs/detect文件夹下生成的exp文件夹中
- andb的结果保存在wandb文件夹里

## 训练代码
python train.py --data ../img/data.yaml --cfg yolov3.yaml --weights 'yolov3.pt' --batch-size 1 --epochs 10

python train.py --data ../img/data.yaml --cfg yolov3-tiny.yaml --weights 'yolov3-tiny.pt' --batch-size 1 --epochs 10
