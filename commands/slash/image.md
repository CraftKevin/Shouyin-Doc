# /image 指令

## 简介

图片相关操作

## 别称

此指令可缩写为：`/img`

## 权限

普通用户组及以上

## 二级指令

### bin - 将图片二值化（黑白化）

```QQ_message
/image bin
```

#### 参数

无参数

#### 附加消息

1. 待处理的图片

### exif - 获取图片的 EXIF 信息

```QQ_message
/image exif
```

#### 参数

无参数

#### 附加消息

1. 待处理的图片

### size - 获取图片尺寸（单位像素）

```QQ_message
/image size
```

#### 参数

无参数

#### 附加消息

1. 待处理的图片

### resize - 返回规定尺寸修改后的图片

#### 用法

```QQ_message
/image resize [size]
```

#### 实例

```QQ_message
/image resize 60*60
```

#### 参数

1. 目标尺寸

> 支持的分割方式：`['x', 'X', '*']`

#### 附加消息

1. 待处理的图片

### gaussianblur\(gs\) - 对图片进行高斯模糊

#### 用法

```QQ_message
/image gaussianblur [Blur Radius]
```

```QQ_message
/img gs [Blur Radius]
```

#### 实例

```QQ_message
/image gaussianblur 60
```

#### 参数

1. 模糊半径

#### 附加消息

1. 待处理的图片
