# /screeps 指令

## 简介

[Screeps](https://screeps.com)游戏的相关操作

> ~~非常好玩赶紧给👴去玩~~

## 权限

普通用户组及以上

## 二级指令

### roomStatus(rs)  - 用于生成房间快照

#### 使用方法

``` QQ_message
/screeps rs [shardName] [roomName]
```

#### 举例

``` QQ_message
/screep rs shard3 W25S11
```

#### 参数

> shard名
> 房号

### info  - 用于获取某一Object的信息

#### 使用方法

``` QQ_message
/screeps info [shardName] [roomName] [ObjectId]/[ObjectType]
```

#### 举例

``` QQ_message
/screeps info shard3 W25S11 storage
```

#### 参数

> shard名
> 房号
> ObjectID / Object类型（忽视大小写）
>> 支持的类型：
>>
>> ``` JavaScript
>> ['storage','terminal','factory','controller','mineral','powerspawn',
>> 'nuker','observer','powerbank','deposit']
>> ```
