## 设置未激活特定技能时的禁用手工制作的锁定功能
在这里，您可以指定一种工艺，在激活该技能之前，您将无法执行该手工制作功能

默认的工艺制作列表可以在 RegisterRecipies 功能中找到， 其他模组的工艺制造列表也可以用同样的方法找到

![image](https://github.com/user-attachments/assets/f48648cb-255b-4781-a697-09cab53b7bf8)

- **`recipeName`**: `string` 配方字符串,如果玩家没有学习 **neededPerkID** 技能，则会被禁止这个手工制作
- **`neededPerkID`**: `int` 技能ID, 允许使用这个手工制作配件时需要激活的技能ID
  
```json
[
    {
        "recipeName": "CraftClassname",
        "neededPerkID": 0
    },
    {
        "recipeName": "CraftClassname2",
        "neededPerkID": 2
    }
]
```
