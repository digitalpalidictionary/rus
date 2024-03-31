# Установка GoldenDict на Linux

## Кратко
1. Скачайте последнюю версию DPD [здесь](https://github.com/digitalpalidictionary/digitalpalidictionary/releases).
2. Установите версию 1.5 GoldenDict.
3. В настройках направьте GoldenDict в папку DPD.

Ниже подробные инструкции *anupubba*.

## Скачать DPD
Прежде всего, скачайте последнюю версию Цифрового Палийского Словаря с [Github](https://github.com/digitalpalidictionary/digitalpalidictionary/releases).

## Создайте папку GoldenDict
Рекомендуется создать легкодоступную папку GoldenDict, например, `/Documents/GoldenDict`.

![создать новую папку](pics/linux-install/create%20new%20folder.png)

Или в терминале:
```
mkdir /home/ваше_имя_пользователя/Documents/GoldenDict
```
(Очевидно, замените ваше_имя_пользователя на ваше реальное имя пользователя)

## Разархивируйте
Щелкните правой кнопкой мыши по zip-файлу DPD в папке Загрузки и откройте его с помощью Архивного менеджера.

![менеджер архивов](pics/linux-install/archive%20manager.png)

Нажмите Извлечь и выберите папку `/Documents/GoldenDict`.

![извлечь](pics/linux-install/extract.png)

Или в терминале:
```
cd home/ваше_имя_пользователя/Загрузки
unzip /home/ваше_имя_пользователя/Загрузки/dpd.zip -d /home/ваше_имя_пользователя/Documents/GoldenDict
```

## Установите GoldenDict
GoldenDict можно установить напрямую с помощью apt-get:
```
sudo apt-get update
sudo apt-get install goldendict
```

Или выберите дистрибутив по вашему выбору с [сайта pkgs.org](https://pkgs.org/download/goldendict).

Или непосредственно из Менеджера программ:

![менеджер программ](pics/linux-install/software%20manager.png)

Убедитесь, что устанавливается версия 1.5, а не версия 1.0!

## Добавление словарей в GoldenDict
1. Запустите приложение GoldenDict.
2. Перейдите в Меню > Редактировать > Словари (Сочетание клавиш **F3**).

![словари F3](pics/linux-install/dictionaries%20F3.png)

3. Перейдите в Источники > Файлы.
4. Нажмите Добавить и выберите папку `/Documents/GoldenDict`.

![добавить](pics/linux-install/add.png)

5. Установите флажок рекурсивного поиска √ (это гарантирует поиск в подпапках).

![рекурсивный](pics/linux-install/recursive.png)

6. Нажмите OK и подождите несколько моментов, пока словари индексируются.

Вы готовы!

Далее узнайте, как [настроить горячую клавишу](setup_hotkey.html) или [настроить всплывающее окно сканирования](setup_scan_popup.html), чтобы вы могли щелкнуть по любому слову Пали в любом тексте и сразу открыть его в словаре.

