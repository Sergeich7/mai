## FastAPI & WebSocket.

### ЗАДАЧА:
С использованием fastapi необходимо сделать веб-страницу сочетающую из:

1. Формы с текстовым полем
2. Списком сообщений пронумерованных с 1

Страница подключается к серверу по WebSocket. С помощью формы вы можете отправить сообщение на сервер, где оно будет принято и добавлен порядковый номер этого сообщения. Далее сообщение с порядковым номером отправляется на страницу и отображается в списке. При перезагрузке страницы данные о нумерации теряются и начинается с 1.

Страница должна быть динамической, обрабатывать все действия без перезагрузки.Имеется ввиду что при отправке сообщения на сервер через вебсокет страница не должна перезагружаться.

Взаимодействие с сервером по вебсокет нужно реализовать с использованием JSON. Формат и именование полей не важно. можно использовать любые.
