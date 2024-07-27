## 设置一些书籍，当你阅读这些书籍时，它们会给你带来经验、激活或解锁某种隐藏技能。

- **`RLF_MedicalBook1_Skills`**: `string` 书籍类型名称.
- **`skillPoints`**: `float` 获得的经验值.
- **`typeOfSkill`**: `string` 获得技能经验的类型.
- **`isPerkShowBook`**: `bool` 如果这本书用于解锁隐藏技能（在阅读这本书之前隐藏技能），则值应为 `1`.
- **`isPerkActivatedBook`**: `bool` 如果此书用于激活技能，则值应为 `1`.
- **`perkActivatedID`**: `int` 阅读后将激活的技能ID.
- **`showNotify`**: `bool` 显示所学经验或技能的通知.
  
```json
{
    "RLF_MedicalBook1_Skills": {
        "skillPoints": 15.0,
        "typeOfSkill": "MEDICAL",
        "isPerkActivatedBook": 0,
        "isPerkShowBook": 0,
        "perkActivatedID": -1,
        "showNotify": 1
    },
}
```
