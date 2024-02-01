---
lang: zh-CN
title: 🌈OverView For Lucy's Magic✨.
description: ~
---

> 第一次在群组使用 管理员 需自行 /response 一次 | 如果 需要 Bot 静下来，可使用 /slience 闭嘴

> 目前 Lucy for Telegram 版本为雏形，大部分的功能基于 For Onebot 版本移植~


## Function

### 响应 / 睡眠

> 原生 Reibot 类功能，本身是在 Zerobot-Plugin 系 Bot 下使用，后作为简单的管理 Bot 启用 / 禁用


- response 启动响应 ( 第一次使用需要启用响应，默认拉入不工作 )

- slience 睡眠 (阻止 Lucy 在群中发言 )



#### 此外还支持以下群组管理功能

- disable / enable 针对 插件进行 禁用 / 启用 ( 方式: /enable  {Plugin_name}|| disable {plugin_name} )

- service_list 查询插件名称


### 对话 (Chat)

> 一些 Lucy 在 Onebot 上的对话功能，经过一部分魔改移植x

- Lucy

> Lucy 会听到并且做出一些答复，在部分情况下可以使用 Lucy + (simai回复词) 实现基础互动而不是@

- callname

> 可以用这个给 Lucy 设定 自己的名字 ，在和 Lucy 互动的时候 {name} || {你} 将会被修改为此名字x

### Action

> 水个群把(?) | 默认禁用 

- 喵 | 咕咕


###  Stickers

> 一定概率下，抽取用户发送 Stickers Collecions 中其中一张贴纸

- (Stickers)

### 运势 (Fortune)

> Lucy 家 非常经典 而且 每天 12 点 刷新的功能~附赠塔罗牌

- fortune

![](https://cdn.himoyo.cn/manual/Screenshot%202023-11-18%20215431.png)



### 签到 (Sign)

> 每天一次签到，会有柠檬片哦~

- sign

![](https://cdn.himoyo.cn/manual/Screenshot%202023-11-18%20221143.png)



### 抽奖(Coinroll) | CoinWager

> 一些使用柠檬片互动的简单机制~

- coinroll (抽奖一次哦~需要60片一次x)

- coinwager [coin] (一次性投入 coin 枚柠檬片，等到一定机会可以拿到多奖励~)

- coinfull (检查你还有多少柠檬片呢w)

- coinrob @User (抢@User的 柠檬片)

- coincheat @User [coin] (骗@User的[coins]个柠檬片)

- coinhand @User [coin] (给@User转[coins]个柠檬片)

- coinstaus [Enable/Disable] (启用/禁用 柠檬片互动)

> 24小时尽可修改一次

![](https://cdn.himoyo.cn/manual/Screenshot%202023-11-18%20221534.png)


### 群老婆(GroupWife) | 写废了 爱修不修（

> 源自于 Lucy For Onebot 上的 老婆插件, 魔改于 FloatTech / Zerobot-Plugin 重写

- marry @User (娶某个人) / 概率性

- wife (随机群老婆~)

- divorce (离婚)  /  概率性

- chwaifu @User (骗 @User 做自己的老婆)

- waifulist (输出今日群老婆列表)

- waifuwish @User (许愿 @User 在下次机会时第一次抽到概率增大)

> 其中 **chwaifu/divorce/marry** 为 调用限制，当天调用少

### Lolicon

> 随机一张涩图~ **注意是 R18 涩图**

- Lolicon

### Reborn

> 随机重生~ 但是没有 Trans 属性

- reborn

### MaiMai

- mai (查询您的 maimai B50)

- mai bind (绑定用户查分名)

- mai plate (自定义绑定区域称号)

- mai upload (自定义上传底图)

- mai remove (移除自带的底图)

- mai defplate (使用自带的maimai底图预设)

- mai userbind [userTempid] (绑定Userid)

- mai lxbind [friendcode] (绑定好友码，适用于 Lxns  maimai查分器)

- mai switch (更换查分源 可以从 lxns maimai 查分 |Diving Fish 水鱼 查分 选择)

- mai unlock (解锁小黑屋/15mins)

- mai region (查询出勤记录)

- mai tokenbind [TokenID]

- mai status (查询 maimai 服务状态)

> 关于底图预设,请查询: [mai_plate](https://lucy.lemonkoi.one/mai_plate/) 底图通用

![](https://cdn.himoyo.cn/manual/Screenshot%202023-11-18%20220041.png)

* 底图设计来源于 [Isoheptane](https://github.com/Isoheptane)


### Phigros

> Phigros 查分，数据来源于 * Phigros Library Project 逆向结果

> 使用到的项目：

> PhigrosLibrary: [PhigrosLibrary](https://github.com/7aGiven/PhigrosLibrary)

> PhigrosLibrary-FlaskAPI : [PhigrosLibrary-FlaskAPI ](https://github.com/MoYoez/PhigrosLibrary-FlaskAPI)



- pgr bind  (绑定Session)

> 此处的 Session 请前往 [关于 Phigros B19 Session 绑定](https://phi.lemonkoi.one/) 绑定


> * 此页面本为 Lucy For Onebot 进行适配，**请在填写QQ的地方填入你的Telegram UserinfoID**

> * 同时传回的结果 **将 ! 改为 /**

- pgr (查询您的 phigros b19 成绩表)

> 因为服务由 Vercel Serverless 提供，会出现相对来说较慢的问题，请多等待~

- pgr roll [20-40] (向下查询您的 Phigros 成绩 ，最高支持到 40首)

 ![](https://cdn.himoyo.cn/manual/Screenshot%202023-11-18%20220915.png)



### Slash

> 请参考 其他家 Bot , 这边只是说明有这个功能x

> 设计同 [SlashBot](https://github.com/Rongronggg9/SlashBot)


### Simai

> 没有介绍哦~ 去 @Lucy 试试回复一些东西吧~

> 使用了2w+的回复库，看Lucy心情，可能就回复你了w


### Status

> 给 Lucy 检查一下身体吧

- status

~~虽然说已经被玩坏了x~~

### DataUpdate (数据更新)

> 更新用户数据部分，如果你的用户名有变动的话记得使用 (  可不使用, Lucy在每24小时后自动刷新一次  )

- dataupdate

### 搜番 (TraceMoe)

> 会帮忙搜番的工具~

- tracemoe


## Thanks

> Reibot-Plugin

