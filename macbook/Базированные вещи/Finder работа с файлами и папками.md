# Операции с файлами и папками

* Переименовать - `Enter`
* Открыть папку \ запустить файл - `Cmd + ▼`
* Перейти на директорию выше - `Cmd + ▲`
* Удалить директорию \ файл
  * В корзину `Cmd + delete`
  * Мимо корзины `Cmd + Opt + delete`. Возникнет окно подтверждения удаления. Можно удерживать `Opt` и тогда в меню File будет пункт "Удалить немедленно" вместо "Переместить в корзину".
* Копировать \ вставить - классические `Cmd + C` и `Cmd + V`

## Скрытые файлы

* Показать \ скрыть скрытые файлы - `Cmd + Shift + .`

## Показать \ скрыть расширения файлов

Настраивается в Finder. `Finder > Настройки > Дополнения > Показывать расширения всех файлов`. 



# Операции с окнами и программами

* Закрыть программу - `Cmd + Q`. Или ПКМ по значку программы в доке и пункт "Завершить".

  Это прямо выйти из программы полностью, выгрузить ее из памяти. На маке программы могут состоять из нескольких окон, поэтому закрытие окна не приводит к закрытию програамы, даже если это окно единственное (TODO: на самом деле не факт, мб после закрытия последнего окна и программа закрывается?). Вместо этого программа "остается в трее", выражаясь терминами windows. Поэтому для закрытия используется отдельное сочетание.

* Закрыть вкладку \ текущее окно - `Cmd + W`. В браузере закрывает текущую вкладку.

  * Закрыть все окна текущей программы - `Cmd + Opt + W`. В некоторых программах открывается много окон. Например, в "Заметках" каждая заметка открывается в отдельном окне. Так можно их закрыть разом все.

* Свернуть текущее окно - `Cmd + M`. При сворачивании окна остаются в доке, каждое окно отдельным элементом.

  * Свернуть все окна текущей программы - `Cmd + Opt + M`.

* Скрыть текущее окно - `Cmd + H`. От сворачивания отличается тем, что окно не появляется отдельным элементом в доке и чтобы его открыть, надо щелкать по пиктограмме программы.

  * Скрыть все окна текущей программы - `Cmd + Opt + H`.

* Переключение между приложениями - `Cmd + Tab`.

  * Переключение между несколькими окнами одного приложения `Cmd + ~`

* Перевести приложение в полноэкранный режим - `Cmd + Ctrl + F`. Повторное нажатие вернет окно в исходное состояние.

* Создать новое окно приложения - `Cmd + N`. Например, открыть дополнительное окно Finder. Насколько я понял, это по сути запустить второй экземпляр приложения. Например, несколько терминалов или браузеров.

* Создать новую вкладку в приложении - `Ctrl + T`. Работает для приложений, которые поддерживают несколько вкладок. Например, браузер. Для некоторых приложений не работает. Например, в "Заметках" открывает какие-то настройки. А для некоторых приложений вроде работает, но как-то странно. Например, в Finder или терминале открывает новые вкладки в том же самом окне, но непонятно, в чем от этого польза. С виду как будто ничего с этим не сделаешь.

* Переключиться на следующую вкладку текущего окна - `Ctrl + Tab`.

  * Переключиться на предыдущую вкладку текущего окна - `Ctrl + Shift + Tab`. Похоже актуально только для браузера. Если создать несколько вкладок, например, в терминале, то сочетания не работают. Хотя в теории было бы удобно, чтобы не скакать между несколькими экземплярами приложения. Но увы.
  
* Открыть окно настроек программы - `Cmd + ,`



TODO: почитать поподробнее, в чем фишка скрытия окна. С виду просто более удобный аналог сворачивания, поскольку спрятанные окна не жрут место в доке, а открыть их можно через клик по пиктограмме программы.

# Кнопки

* Стереть следующий символ - `Fn + Del`
  * Стереть предыдущий символ - `Del` без модификаторов.

# Браузер

* Перейти назад \ вперед по истории - `Cmd + ◄ | ►`
* Увеличить \ уменьшить мастшаб страницы - `Cmd + +`, `Cmd + -`
  * Сбросить масштаб до оригинального `Cmd + 0`