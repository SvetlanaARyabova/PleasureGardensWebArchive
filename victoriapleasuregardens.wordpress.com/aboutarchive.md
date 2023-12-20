# Архив сайта "Victoria pleasure gardens" https://victoriapleasuregardens.wordpress.com

### Оглавление:

- [*описание архива*](https://github.com/SvetlanaARyabova/PleasureGardensWebArchive/blob/main/americanpleasuregardens.com/aboutarchive.md#описание)
- [*анализ архивируемости*](https://github.com/SvetlanaARyabova/PleasureGardensWebArchive/blob/main/americanpleasuregardens.com/aboutarchive.md#анализ-архивабилити)
- [*анализ архива*](https://github.com/SvetlanaARyabova/PleasureGardensWebArchive/blob/main/americanpleasuregardens.com/aboutarchive.md#анализ-архива)
- [*просмотр архива*](https://github.com/SvetlanaARyabova/PleasureGardensWebArchive/blob/main/americanpleasuregardens.com/aboutarchive.md#просмотр-архива)

## Описание

Архив содержит снимок всех страниц сайта **"Victoria pleasure gardens"** по состоянию на 18.12.2023. Размер архивного файла составляет **50049 Кб**. Кроме самого архивного файла при создании архива записаны файлы индексов, логов и файл базы данных сайта.

## Анализ архивируемости

Перед архивацией с помощью инструмента [ArchiveReady](https://archiveready.com/) был проведен анализ сайта. При предварительной оценке архивируемости  перед архивацией были определены потенциально проблемные моменты. Общая  оценка архивируемости сайта составила **79%**;

Самый низкий процент у показателя **Accessibility** или доступности, он составляет **60%** по следующим причинам:

- неработающих ссылок на внешние ресурсы

<img src="/americanpleasuregardens.com/images/image-20231220222108047.png"/>

- встроенных элементов скрипта

<img src="/americanpleasuregardens.com/images/image-20231220222155671.png"/>

- низкой скорости ответа сайта

<img src="/americanpleasuregardens.com/images/image-20231220222233491.png"/>

- нехватки файла с картой сайта (sitemap),  защиты доступа для автоматических систем (роботов)

<img src="/americanpleasuregardens.com/images/image-20231220222336746.png"/>

Процент **соответствия стандартам (Standards Compliance)** составляет **66%**. Снижение процентов происходит из-за несоответствия кода страницы принятым стандартам.

- несоответствия в коде CSS и HTML

<img src="/americanpleasuregardens.com/images/image-20231220223013266.png"/>

Показатель **согласованности (Cohesion) — 90%** снижен из-за

- ссылок на внешние скрипты, размещенные на внешних ресурсах

<img src="/americanpleasuregardens.com/images/image-20231220223151755.png"/>

Показатель по **метаданным (Metadata)** составляет **100%**

[К оглавлению](#оглавление)

------

## Анализ архива

Архивный файл был проанализирован с помощью утилиты  командной строки, созданной для задач цифрового дознания, сбора данных  из архивов веб-сайтов — [Metawarc](https://github.com/datacoon/metawarc)

Архив был проанализирован с помощью команды `-analyze` в полученном ответе команды в последней строке подсчитывается общее  количество файлов, размер архива в байтах. В перечне типов файлов  перечислены все встречающиеся в архиве типы данных, указано количество  файлов каждого типа, их общий размер и процент от общего объема.

<img src="/americanpleasuregardens.com/images/image-20231220223409017.png"/>

Судя по анализу сайта можно сказать, что большую часть архива ~ 87% составляет текст.

С помощью утилиты Metawarc была также команда `-index`, записывающая все метаданные в базу данных. Записано более 89% файлов.

<img src="/americanpleasuregardens.com/images/image-20231220223816232.png"/>

С помощью команды `metawarc stats -m mimes` проанализирован размер, типы данных и их кодировки.

<img src="/americanpleasuregardens.com/images/image-20231220224019811.png"/>

Из получившейся таблицы видно, что больше всего используется язык HTML.

При анализе архива с помощью команды `metawarc stats -m exts`, видим, что показатели отличаются. У большей части файлов расширение не определено. Значительную группу составляют файлы PHP. Движок PHP создает из кода HTML-контент, который мы видим в браузере.

<img src="/americanpleasuregardens.com/images/image-20231220224233824.png"/>

[К оглавлению](#оглавление)

------

## Просмотр архива

При просмотре архива с помощью расширения [Replay Web Page](https://replayweb.page/) открывается главная страница, корректно работает переход по разделам  сайта. Не везде сохранилось корректное форматирование. При переходе по  разделам меню сталкиваемся с тем, что многие картинки не отображаются.

<img src="/americanpleasuregardens.com/images/image-20231220225142097.png"/>

Возникает ошибка при переходе на внешние сайты, где  размещен представленный контент

<img src="/americanpleasuregardens.com/images/image-20231220225328068.png"/>

Это подтверждает предусмотренные анализом ошибки при   архивировании сайтов со ссылками на контент, размещенный на внешних   источниках.

[К оглавлению](#оглавление)
