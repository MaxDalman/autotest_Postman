# autotest_Postman
<br>
<strong><i>Nexign test API.postman_collection.json</i></strong> - файл, содержащий коллекцию реквестов на API. 

<p><strong><span>E2E тест, проверяющий корректность работы API на:</span></strong></p>
<ul>
<li><strong><span>Создание записи о питомце;</span></strong></li>
<li><strong><span>Создание записи о пользователе;</span></strong></li>
<li><strong><span>Создание заказа;</span></strong></li>
<li><strong><span>Обновление данных пользователя;</span></strong></li>
<li><strong><span>Удаление всех участников процесса после сделки для экономии места БД;</span></strong></li>
</ul>
<p><span>Перед запуском автоматически происходит удаление используемых переменных в тесте на случай, если они уже заняты в данном окружении.</span></p>
<p><span>В случае необходимости изменить тестовые параметры, необходимо их отредактировать во вкладке&nbsp;</span><strong><em><span>Pre-request script</span></em></strong><span>&nbsp;в методах&nbsp;</span><em><span>POST</span></em><span>&nbsp;и&nbsp;</span><em><span>PUT</span></em><span>.</span></p>
<p><span>После реквестов всегда происходит проверка на корректность кода ответа.</span></p>
