#### Служебные пользователи
В этом разделе вы научитесь:
- Настраивать сервисные учетные записи.

<html>
<body>
<ol type="1">
<li> Для начала вам необходимо зайти в консоль администратора, сделать это можно, нажав на иконку пользователя в правом верхнем углу, где затем нажать «Консоль администратора».</li>
<img src="/attachments/images/FAQ/ADMIN/Integration/integr1.jpg"/>
<p>После того, как вы зашли в Консоль Администратора, вам потребуется зайти в разделе "Интеграция" на вкладку «Служебные пользователи».</p>
<img src="/attachments/images/FAQ/ADMIN/Integration/integr2.png"/>
<li> Теперь вам необходимо активировать Пользователя API. Переключив тумблер, выберите какие роли получат возможность использовать интеграцию со сторонними системами (рекомендуем выдавать такие права только Начальнику сервисной службы, либо Администратору). Также выберите участки, информацию по которым хотите интегрировать. Осталось нажать на кнопку «Сгенерировать» и скачать токен доступа.</li>
<img src="/attachments/images/FAQ/ADMIN/Integration/integr3.png"/>

<p>В скачанном текстовом документе скопируйте ключ.</p>
<li> Теперь зайдите в разделе «Интеграция» на вкладку «Ключи».
Создайте 2 ключа: </li>
<ul>
<li> С названием «hubex_token», в поле «Значение» которого введите код из скачанного файла;</li>
<img src="/attachments/images/FAQ/ADMIN/Integration/integr4.png"/>

<li> С названием «request_path», в поле «Значение» которого введите «HubEx.INT.Bitrix24.Api/Api/webhook».</li>
<img src="/attachments/images/FAQ/ADMIN/Integration/integr5.png"/>
</ul>
После создания двух ключей вкладка «Ключи» должна выглядеть так:
<img src="/attachments/images/FAQ/ADMIN/Integration/integr6.png"/>




</ol>
</body>
</html>
____
- [Перейти в меню](http://wiki.hubex.ru)