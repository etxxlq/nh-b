# nh-b
网站框架指纹识别工具，网站标题批量提取工具

## 网站框架指纹识别
### 单个目标识别

```
nh-b bannerinfo -u url
```

### 多个目标识别

```
nh-b bannerinfo -uf url.txt
```

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
