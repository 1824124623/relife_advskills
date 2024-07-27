# config_ActionCompletePoints.json 配置中变量的描述

可以指定参数，按变量名搜索累计经验

## `GetAdvSkills().GetAddPointsFromName(string pointConfigName)`

函数为指定的应计经验值名称返回一个 `float` 类型的值.

### Параметры:

- **`pointConfigName`**: Строка, представляющая параметр.

### Возвращаемое значение:

- Если `AddPointBaseList` существует и содержит указанное `pointConfigName`, то возвращается соответствующее значение.
- В противном случае возвращается `0`.

### Пример использования:

```csharp
float result = GetAdvSkills().GetAddPointsFromName("PlayerKilled");
// Вернется значение 15.0 
```

Пример конфигурации:

```json
{
    "CraftWhetstone": 1.0,
    "PlayerKilled": 15.0,
    "ActionInjectTarget": 1.0,
    "BadEatPrepareFruit": 0.0,
    "BadEatPrepareMeat": 0.0,
    "ActionFishingNewCircle": 0.10000000149011612,
    "BadEatPrepareFish": 0.0,
    "BloodTestSelf": 1.0
}
```
