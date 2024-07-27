# config_ActionCompletePerks.json 配置中变量的描述
## 在执行继承自 ActionContiniousBase 和 ActionSingleUseBase 类的操作时配置技能激活
行动说明 `ActionBandageSelf`.

- **`ActionBandageSelf`**: Класснейм действия.
- **`perkID`**: ID активируемого перка.
- **`itemInHandsList`**: Массив класснеймов предмета в руках, который должен быть чтобы перка активировался. Оставить пустым если предмет может быть любой.
- **`showNotify`**: Флаг для отображения уведомлений - 1 или 0.

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
