1. Форкаем этот репозиторий.
2. [Создаем API ключ](https://github.com/settings/tokens/new), нажимаем Generate new token (classic). Выставляем "No 
Expiration" и прожимаем все галочки. Копируем ключ и сохраняем для дальнейшего
использования.
![telegram-cloud-photo-size-4-5894089822413369445-w](https://github.com/hhermesa/randomCatFacts/assets/56301001/4186ea57-a5c0-439f-8ad2-fae44f83f903)
3. Повторяем первые два шага для каждого GitHub аккаунта.
4. Переходим на [PipeDream](https://pipedream.com), регистрируемся и создаем Workspace.
5. Далее создаем Workflow и создаем временной триггер:
6. Выставляем нужный вам график commit`ов в гитхабе.
7. Далее генерируем тестовый ивент и выбираем его.
8. Выбираем Custome Code и вставляем код из файла [main.js], который будет активироваться по временному триггеру.
В коде меняем token и name на ваш API ключ и юзернейм аккаунта Github, соответственно. Через запятую указываем любое кол-во аккаунтов, сохраняя при 
этом порядок ввода (если API ключ введен третьим по счету, то и юзернейм должен 
быть третьим). 
9. Жмем Deploy и сохраняем Workflow.
