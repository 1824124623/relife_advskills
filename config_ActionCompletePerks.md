# config_ActionCompletePerks.json 配置中变量的描述
## 在执行继承自 ActionContiniousBase 和 ActionSingleUseBase 类的操作时配置的激活技能
行动示例 `ActionBandageSelf`.

- **`ActionBandageSelf`**: 动作的类型名称
- **`perkID`**: 已激活的技能ID
- **`itemInHandsList`**: 手中物品的类型名称数组，行动时手中的物品必须与物品类型名称一致才能行动。如果物品可以是任何物品，则留空.
- **`showNotify`**: 是否显示通知的 - 1 或 0

示例:

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
