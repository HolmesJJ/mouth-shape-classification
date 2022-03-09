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
conda remove -n mouth_shape_classification --all
```

6. 对于ubuntu 16
```
source ~/anaconda3/etc/profile.d/conda.sh
conda activate VideoPose3D
```

7. 安装CUDA Toolkit
* [软件要求](https://www.tensorflow.org/install/gpu)
* [教程](https://blog.csdn.net/qq_44703886/article/details/112393149)
	* Toolkit: Installed in `/usr/local/cuda-11.2/`
* [常见问题](https://github.com/tensorflow/tensorflow/issues/42738)

