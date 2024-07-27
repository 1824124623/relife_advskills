## 在手工制作时获得经验
在这里，您可以指定完成后可获得经验的工艺

默认的工艺制作列表可以在 RegisterRecipies 功能中找到， 其他模组的工艺制造列表也可以用同样的方法找到
警告！不要在这里使用允许反复工作的工艺。例如，火炬工艺。你制作了它，然后可以把它拆开再制作。否则，玩家将无限制作这种工艺，并获得无限经验

![image](https://github.com/user-attachments/assets/f48648cb-255b-4781-a697-09cab53b7bf8)


- **`className`**: `string` 工艺类型名称
- **`skillPoints`**: `float` 获得的经验值
- **`typeOfSkill`**: `string` 获得技能经验的类型
- **`showNotify`**: `bool` 展示所学经验或技能的通知
  
```json
[
    {
        "className": "SplitStones",
        "skillPoints": 0.20000000298023225,
        "typeOfSkill": "ENGINEERING",
        "showNotify": 1
    },
    {
        "className": "CraftArmbandFlag",
        "skillPoints": 1.0,
        "typeOfSkill": "ENGINEERING",
        "showNotify": 1
    },
]
```

