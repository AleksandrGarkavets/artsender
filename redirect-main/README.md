# redirect
<p>Свой укорачиватель ссылок с отслеживанием перехода в Smart Sender<br>
<img src="https://image.mufiksoft.com/chrome_t6stICDeNy.jpg" alt="Пример" style="width: 600px"></p>
<p>Разместите файл на Вашем хостинге и используйте его для укорачивания любых ссылок, чтобы иметь возможность отслеживать переходы по ссылкам в тексте сообщений</p>
<p>Чтобы создать уникальную ссылку, используйте внешний запрос типа POST со следующим телом запроса:</p>
<p>{<br>
"userId":"{{ userId }}",<br>
"url":"https://smartsender.com",<br>
"tag":"Название тега",<br>
"funnel":"Название воронки"<br>
}<br></p>
<p>userId - идентификатор пользователя. Переменная {{ userId }}. Обьязательно.<br>
url - ссылка, которую нужно сократить/отследить переход. Обьязательно<br>
tag - Название тега, который необходимо добавить пользователю при переходе. Необьязательно<br>
funnel - Название воронки, на которую нужно подписать пользователя при переходе. Необьязательно<br></p>
