# Установка GoldenDict на Mac

## Кратко
1. Скачайте последнюю версию DPD [здесь](https://github.com/digitalpalidictionary/digitalpalidictionary/releases).
2. Установите версию 1.5 GoldenDict для [OS X 10.9 Mavericks и выше](https://sourceforge.net/projects/goldendict/files/early%20access%20builds/MacOS/GoldenDict-1.5.0-RC2-372-gc3ff15f%28Qt_563%29.dmg/download) или [OS X 10.12 Sierra и выше](https://sourceforge.net/projects/goldendict/files/early%20access%20builds/MacOS/GoldenDict-1.5.0-RC2-372-gc3ff15f%28Qt_5121%29.dmg/download).
3. В настройках направьте GoldenDict в папку DPD.

Ниже подробные инструкции *anupubba*.

## Скачать GoldenDict
- Если вы используете OS X 10.9 Mavericks или более позднюю версию, [скачайте эту версию GoldenDict с Sourceforge](https://sourceforge.net/projects/goldendict/files/early%20access%20builds/MacOS/GoldenDict-1.5.0-RC2-372-gc3ff15f%28Qt_563%29.dmg/download).
- Если вы используете OS X 10.12 Sierra или более позднюю версию, [скачайте эту версию GoldenDict с Sourceforge](https://sourceforge.net/projects/goldendict/files/early%20access%20builds/MacOS/GoldenDict-1.5.0-RC2-372-gc3ff15f%28Qt_5121%29.dmg/download).
- Более подробную информацию о последней версии GoldenDict для Mac можно найти [здесь](https://github.com/goldendict/goldendict/wiki/Early-Access-Builds-for-Mac-OS-X).

## Установка GoldenDict
1. Дважды щелкните файл .dmg GoldenDict в папке Загрузки.
   ![download gd](pics/mac-install/download%20gd.png)
2. Дважды щелкните установщик.
   ![goldendict install](pics/mac-install/goldendict%20install.png)
3. Вероятно, вы получите предупреждение безопасности. Нажмите "Открыть в любом случае".
   ![warning](pics/mac-install/warning.png)
4. Нажмите "Открыть" на следующем предупреждении безопасности.
   ![allow gd](pics/mac-install/allow%20gd.png)
5. Установка завершена.

## Скачать DPD
Скачайте последнюю версию Цифрового Палийского Словаря для GoldenDict с [Github](https://github.com/digitalpalidictionary/digitalpalidictionary/releases) в вашу папку Загрузки.

## Распаковка
Найдите файл .zip в папке Загрузки и распакуйте его.
![unzip dpd](pics/mac-install/unzip%20dpd.png)

## Создание папки GoldenDict
- Рекомендуется создать легко доступную папку GoldenDict, например `/Documents/GoldenDict`.
  ![documents folder](pics/mac-install/documents%20folder.png)
- Скопируйте распакованную папку DPD в `/Documents/GoldenDict`.
  ![documents gd dpd](pics/mac-install/documents%20gd%20dpd.png)

## Добавление словарей в GoldenDict
1. Запустите приложение GoldenDict.
2. Перейдите в Меню > Правка > Словари (Горячая клавиша **F3**).
   ![edit dictionaries](pics/mac-install/edit%20dictionaries.png)
3. Перейдите в Источники > Файлы. Нажмите Добавить.
   ![sources files](pics/mac-install/sources%20files.png)
4. Выберите папку `/Documents/GoldenDict`.
   ![select gd folder](pics/mac-install/select%20gd%20folder.png)
5. Установите флажок "Рекурсивно" √ (это гарантирует поиск во вложенных папках).
   ![recursive](pics/mac-install/recursive.png)
6. Нажмите "Пересканировать сейчас" или OK и подождите несколько моментов, пока словари индексируются.
   ![indexing](pics/mac-install/indexing.png)

Всё готово!

Можно почитать, как [настроить горячую клавишу](setup_hotkey.html), чтобы вы могли щелкнуть по любому измененному слову Пали в любом тексте и немедленно открыть его в словаре.