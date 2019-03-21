---
title: Шаблоны заявок и паспорт объекта.
description: Как создать шаблон заявки, а также посмотреть паспорт оборудования в системе HubEx?
---

<!-- Yandex.Metrika counter -->
<script type="text/javascript" >
   (function(m,e,t,r,i,k,a){m[i]=m[i]||function(){(m[i].a=m[i].a||[]).push(arguments)};
   m[i].l=1*new Date();k=e.createElement(t),a=e.getElementsByTagName(t)[0],k.async=1,k.src=r,a.parentNode.insertBefore(k,a)})
   (window, document, "script", "https://mc.yandex.ru/metrika/tag.js", "ym");
   ym('{{ site.yandex_metric }}', "init", {
        id:'{{ site.yandex_metric }}',
        clickmap:true,
        trackLinks:true,
        accurateTrackBounce:true,
        webvisor:true
   });
</script>
<noscript><div><img src="https://mc.yandex.ru/watch/'{{ site.yandex_metric }}'" style="position:absolute; left:-9999px;" alt="" /></div></noscript>
<!-- /Yandex.Metrika counter -->

#### Шаблоны заявок и паспорт объекта
В этом разделе вы научитесь:
- Создавать шаблоны заявок
- Просматривать паспорт объекта

Для быстрой подачи заявки на обслуживание конкретного оборудования имеется возможность создать заявку с заполненными полями, используя для создания шаблон заявки.
>**Для создания шаблона заявки перейдите в пункт «Заявки» бокового меню на вкладку «Шаблоны заявок». Нажмите на кнопку «Создать шаблон». Заполните необходимые поля на форме создания шаблона, сохраните.
Для того, чтобы иметь возможность подать заявку с использованием созданного шаблона, необходимо опубликовать шаблон. Откройте выпадающее меню на странице готового шаблона и выберите пункт «Опубликовать».**

![templt1.png](/attachments/images/FAQ/USER/CreatingTickTemplates/templt1.png)

При создании нового шаблона заявки обратите внимание на поле «Опубликовать», если стоит галочка, то все пользователи смогут увидеть при сканировании QR-кода паспорт оборудования со всеми его атрибутами, в противном случае только зарегистрированные пользователи могут подавать заявки. Чтобы любой желающий мог подать заявку по этому шаблону заявки, Вам требуется сделать данный шаблон заявки публичным. Для того, чтобы новый пользователь при регистрации получил определенные роль и тип в системе, Вам необходимо привязать Шаблон сотрудника к Шаблону заявки. Сделать это можно посредством добавления приглашения при создании Шаблона заявки.

>**Приглашение - определяет с какой ролью и типом будет создан новый самозарегестрировавшийся пользователь.**

>**Код шаблона объекта -  при создании шаблона заявки Вы можете обратить внимание на поле «Код шаблона», это поле отвечает за связь между шаблоном заявки и шаблоном объекта, также Вы можете вставить в это поле собственный код, однако в таком случае функция «паспорт объекта» не будет работать.**

Очень важно отметить, что создать шаблон заявки, который также будет являться паспортом объекта, можно сделать напрямую со страницы созданного оборудования. Для этого надо открыть профиль оборудования, после чего перейти в раздел QR-коды, где нажать на кнопку «Маркировать», которая вас перенесет на страницу создания нового шаблона заявки. 

## Паспорт объекта
При сканировании QR кода можно получить паспорт объекта, в котором указаны основная информация и публичные файлы и документы по объекту.

<div>
  <img  style="margin: 0 auto; display: block; max-width: 100%;" src="/attachments/images/FAQ/USER/CreatingTickTemplates/templt2.jpg" />
</div>



### Следующие шаги:
- [Саморегистрация и подача заявок](./SelfRegister.md)
- [Ограничение видимости файлов](./ViewRestriction.md)
- [Сообщения по заявке и вкладка сообщения](./Messages.md)


___
- [Перейти в меню](http://wiki.hubex.ru)