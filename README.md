# UOPatcher

При выборе процесса/файла:

- _**Чекбокс**_ не активен - патч не был найден (либо клиент не поддерживает это изменение, либо уже был изменен ранее).

- _**Активен**_ и его **цвет**:

 - _**Зеленый**_ - патч установлен.

 - _**Красный**_ - патч снят.

***

По галочкам патчера:

- _**FPS**_ - Включить/выключить ФПС патч (инжектовский). (*патч процесса)

- _**Stamina**_ - проход через персонажей.

- _**Always light**_ - Включить свет. При патче запущенного клиента требуется ресенд/отбежать на экран/телепорт/перезаход.

- _**Paperdoll slots**_ - Отображение слотов на чужих персонажах с корректным отображением тултипов и кликами по предметам в этих слотах.

- _**No splash screen**_ - Убрать начальную заставку. (*патч файла)

- _**Resolution**_ - Возможность изменить габариты игрового окна в uo.cfg. (*патч файла)

- _**No options notification**_ - Убрать сообщение при изменении опций (если было изменено разрешение игрового окна) и сброс разрешения игрового окна.

- _**Multi client**_ - возможность запуска нескольких клиентов. (*патч файла)

- _**No crypt**_ - Убрать шифрование клиента. (*патч файла)

- _**Global sound**_ - Включить проигрывание звуков независимо от фокуса в окне УО. (*патч файла)

***

При патче файла, если клиент уже был пропатчен на No crypt (например), или какой-либо другой патч, то этот патч включать не нужно. Желательно патчить только чистые клиенты, без посторонних патчей.

В имени запускаемого клиентского файла не должно быть слова patched, иначе патчер может не получить доступа к процессу клиента.

Патчер желательно запускать от имени администратора.