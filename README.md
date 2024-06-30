
#### SD card image:
(шляхи розміщення)

- Всі ігри відповідно консолі: game\
- Збереження ігрового прогресу знаходиться: .emu_cfg\game\

### Додавання назв ігор у списки меню:

1. Відкрити текстовим редактором файл game\ .date\xxx.js відповідно емулятора консолі
2. Зробити бекап файлу .js
3. Додати блок з потрібною грою аналогічно списку:
- приклад блоку для ps.js (якщо гра остання в списку, кому в кінці прибрати):

  {"soupin":"yakitori musume - sugo ude hanjouki","child":false,"title":"Yakitori Musume - Sugo Ude Hanjouki","url":"/mnt/card/game/ps/Yakitori Musume - Sugo Ude Hanjouki/Yakitori Musume - Sugo Ude Hanjouki.bin"},
  
### Додавання прев'ю зображення гри у списки меню:

1. Розмістити зображення в форматі .png у папку "images" потрібної консолі
2. Назвати файл зображення так само, як назва гри у файлі .js
- приклад шляху для консолі емулятор PS1:
game\ps\images\Yakitori Musume - Sugo Ude Hanjouki.png

