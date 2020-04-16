# /screeps 指令

## 简介

[Screeps](https://screeps.com)游戏的相关操作

> ~~CK: 非常好玩赶紧给 👴 去玩~~

## 权限

普通用户组及以上

## 二级指令

### findroute(fr) - 用于寻找包含portal的最短路径

Powered by [Du](https://github.com/ChenyangDu)

[项目源码](https://github.com/tsssp/Screeps-UoP/tree/master/overShard)

#### 用法

```QQ_message
/screeps findroute [start_shardName_roomName] [end_shardName_roomName]
```

```QQ_message
/screeps fr [start_shardName_roomName] [end_shardName_roomName]
```

#### 实例

```QQ_message
/screeps fr shard3_E30N40 shard3_E20N40
```

#### 参数

1. 起点房间名(shard名与房间名，用下划线连接)
2. 终点房间名(shard名与房间名，用下划线连接)

> 暂时仅支持十字路口

### info - 用于获取某一 Object 的信息

#### 用法

```QQ_message
/screeps info [shardName] [roomName] [ObjectId/ObjectType]
```

#### 实例

```QQ_message
/screeps info shard3 W25S11 storage
```

#### 参数

1. shard 名
2. 房号
3. ObjectID / Object 类型（忽视大小写）

> 支持的类型：
>
> ```JavaScript
> ['storage','terminal','factory','controller','mineral','powerspawn','nuker','observer','powerbank','deposit']
> ```

### roomstatus(rs) - 用于生成房间快照

#### 用法

```QQ_message
/screeps roomstatus [shardName] [roomName]
```

```QQ_message
/screeps rs [shardName] [roomName]
```

#### 实例

```QQ_message
/screep rs shard3 W25S11
```

#### 参数

1. shard 名
2. 房号
