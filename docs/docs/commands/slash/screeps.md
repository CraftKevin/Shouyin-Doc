# /screeps 指令

## 简介

[Screeps](https://screeps.com)游戏的相关操作

> ~~非常好玩赶紧给👴去玩~~

## 权限

普通用户组及以上

## 二级指令

* roomStatus\(rs\)  - 用于生成房间快照 

```
/Screep rs shard3/W25S11
```

> 参数：
>
> 1. shard名/房号

* info  - 用于获取某一Object的信息

```
/screeps info shard3/W25S11 storage
```

> 参数：
>
> 1. shard名/房号
> 2. ObjectID / Object类型（忽视大小写） 
>    1. 支持的类型：
>       `['storage','terminal','factory','controller','mineral',`
>       `'powerspawn','nuker','observer','powerbank','deposit']`



