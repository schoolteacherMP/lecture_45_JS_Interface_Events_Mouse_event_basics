# lecture_46_JS_Interface_Events_Mouse_event_basics  

#  [Задачи ](https://github.com/schoolteacherMP/lecture_46_JS_Interface_Events_Mouse_event_basics/blob/main/tasks.md)  

События мыши имеют следующие свойства:

-  Кнопка: button.

-  Клавиши-модификаторы (true если нажаты): altKey, ctrlKey, shiftKey и metaKey (Mac).

-  Если вы планируете обработать Ctrl, то не забудьте, что пользователи Mac обычно используют Cmd, поэтому лучше проверить if (e.metaKey || e.ctrlKey).
-  Координаты относительно окна: clientX/clientY.

-  Координаты относительно документа: pageX/pageY.

Действие по умолчанию события mousedown – начало выделения, если в интерфейсе оно скорее мешает, его можно отменить.
