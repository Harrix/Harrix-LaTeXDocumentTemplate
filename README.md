HarrixLaTeXDocumentTemplate
===========================

Версия 1.9

Шаблон документов в LaTeX на русском языке. Данный шаблон применяется в проектах HarrixTestFunctions, MathHarrixLibrary, Standard-Genetic-Algorithm  и др.

https://github.com/Harrix/HarrixLaTeXDocumentTemplate

Шаблон распространяется по лицензии Apache License, Version 2.0.

Про структуру проекта
---------------------

Главными файлами являются:
 - **names.tex** - переопределение некоторых имен и команд в пакетах;
 - **packages.tex** - подключение пакетов для *.tex файлов;
 - **styles.tex** - стили оформления документа, руссификация некоторых пакетов;

Все остальное - это примеры использования этих файлов.

Сведения для редактирования файлов
----------------------------------

Для полноценной работы редактированию LaTeX документа вам потребуются программа для компиляции *.tex документов в *.pdf. Автор использует для этого связку MiKTex и TeXstudio. 

В варианте, который использует автор, в *.tex файлах справок для отображения русских букв используется модуль pscyr. Об его установке (и можно там скачать) можно прочитать в статье http://blog.harrix.org/?p=444.

Проекты, которые связаны с данным шаблоном
------------------------------------------

 * **HarrixBiblio** - файл библиографических ссылок **biblio.bib**, которые я использую в своих статьях в формате LaTeX: https://github.com/Harrix/HarrixBiblio
 * **HarrixLaTeXSymbols** - глава о условных обозначениях, которые используются в LaTeX документах. Использую у себя в крупных работах с математическим уклоном:https://github.com/Harrix/HarrixLaTeXSymbols
 * **HarrixQtLibraryForLaTeX** - библиотека для отображения различных данных в LaTeX файлах: https://github.com/Harrix/HarrixQtLibraryForLaTeX
 * **HarrixClass_DataOfHarrixOptimizationTesting** - класс HarrixClass_DataOfHarrixOptimizationTesting для считывания информации формата данных Harrix Optimization Testing на C++: https://github.com/Harrix/HarrixClass_DataOfHarrixOptimizationTesting


История проекта
---------------

Подробный список изменений в файле [CHANGELOG.md](../master/CHANGELOG.md).

Контакты
--------

Автор: Сергиенко Антон Борисович (Сибирский государственный аэрокосмический университет имени академика М.Ф. Решетнева).

С автором можно связаться по адресу sergienkoanton@mail.ru или  http://vk.com/harrix .

Сайт автора, где публикуются последние новости: http://blog.harrix.org, а проекты располагаются по адресу http://harrix.org .