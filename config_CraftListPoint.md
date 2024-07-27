## 在手工制作时获得经验.
在这里，您可以指定完成后可获得经验的工艺. 

Список ванильных крафтов можно найти в функции RegisterRecipies, с другими модами точно также. 
ВНИМАНИЕ! Не используйте здесь крафты которые работают от обратного. То есть к примеру крафт на факел. Вы его крафтите, а потом можете разобрать и снова скрафтить. Иначе игроки будут арбузить этот крафт и получать бесконечный опыт.

![image](https://github.com/user-attachments/assets/f48648cb-255b-4781-a697-09cab53b7bf8)


- **`className`**: `string` Класснейм крафта.
- **`skillPoints`**: `float` Количество начисляемого опыта.
- **`typeOfSkill`**: `string` Тип навыка на который будет начислен опыт.
- **`showNotify`**: `bool` Показывать уведомление о полученом опыте или изученом навыке.
  
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

