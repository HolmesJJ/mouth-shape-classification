## Anaconda配置环境

1. 创建python版本3.7.10的环境
```
conda create --name mouth_shape_classification python=3.7.10
```

2. 安装好之后，使用以下命令查看所有已安装的环境
```
conda info --envs
```

3. 激活环境
```
conda activate mouth_shape_classification
```

4. 退出环境
```
conda deactivate
```

5. 删除环境
```
conda remove -n VideoPose3D --all
```

6. 对于ubuntu 16
```
source ~/anaconda3/etc/profile.d/conda.sh
conda activate VideoPose3D
```