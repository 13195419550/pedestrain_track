# pedestrain_track

## **简介**

* 基于paddle框架进行开发
* 使用PaddleDetection进行模型训练
* 选择的模型为PP-YOLOv2
* 基于[DeepSort](https://github.com/nwojke/deep_sort)官方开源代码开发，将其中的深度学习模型更换为Paddle模型

## **快速使用**
* 同步代码
```shell
$ git clone https://github.com/13195419550/pedestrain_track.git
```

* 按照 [train](./train) 中代码进行环境的安装及模型训练
* 训练完成后将模型导出到model/detection文件夹下

* 预测推理
```shell
$ cd deep_sort_paddle

$ python main.py \
    --video_path PATH_TO_VIDEO \
    --save_dir PATH_SAVE_DIR \
    --use_gpu SET_IT_IF_USE_GPU \
    --display SET_IT_IF_DISPLAY_RESULTS  
```

* 更多参数请查看 [main.py](./main.py) 源代码
