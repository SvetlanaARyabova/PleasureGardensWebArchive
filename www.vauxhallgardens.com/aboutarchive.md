# Архив сайта "Vauxhall pleasure gardens" http://www.vauxhallgardens.com/

### Оглавление:

- [*описание архива*](https://github.com/SvetlanaARyabova/PleasureGardensWebArchive/blob/main/americanpleasuregardens.com/aboutarchive.md#описание)
- [*анализ архивируемости*](https://github.com/SvetlanaARyabova/PleasureGardensWebArchive/blob/main/americanpleasuregardens.com/aboutarchive.md#анализ-архивабилити)
- [*анализ архива*](https://github.com/SvetlanaARyabova/PleasureGardensWebArchive/blob/main/americanpleasuregardens.com/aboutarchive.md#анализ-архива)
- [*просмотр архива*](https://github.com/SvetlanaARyabova/PleasureGardensWebArchive/blob/main/americanpleasuregardens.com/aboutarchive.md#просмотр-архива)

## Описание

Архив содержит снимок всех страниц сайта **"Vauxhall pleasure gardens"** по состоянию на 18.12.2023. Размер архивного файла составляет **14 649 Кб**. Кроме самого архивного файла при создании архива записаны файлы индексов, логов и файл базы данных сайта.

## Анализ архивируемости

Перед архивацией с помощью инструмента [ArchiveReady](https://archiveready.com/) был проведен анализ сайта. При предварительной оценке архивируемости  перед архивацией были определены потенциально проблемные моменты. Общая  оценка архивируемости сайта составила **84%**;

Самый низкий процент у показателя **Accessibility** или доступности, он составляет **63%** по следующим причинам:

- неработающих ссылок на внешние ресурсы

![image-20231220232516274](C:\Users\nefer\AppData\Roaming\Typora\typora-user-images\image-20231220232516274.png)

- нехватки файла с картой сайта (sitemap),  защиты доступа для автоматических систем (роботов)

![image-20231220232654326](C:\Users\nefer\AppData\Roaming\Typora\typora-user-images\image-20231220232654326.png)

Процент **соответствия стандартам (Standards Compliance)** составляет **73%**. Снижение процентов происходит из-за несоответствия кода страницы принятым стандартам.

- несоответствия в коде HTML

![image-20231220232805533](C:\Users\nefer\AppData\Roaming\Typora\typora-user-images\image-20231220232805533.png)

- найдены ошибки воспроизведения изображений:

![image-20231220232858937](C:\Users\nefer\AppData\Roaming\Typora\typora-user-images\image-20231220232858937.png)

Показатель **согласованности (Cohesion) — 100% **метаданных (Metadata)** составляет **100%**

[К оглавлению](https://github.com/SvetlanaARyabova/PleasureGardensWebArchive/blob/main/americanpleasuregardens.com/aboutarchive.md#оглавление)

------

## Анализ архива

Архивный файл был проанализирован с помощью утилиты  командной строки, созданной для задач цифрового дознания, сбора данных  из архивов веб-сайтов — [Metawarc](https://github.com/datacoon/metawarc)

Архив был проанализирован с помощью команды `-analyze` в полученном ответе команды в последней строке подсчитывается общее  количество файлов, размер архива в байтах. В перечне типов файлов  перечислены все встречающиеся в архиве типы данных, указано количество  файлов каждого типа, их общий размер и процент от общего объема.

![image-20231220233226662](C:\Users\nefer\AppData\Roaming\Typora\typora-user-images\image-20231220233226662.png)

Судя по анализу сайта можно сказать, что большую часть архива составляют изображения (55%) и текст (45%).

С помощью утилиты Metawarc была также команда `-index`, записывающая все метаданные в базу данных. Записано 100% файлов.

![image-20231220233446939](C:\Users\nefer\AppData\Roaming\Typora\typora-user-images\image-20231220233446939.png)

С помощью команды `metawarc stats -m mimes` проанализирован размер, типы данных и их кодировки.

![image-20231220233542303](C:\Users\nefer\AppData\Roaming\Typora\typora-user-images\image-20231220233542303.png)

Из получившейся таблицы видно, что больше всего используется язык HTML.

При анализе архива с помощью команды `metawarc stats -m exts`, видим, что для текстовых файлов использован язык html, a изображения в формате jpg.

![image-20231220233707175](C:\Users\nefer\AppData\Roaming\Typora\typora-user-images\image-20231220233707175.png)

[К оглавлению](https://github.com/SvetlanaARyabova/PleasureGardensWebArchive/blob/main/americanpleasuregardens.com/aboutarchive.md#оглавление)

------

## Просмотр архива

При просмотре архива с помощью расширения [Replay Web Page](https://replayweb.page/) открывается главная страница, корректно работает переход по разделам  сайта. 

![image-20231220234110263](C:\Users\nefer\AppData\Roaming\Typora\typora-user-images\image-20231220234110263.png)

Возникает ошибка при переходе на внешние сайты, где размещен представленный контент

[К оглавлению](https://github.com/SvetlanaARyabova/PleasureGardensWebArchive/blob/main/americanpleasuregardens.com/aboutarchive.md#оглавление)
