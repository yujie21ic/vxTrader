# vxTrader

## vxTrader

一个标准化，统一封装的A股券商web 交易接口。

### 安装方法

```
pip3 install vxTrader
```

### 使用方法

```python
from vxTrader import TraderFactory
trader = TraderFactory.create(
    brokerID='yjb',
    account='你的佣金宝账号',
    password='加密后的密码'
)

print(trader.portfolio)
print(trader.orderlist)

```

### 支持券商
|券商名称 | broker id |
|:    ---    |:    ---    :|
| 国金证券（佣金宝) | yjg |
|广发证券 | gf |
|雪球组合管理 | xq |
