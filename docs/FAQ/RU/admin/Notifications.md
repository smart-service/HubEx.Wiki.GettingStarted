#### Настройка уведомлений
<html>
<meta charset="utf-8">
<title>Быстрый переход внутри документа</title>
<ul>
     <li><a href="#rocr">Правила выбора получателя;</a></li>
     <li><a href="#notiftrig">Триггеры уведомления.</a></li>
</ul>
</html>

<h5 id="rocr">Правила выбора получателя.</h5>
Первым шагом в настройке нового уведомления является создание нового "Правила выбора получателя", перейдя на вкладку с соответствующим названием, Вы увидите список уже созданных правил.

![notif1.png](/attachments/images/FAQ/ADMIN/Notifications/notif1.png)

Нажмите "Создать правило выбора получателя", после чего откроется окно создания нового правила.

![notif2.png](/attachments/images/FAQ/ADMIN/Notifications/notif2.png)

В нём обязательно укажите название нового правила выбора получателя. В полях "Получатели уведомления", "Пользователь который получит уведомление", "Роль, которая получит уведомления" укажите тех пользователй, который должны будут получить уведомление. **Обратите внимание, если вы выберете пользователя в системе, а также укажете его "Роль", то он получит 2 уведомления.** Если же вы хотите получить уведомление на почту, то заполните поле "E-mail адреса, которые получат уведомления."

![notif3.png](/attachments/images/FAQ/ADMIN/Notifications/notif3.png)

После заполнения всех полей, нажмите кнопку сохранить.

<h5 id="notiftrig">Триггеры уведомления.</h5>
Теперь перейдем к созданию триггера уведомления. Перейдя на вкладку с соответствующим названием, Вы увидите список уже созданных триггеров.

![notif4.png](/attachments/images/FAQ/ADMIN/Notifications/notif4.png)

Для того чтобы создать новый "Триггер уведомления", нажмите "Создать новый триггер уведомления", после чего откроется новая страница, где надо будет указать требуемую информацию.

![notif5.png](/attachments/images/FAQ/ADMIN/Notifications/notif5.png)
<ul>
<li> Заполните поле "Название триггера", далее в "Условиях отправки" укажите условия, при которых будет отправлено уведомление. Обратите внимание, что, например, заполнив поля "Событие из-за которого сработает триггер" и "Стадии заявки, на которых будет отправлено уведомление", придет 2 уведомления.</li>
<li> В поле "Шаблон сообщения" также требуется заполнить все поля. В описании сообщения Вы можете выбрать уже существующее описание, после чего скопировать его текст, а потом создать новое. Это облегчит Вам задачу, так как в тексте сообщения могут использоваться специальные термины (например, "@Model.TaskNumber").</li>
<li> Выберите "Тт", если хотите отправить push-уведомление или же "M со стрелкой вниз" для e-mail.</li>
<li> Если вы хотите, чтобы конкретный пользователь получил уведомление, сделать это можно посредством добавления "Правила выбора получателя". Чтобы его добавить, нажмите "Добавить правило выбора получателя" и выберите его из списка.</li>
</ul>

![notif6.png](/attachments/images/FAQ/ADMIN/Notifications/notif6.png)

После заполнения всех полей, нажмите кнопку сохранить.

### Следующие шаги:
- [Дополнительные поля](./TicketAttribute.md)
- [Интеграция](./Integration.md)



____
- [Перейти в меню](http://wiki.hubex.ru)