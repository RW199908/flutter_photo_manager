# api 列表

## 相册相关

### 获取相册 id 列表

通过 id 在 dart 端封装出列表数据

### 相册信息

通过 id 获取相册信息

特例: all, 则获取全部

### 分页获取图片

根据页码, 分页数量获取对应相册 id

## 图片相关

### 根据 id 获取信息

同步信息:

- 类型: 图片或视频
- 时长: 秒, 图片为空
- 修改日期: 10 位 unix 时间戳

- 根据需要获取图片定位信息(需要由用户自行申请权限)

异步信息:

每个异步信息均为单独接口

图片缩略图, 图片原图

## 接口统计

1. 获取 path 列表(返回所有同步数据, 数量,名称)
2. 根据 path 异步获取数据列表(分页,所有同步数据)
3. 根据 asset 异步资源
   1. 缩略图(根据尺寸)
   2. 原图

## 权限相关

申请权限(ios android)

开启应用设置的 channel