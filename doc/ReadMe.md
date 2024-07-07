## ZVT快速入门

#### 安装
```shell
conda create -n zvt python=3.8
conda activate zvt
python -m pip install -U zvt

# 或者源码编译

conda activate python38
python -m pip install -U .

# 安装路径在 C:\Users\huzhe\.conda\envs\py38\Scripts
``` 

#### 配置
##### 数据下载
+ [下载地址](https://drive.google.com/drive/folders/17Bxijq-PHJYrLDpyvFAm5P6QyhKL-ahn)
+ 配置， 根据默认配置放置数据，然后解压即可
    ```json
     {'data_path': 'C:\\Users\\huzhe\\zvt-home\\data',
        'log_path': 'C:\\Users\\huzhe\\zvt-home\\logs',
        'resource_path': 'C:\\Users\\huzhe\\zvt-home\\resources',
        'tmp_path': 'C:\\Users\\huzhe\\zvt-home\\tmp',
        'ui_path': 'C:\\Users\\huzhe\\zvt-home\\ui',
        'zvt_home': 'C:\\Users\\huzhe\\zvt-home'}
    ```
    
    
    
#### 运行
```shell
zvt
```