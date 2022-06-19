# AkaneTech
# 茜茜绝龙诗科技

本插件使用Triggernometry进行优先级自动标点和部分机制提醒

严重依赖 鲶鱼精邮差 进行队员标点

安装鲶鱼精邮差请自行进入鲶鱼精邮差[wiki page](https://github.com/Natsukage/PostNamazu/wiki)
## 使用方式:
Triggernometry内选择远程触发器->添加->仓库

仓库地址内复制黏贴: https://raw.githubusercontent.com/ShohoUmi/AkaneTech/main/AkaneTech_DSR.xml

## 目前已支持功能:

### P2 骑神托尔丹
#### Strength of the Ward 一运
自动按照优先级标记:

攻击1-3为蓝标优先级

止步1-3为分摊踩塔优先级
### P3 尼德霍格:
#### Dive from grace 一运
自动按照优先级标记:

攻击1-3为一号塔优先级

禁止1-2为二号塔优先级

止步1-3为三号塔优先级

支持自动取消带箭头塔的标点，以避免打法不同造成的迷惑，请根据打法判断是否需要开启

### P4 龙眼:
#### Mirage Dive 
按照优先级标记第一次幻象冲目标和第三次俯冲的目标

攻击1-2为按照优先级的第一次被俯冲目标

禁止1-2为第三次俯冲目标
### P5 伪典托尔丹:
#### Wrath of the Heavens 一运:
自动判断战士小怪位置并使用TTS和小队聊天提醒(以双塔龙骑为北)

自动使用禁止1-2标记百雷点名

大龙卷判定瞬间小队列表音效提醒(音效为<se.10>)
#### Death of the Heavens 二运:
死宣出现后自动按照优先级标记死宣优先级和非死宣优先级

攻击1-4为死宣优先级

禁止1-3和方块为无死宣优先级

同时有一运同款大龙卷小队提醒

## To Do:
### P2 托尔丹:
#### Strength of the Ward 一运:
可能增加蓝圈点名优先级自动标点，分摊踩塔优先级自动标点
#### Sanctity of the Ward 二运:
可能增加龙眼位置检测
### P3 尼德霍格:
#### Dive from Grace 一运:
可能完善箭头处理，让上箭头标记1圆圈标记2下箭头标记3而非单纯取消箭头
#### P6P7等开荒完了再写
