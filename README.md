v8CfgAddsAhk
============
Набор скриптов для автоматизации ряда действий в конфигураторе.

Реализует часть функционала из Снегопат (https://snegopat.ru/)

Описание + скрины: http://itpath.ru/v8cfgaddsahk/

Установка
------------
1. Установить Autohotkey (http://www.autohotkey.com/)
2. Зарегистрировать библиотеки: 
	- v8CfgAddsAhk\system\svcsvc.dll
	- v8CfgAddsAhk\system\WshExtra.dll
	
Запуск
------------
- v8CfgAddsAhk\v8CfgAdds.ahk (Основной набор скриптов)
- v8CfgAddsAhk\continueRow.ahk (Операции по переносу комментариев, строк). Автор ADirks

Реализованные функции
------------

- Вызов списка процедур: {ctrl +1}
- Поиск с рег.выражениями: {Alt+f}
- Поиск с рег.выражениями (результат последнего поиска): {Alt+r}
- Закоментировать строку: {ctrl + / (ctrl + .)}
- Развернуть модуль: {ctrl+i}
- Удаление строки: {Ctrl+y}
- Авторские комментарии:
	- блок добавлен: {alt+s}
	- блок изменен: {alt+e}
	- блок удален: {alt+d}
- Cимвол '<': {Ctrl-,}
- Cимвол '>': {Ctrl-.}
- Cимвол '|': {Ctrl-\}
- Cимвол '&': {Ctrl-&}
- Cимвол '[': {Alt-[}
- Cимвол ']': {Alt-]}
- Копирование текущей строки и вставка в следующей: {ctrl+d}
- Переход в процедуру: {ctrl+enter}
- Возврат на предыдущую позицию: {Alt,-}
- Добавление ссылки на основной реквизит в модуле (преобразование модуля формы из обычных форм в управляемые): {Alt+h}
- Генератор кода для объектов метаданных (требуется предварительная генерация файла структуры обработкой v8CfgAddsAhk\ext\ПолучениеСтруктуры.epf): {Alt+g}
- Форматирование модуля: {F6} (code_beautifier.pl - ADirks)
- Препроцессор функции: {Alt+7}
- Выбор ранее набранных слов: {ctrl+w}
- Выбор заранее заготовленных слов\фраз (файл words.txt в корне директории скриптов)
- Переход в начало метода: {Ctrl+b}
- Переход в конец метода: {Ctrl+e}
- Переход по областям: {Ctrl+2}
- Поиск метаданных по имени: {Alt+j}