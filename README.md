# Настройка микрофона гарнитуры Fifine H6

<br>

НАСТРОЙКА:

Для начала необходимо установить <a href="https://sourceforge.net/projects/equalizerapo/files/1.3/EqualizerAPO64-1.3.exe/download">Equalizer APO</a> и выбрать микрофон на вкладке Capture devices в Configurator. Компьютер перезагрузится.

* Уровень громкости микрофона в системе: 53<br>

Порядок настройки:

1. Разместить нужные 64-битные DLL плагины в папке "C:\Program Files\VSTPlugins\". Если папки нет, создать.<br>
2. Закинуть config.txt в папку "C:\Program Files\EqualizerAPO\config\"<br>
3. Выбрать микрофон в качестве устройства ввода в Configuration Editor (самый первый фильтр)<br>

Если пути горят красным (File not found), значит нужных плагинов нет по адресу "C:\Program Files\VSTPlugins\", выбирать плагины вручную в Equalizer APO не нужно, настройки собъются. Лучше положить нужные плагины в эту папку и перезапускать программу пока при запуске Equalizer APO не пропадёт красная надпись. Сравните имя файла в папке VSTPlugins и имя файла, которое написано в config.txt, они должны совпадать.<br>

ПЛАГИНЫ:

* LoudMax можно скачать здесь: https://loudmax.blogspot.com/<br>

<b>config.txt</b> содержит настройки, которые исправляют очевидные проблемы АЧХ микрофона и убирают собственные резонансы, добавляют компрессию, лимитер и De-Esser. Найти фаб плагины, которые используются в пресете можно ВКонтакте в файлах по запросу "FabFilter2", размер файла для сверки 4.8 МБ, расширение ".7z". Найти De-Esser, который используется в пресете можно ВКонтакте в файлах по запросу "accusonus4", размер файла для сверки 50.8 МБ, расширение ".7z". Необходимо включить отображение расширений файлов в системе для установки VST плагинов. Для распаковки можно использовать архиватор 7-Zip.

Если вы хотите использовать шумодав от RNNoise, активируйте 3-й фильтр.<br>

RNNoise качественно чистит шумы, сохраняя естественное звучание голоса. Отлично подойдёт для озвучки, стрима, но не подходит для вокала с гитарой или другими инструментами. С гитарой лучше писать без шумодава.
