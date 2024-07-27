# config_ActionCompletePerks.json 配置中变量的描述
## 在执行继承自 ActionContiniousBase 和 ActionSingleUseBase 类的操作时激活技能配置
行动说明 `ActionBandageSelf`.

- **`ActionBandageSelf`**: 动作的类别名称.
- **`perkID`**: 已激活的技能ID.
- **`itemInHandsList`**: 手中物品的类别名称数组，必须与物品名称一致才能激活津贴。如果物品可以是任何物品，则留空.
- **`showNotify`**: 是否显示通知的  1 或 0

Пример:

```json
{
   "ActionBandageSelf": {
        "perkID": 100,
        "itemInHandsList": [],
        "showNotify": 1
    }
 "ActionBandageTarget": {
        "perkID": 100,
        "itemInHandsList": ["Item1", "Item2"],
        "showNotify": 1
    }
}
