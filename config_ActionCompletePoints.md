# config_ActionCompletePoints.json 配置中变量的描述
## 配置执行继承自 ActionContiniousBase 和  ActionSingleUseBase 类的操作时的获得的经验值
行动说明 `ActionChickenBreak`

- **`ActionChickenBreak`**: 动作的类型名称
- **`skillPoints`**: 执行动作时获得的经验值
- **`typeOfSkill`**: 技能类型
- **`showNotify`**: 是否显示通知 - 1 或者 0

Пример:

```json
{
  "ActionChickenBreak": {
    "skillPoints": 0.5,
    "typeOfSkill": "HUNTING",
    "showNotify": 1
  },
 "ActionConsumeStarBalsam": {
        "skillPoints": 0.5,
        "typeOfSkill": "MEDICAL",
        "showNotify": 1
    },
}
