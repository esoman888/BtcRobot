# A Robot For Huobi

当前正在开发中，暂无法使用。了解情况可以关注下之前做的比特时代盘口机器人


## 开发计划
- [ ] 程序初步跑起来  
- [ ] 支持无数据库
- [ ] 支持参数配置
- [ ] 支持多个币种和交易所

## 币安交易机器人
计划开发以下不同机器人

- 买卖单机器人
- 盘口机器人
- 量化机器人
- 差价机器人
- 消息机器人
- 搬砖机器人

## 使用方法
1. env.example.php改为env.php
然后修改里面常量值的为自己的信息
2. php kx cron:bot coin/btc
btc可以更换其他币种，当前仅支持火币usdt区



## 今后的方法
请保留账户中有足够的usdt
每笔交易为50usdt 可以开多窗口运行
2. php kx migrate:up 导入数据库
3. php kx robot:start 运行
4. php kx robot:stats 查看统计 