# nh-b
网站框架指纹（及版本）识别工具，网站标题批量提取工具


***第一次运行会生成config文件夹，需要将指纹库放在config文件夹下面，否则会报错***
![image](https://github.com/user-attachments/assets/f2507423-3fcf-4635-b536-1e821e9e6a08)

运行之后会自动在result目录下生成本地数据库，可以安装DB Browser for SQLite软件进行打开查看


## 网站框架指纹识别
### 单个目标识别

```
nh-b bannerinfo -u url
```

### 多个目标识别

```
nh-b bannerinfo -uf url.txt
```

![image](https://github.com/user-attachments/assets/33e5c165-5a68-4666-ba6f-a4d0043fd217)


## 网站标题提取

### 单个目标标题提取
```
nh-b titlescan -u url
```
### 多个目标标题提取
```
nh-b titlescan -uf url.txt
```

### 指定拼接单个路径后标题提取
```
nh-b titlescan -uf url.txt -d /nacos/,/robots.txt,/admin/
```

### 指定拼接多个路径后标题提取
```
nh-b titlescan -u url -df dirs.txt
```
