# config_ActionCompletePoints.json 配置中变量的描述

可以指定参数，按变量名搜索累计经验

## `GetAdvSkills().GetAddPointsFromName(string pointConfigName)`

函数为指定的应计经验值名称返回一个 `float` 类型的值.

### 参数:

- **`pointConfigName`**: 字符串, 代表参数.

### 返回值:

- 如果 `AddPointBaseList` 存在并包含指定的 `pointConfigName`, 则返回相应的值.
- 否则，将返回  `0`.

### 使用示例:

```csharp
float result = GetAdvSkills().GetAddPointsFromName("PlayerKilled");
// 将返回值 15.0 
```

配置示例:

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
