# /screeps 指令
- - -
## 简介
[Screeps](https://screeps.com)游戏的相关操作
> ~~非常好玩赶紧给👴去玩~~

## 二级指令
* roomStatus(rs)  
  * shard名  
  * 房号

> 用于生成房间快照  
> 示例：  
> /screeps rs shard3/W25S11

* info  
  * shard名  
  * 房号
  * ObjectID / Object类型（忽视大小写）  
  *支持类型：*  
  `['storage','terminal','factory','controller','mineral','powerspawn','nuker','observer','powerbank','deposit']`
  
> 用于获取某一Object的信息  
> 示例：  
> /screeps info shard3/W25S11 storage  
