# Java2

## Общее задание: 

Разработать оконное приложение с одним главным окном и несколькими дочерними диалогами. Вызов диалогов осуществляется через соответствующие пункты меню. Команды меню должны дублироваться на панели инструментов. 
Для реализации приложения необходимо использовать язык Java и одну из графических библиотек SWING/ SWT/ JavaFx. Тип графической библиотеки назначается преподавателем. Нельзя пользоваться редакторами форм!!!!!
Приложение должно быть построено при помощи шаблона проектирования Model-View-Controller.

## Приложение должно уметь:

формировать массив записей путем ввода записей через окна диалога (для полей типа дата использовать соответствующий тип data и компонент для ввода дат);

осуществлять поиск записей в массиве соответствие с условиями, указанными в отдельном диалоговом окне (не в диалоге удаления);

в варианте задания условия поиска должны вводиться в специальном диалоговом окне, результат поиска выводиться в нём же с помощью стандартных элементов управления, выбранной библиотеки пользовательского интерфейса.

удалять запись из массива по условиям, указанным в варианте. Условия удаления должны вводиться в отдельном диалоговом окне (не в диалоге поиска);

пользователю должно сообщаться о том были ли удалены записи, и сколько было удалено, согласно введенным условиям или таких записей не было найдено;

отображать весь текущий массив записей в главном окне приложения с помощью стандартных элементов управления выбранной библиотеки. 

Сохранять и загружать массив записей из указываемого пользователем файла, посредством стандартного диалога сохранения/загрузки. Формат хранения данных в файле XML. Для записи использовать DOM парсер, для чтения SAX парсер.
Для хранения должны использоваться правильные типы. Например, в таблице написано, что поле будет содержать дату рождения, значит, при реализации должен использоваться тип дата для данного поля. На диалогах для ввода даты должен использоваться специальный компонент для ввода дат. Например, календарь, чтобы дату было удобно создать. Если поле хранит число. Например, возраст, значит нужно использовать целочисленный атрибут для хранения возраста.

Вывод записей в главном окне и в диалоге поиска осуществляется в постраничном виде. Например, по 10 записей на странице. Элемент управления страницами должен позволять переходить на первую, последнюю, следующую и предыдущую страницы, должен позволять изменить число записей на странице и показывать текущее число записей на странице, а также должен показывать число всех доступных записей и номер текущей активной страница, а также число всех доступных страниц. Подключение табличного компонента с постраничным выводом должно занимать 2-3 строки кода в каждом диалоге. Каждый диалог работает со своим экземпляром постраничного компонента.

![Вариант задания] 
https://github.com/Dememedp/Java2/raw/master/image.png
