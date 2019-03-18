# TOEX-Risk

## 每分钟推送

```python
BinaryRisk.feedShares(币种[type:string]，现价【type：float】，[5分钟买涨盈亏，10分钟买涨盈亏，30分钟买涨盈亏，60分钟买涨盈亏]，[5分钟买跌盈亏，10分钟买跌盈亏，30分钟买跌盈亏，60分钟买跌盈亏]，最大下单总金额【type：float】,根据亏损调整的倍数【type:int】) 
```

## 获取秒级调整赔率

```python
binaryRisk.getOdds(币种[type:string]，现价【type：float】，合约截止时间【type:datetime】，合约停止下单时间【type:int】，最大下单总金额【type：float】，当前初始赔率【type:float】,根据亏损调整的倍数【type:int】)
```

★ 根据亏损调整的倍数【type:int】 需要在后台风控管理界面 增加一个可设置的参数
