---
title: Создание обслуживаемого оборудования
description: Объект (оборудование) в HubEx - это элемент инфраструктуры, на который направлено предоставление услуг (видов работ). Аналогом
    объекта в ITSM-системах является конфигурационная единица. Создать новый Объект можно в меню Объекты|Оборудование
    по кнопке Создать объект.
keywords: создать объект, оборудование, объект, родительский объект, дочерний объект, история обслуживания, разрешение на подачу заявок, hubex, хабекс, хубекс, хабикс
---


#### Создание обслуживаемого оборудования
В этом разделе вы узнаете:
<html>
<meta charset="utf-8">
<ul>
    <li><a href="#newobject">Как создать объект (оборудование);</a></li>
    <li><a href="#parentchild">Чем отличается родительский объект от дочернего;</a></li>
    <li><a href="#child">Способы создания дочерних объектов;</a></li>
    <li><a href="#tga">Как разрешать подачу заявок на объект (оборудование).</a></li>
</ul>
</html>

<body>
<p><strong>Объект (оборудование)</strong> - элемент инфраструктуры, на который направлено предоставление услуг (видов работ). Аналогом
    объекта в ITSM-системах является конфигурационная единица.
    Например, объектами могут быть: офис, здание, АЗС, магазин, или другой элемент инфраструктуры. Оборудованием может
    быть: кондиционер, кофемашина, двигатель, топливный насос, медицинский аппарат и т.п.</p>
<p> <strong>Объекты</strong> необходимы для ведения учета заявок по различным сущностям: объектам, оборудованию, его компонентам, узлам,
    агрегатам и т.п.
</p>
<p> <strong>Объекты (оборудование)</strong> привязываются к конкретным компаниям-заказчикам.
    Если детальный учет по различным объектам или оборудованию заказчика не требуется, можно завести один обслуживаемый
    объект для каждого заказчика и он автоматически будет подставляться в заявку при выборе заказчика. </p>
<p>Указывая в
    <strong>Заявках</strong> <strong>Объект (оборудование)</strong>, можно в дальнейшем получать детальную
    аналитику обращений клиентов, заказов, выполненных работ по каждой единице оборудования заказчика. Также можно
    назначать <strong>Заявки</strong> по разным <strong>Объектам (оборудованию)</strong> на разных исполнителей.</p>


<h5 id="fillelse">Создание объекта (оборудования)</h5>
<p>Создать новый <strong>Объект</strong> можно в меню <strong>Объекты|Оборудование</strong>
    по кнопке <strong>Создать объект</strong>. При создании форма <strong>Объекта</strong> состоит
    из следующих
    вкладок: <strong>Объект|Оборудование</strong>, <strong>Контакты</strong>, <strong>Обслуживание</strong>, <strong>Дополнительные
        поля</strong>. После сохранения карточки
    <strong>Объекта</strong> на
    форме появятся дополнительные вкладки: <strong>QR-коды</strong>, <strong>Дочерние объекты</strong> и <strong>История
        обслуживания</strong>.
</p>

<div style="display: flex;">
    <img style="margin: 0 auto; display: block; max-width: 47%;"
         src="/attachments/images/FAQ/USER/CreatingObjects/ObjectEmpty.jpg"/> <img
        style="margin: 0 auto; display: block; max-width: 47%;"
        src="/attachments/images/FAQ/USER/CreatingObjects/ObjectMain.jpg"/>
</div>

<p>Рассмотрим заполнение вкладки <strong>Объекты|Оборудование</strong>:</p>
<div>
    <img style="margin: 0 auto; display: block; max-width: 95%;"
         src="/attachments/images/FAQ/USER/CreatingObjects/Object1.jpg"/>
</div>
<ul>
    <li id="#parentchild"><strong>Родительский объект</strong>: Объекты отображаются в системе иерархическим списком
        (количество
        вложенностей не ограничено). Иерархический список представляет собой расположение элементов от родительских к
        дочерним.
        Родительский объект обязательно должен иметь адрес. Для дочернего объекта наличие адреса необязательно, так как
        он будет наследоваться от родителя. Адрес объекта в дальнейшем автоматически подставляется в Заявку по
        выбранному объекту. Признак наличия адреса регулируется <strong>Типом оборудования</strong> (следующее поле).
        <p>Если вы создаете родительский объект, то в этом поле ничего указывать не нужно.</p>
    </li>
    <li><strong>Тип (Тип оборудования)</strong> - это классификатор объектов (оборудования) по признаку наличия адреса.
        <p>В системе HubEx
            по умолчанию созданы следующие базовые типы: <strong>Объект</strong> и <strong>Оборудование</strong>.
            У типа <strong>Объект</strong> по умолчанию в настройках установлен флажок <strong>Обязательное наличие
                адреса</strong>, у типа <strong>Оборудование</strong> его
            нет. Значит, создавая объекты, родительским будет элемент с типом <strong>Объект</strong>, а дочерними с
            типом <strong>Оборудование</strong>.
            Например, <strong>Объектом</strong> может быть Бизнес-центр с адресом ул. Кирова 53, а
            <strong>Оборудованием</strong> – Кофемашина внутри центра,
            при этом у кофемашины может не быть своего адреса, но она будет его наследовать от Бизнес-центра. Другой
            пример:
            <strong>Объектом</strong> может быть Двигатель, а <strong>Оборудованием</strong> его более мелкая часть -
            Топливный насос.</p>
        <p>Создать новый или изменить существующие <strong>Типы объектов</strong> можно в консоли администратора.
            Подробнее читайте в статье <a
                    href="https://wiki.hubex.ru/docs/FAQ/RU/admin/ObjectsType.html">Типы оборудрования</a>.</p>
    </li>

    <li><strong>Компания-владелец</strong>: выберите, какой компании принадлежит обслуживаемое оборудование. Выбор
        осуществляется из списка уже созданных компаний. Подробнее читайте в статье: <a
                href="https://wiki.hubex.ru/docs/FAQ/RU/user/CreatingCompany.html">Создание обслуживаемых компаний</a>;
    </li>
    <li>Флажок <strong>Мобильное оборудование</strong> отвечает за возможность изменить адрес <strong>Объекта</strong>
        при изменении
        адреса в <strong>Заявке</strong>. То есть заполняя <strong>Заявку</strong>, вы можете изменить автоматически
        подставленый из карточки <strong>Объекта</strong>
        адрес, тогда он изменится и в карточке <strong>Объекта</strong>.
    </li>
    <li><strong>Адрес</strong> обязательно указывать для родительских объектов. Дочерний объект может иметь свой
        собственный адрес или наследовать
        его от родителя. Адрес автоматически подставляется в <strong>Заявку</strong>.
    </li>
    <li>в поле <strong>Участок</strong> выберите, к какому участку принадлежит оборудование. <strong>Участок</strong> –
        классификация
        <strong>Объектов</strong>, <strong>Типов заявок</strong>, <strong>Сотрудников</strong>,
        <strong>Зказчиков</strong> по различным критериям: географическим, функциональным и т.д. Например, разделение по
        географии: Северо-Западный округ, Краснодарский
        край, Сибирь и т.д. <strong>Объект</strong> может принадлежать к нескольким участкам одновременно. Подробнее
        читайте в статье: <a href="https://wiki.hubex.ru/docs/FAQ/RU/admin/Places.html">Настройка участков</a>;
    </li>
    <li><strong>Файлы</strong>: При создании нового <strong>Объекта</strong> вы можете приложить файлы для помощи в
        работе с
        оборудованием. Это могут быть фотографии, инструкции в текстовых файлах. К каждому файлу можно ограничить права доступа. Подробнее читайте в статье: a
                href="https://wiki.hubex.ru/docs/FAQ/RU/user/ViewRestriction.html">Ограничение доступа к файлам в заявке и объекте</a>.
        <p>
        <div>
            <img style="margin: 0 auto; display: block; max-width: 80%;"
                 src="/attachments/images/FAQ/USER/CreatingObjects/obj7.png"/>
        </div>
        </p>
    </li>
    <li><strong>График работы</strong> носит справочную информаци. Его заполнять не обязательно.</li>
    <li><strong>Класс (Класс оборудования)</strong> - совокупность объектов (оборудования) с общими характеристиками,
        отличительными
        особенностями. <strong>Классы оборудования</strong> используются для группировки <strong>Объектов</strong> и для
        группировки <strong>Заявок</strong> по <strong>Объектам</strong>.
        Вы можете не использовать <strong>Классы</strong> и устанавливать у всех <strong>Объектов</strong> значение
        <strong>По умолчанию</strong>. Подробнее читайте в
        статье: <a href="https://wiki.hubex.ru/docs/FAQ/RU/admin/ObjectClass.html">Классы оборудования</a>.
    </li>
</ul>


<p>На вкладке <strong>Контакты</strong> можно указать контактную информацию
    ответственного по объекту со стороны заказчика. Также можно ввести дополнительные контакты, например, директора,
    диспетчера.</p>

<div>
    <img style="margin: 0 auto; display: block; max-width: 90%;"
         src="/attachments/images/FAQ/USER/CreatingObjects/Contact.jpg"/>
</div>


<p>На вкладке <strong>Обслуживание</strong> запоняются следующие поля:</p>
<ul>
    <li>В поле <strong>Ответственный за объект</strong> можно указать сервисного инженера, который постоянно обслуживает
        этот
        обект. Эту информацию в дальнейшем можно использовать при настройке автораспределения сотрудников на Заявки.
        Подробнее
        читайте в статье: <a href="https://wiki.hubex.ru/docs/FAQ/RU/admin/RulesOfChoice.html">Правила выбора
            исполнителя</a>.
    </li>
    <li><strong>Вид работ</strong> - специфический вид деятельности (услуг), который может выполняться сотрудником и
        быть направлен на объект. Например, видами работ могут быть: услуги клининга, ремонт, диагностика, услуга аренды
        недвижимости, услуги доставки и т.д. Один из установленных в карточке Объекта <strong>Видов работ</strong>
        выбирается при создании <strong>Заявки</strong>. Также <strong>Вид работ</strong> может быть использован в
        настройке автораспределения сотрудников на заявки. Подробнее
        читайте в статье: <a href="https://wiki.hubex.ru/docs/FAQ/RU/admin/RulesOfChoice.html">Правила выбора
            исполнителя</a>.
    </li>
    <li><strong>Навыки</strong> - дополнительные, особые умения, необходимые для выполнения определенной работы.
        Навыки позволяют дополнительно классифицировать Объекты и Сотрудников (исполнителей). С помощью Навыков можно
        детализировать особые знания, которыми должен обладать специалист для работы с Объектом. Например, знать
        английский язык для настройки приборов на английском языке. Указав Навыки в Объекте и карточке Сотрудника
        (исполнителя), можно настроить правила автоматического распределения исполнителей на заявки. Подробнее
        читайте в статье: <a href="https://wiki.hubex.ru/docs/FAQ/RU/admin/RulesOfChoice.html">Правила выбора
            исполнителя</a>.
    </li>
    <li>Если вы даете гарантию на свои услуги, то ее срок можно отразить с помощью реквизита <strong>На гарантии
        до</strong>.
    </li>
    <li>К <strong>Объекту</strong> можно привязать один <strong>Чек-лист</strong>. <strong>Чек-лист</strong> - это
        контрольный список дел или задач, которые необходимо
        выполнить или проверить по <strong>Объекту</strong>. Подробнее о создании <strong>Чек-листов</strong> читайте <a
                href="https://wiki.hubex.ru/docs/FAQ/RU/users/Checklists.html"> здесь</a>.
    </li>
</ul>

<p></p>

<div>
    <img style="margin: 0 auto; display: block; max-width: 90%;"
         src="/attachments/images/FAQ/USER/CreatingObjects/ObjectService.jpg"/>
</div>


<p>Вкладка <strong>QR-коды</strong> позволит вам промаркировать <strong>Объект</strong> - создать шаблон заявки с
    привязанным QR-кодом, паспорт объекта.</p>
<div>
    <img style="margin: 0 auto; display: block; max-width: 90%;"
         src="/attachments/images/FAQ/USER/CreatingObjects/QR1.jpg"/>
</div>
<p>Сканируя QR-код в мобильном приложении, вы можете просмотреть паспорт объекта и подать по нему Заявку. Также QR-коды
    могут сканировать незарегистрированные в системе пользователи и подавать заявки. Подробнее читайте в статьях: <a
            href="https://wiki.hubex.ru/docs/FAQ/RU/user/QRcodeMain.html">QR-код в HubEx: основные понятия</a>, <a
    href="https://wiki.hubex.ru/docs/FAQ/RU/user/CreatingTaskTemplates.html">Создание шаблона заявки, подача заявки по QR-коду</a>, <a
            href="https://wiki.hubex.ru/docs/FAQ/RU/user/SelfRegister.html">Подача заявок по QR-коду без приложения, самостоятельная регистрация нового пользователя</a>.</p>
<div>
    <img style="margin: 0 auto; display: block; max-width: 70%;"
         src="/attachments/images/FAQ/USER/CreatingObjects/QR2.jpg"/>
</div>

<p>На вкладку <strong>Дополнительные поля</strong> вы можете добавить дополнительные поля для заполнения. Создать
    дополнительные поля можно в консоли администратора. Например, можно указать
    площадь объекта, если это необходимо. Подробнее читайте в статье: <a
            href="https://wiki.hubex.ru/docs/FAQ/RU/user/AdditionalFieldsObject.html">Создание дополнительных полей в объекте</a>.
</p>

<div>
    <img style="margin: 0 auto; display: block; max-width: 80%;"
         src="/attachments/images/FAQ/USER/CreatingObjects/AdditionalField.jpg"/>
</div>

<p>На вкладке <strong>Дочерние объекты</strong> отображаются все дочерние объекты, а также есть возможность создать
    новый дочерний объект по кнопке +. Подробнее о создании дочерних объектов читайте <a href="#child">ниже</a>.
</p>
<p>Во вкладке <strong>История обслуживания</strong> отражаются все созданные по объекту </strong>Заявки</strong>. При установке флажка <strong>С
    вложенными объектами</strong> в списке отразятся <strong>Заявки</strong> по дочерним объектам.
</p>
<div>
    <img style="margin: 0 auto; display: block; max-width: 80%;"
         src="/attachments/images/FAQ/USER/CreatingObjects/History.jpg"/>
</div>

<p> Вы можете ускорить процесс добавления <strong>Объектов</strong> в систему HubEx с помощью функциии <a
        href="https://wiki.hubex.ru/docs/FAQ/RU/user/Import.html#objects">Импорта</a>.</p>
<p> Для выгрузки информации по <strong>Объектам</strong> из системы HubEx можно воспользоваться функцией <a
        href="https://wiki.hubex.ru/docs/FAQ/RU/user/Export.html#objects">Экспорта</a>.</p>

<h5 id="#child">Способы создания дочерних объектов</h5>

<p>Созать дочерний объект в системе можно несколькими способами:</p>
<ol>
    <li>
        После сохранения карточки родительсого объекта на вкладке <strong>Дочерние объекты</strong> по кнопке + можно
        создать новый дочерний объект.
    </li>
    <div>
        <img style="margin: 0 auto; display: block; max-width: 80%;"
             src="/attachments/images/FAQ/USER/CreatingObjects/ChildObject3.jpg"/>
    </div>

    <li>Из карточки родительского объекта по кнопке <strong>Контекстного меню</strong> (3 точки) в правом верхнем
        углу - <strong>Создать
            дочерний объект|оборудование</strong>.
    </li>

    <div>
        <img style="margin: 0 auto; display: block; max-width: 80%;"
             src="/attachments/images/FAQ/USER/CreatingObjects/ChildObject2.jpg"/>
    </div>

    <li><p>В главном меню <strong>Объекты|Оборудование</strong> по кнопке <strong>Создать объект</strong> с указанием
        родительского элемента.</p></li>

    <div>
        <img style="margin: 0 auto; display: block; max-width: 80%;"
             src="/attachments/images/FAQ/USER/CreatingObjects/ChildObject.jpg"/>
    </div>

    <li><p>Выбрав конкретный объект из списка всех объектов в главном меню <strong>Объекты|Оборудование</strong> и нажав
        на кнопку <strong>Контекстного меню</strong> (3 точки) -
        <strong>Создать дочерний объект|оборудование</strong>.</p>
    </li>

    <div>
        <img style="margin: 0 auto; display: block; max-width: 80%;"
             src="/attachments/images/FAQ/USER/CreatingObjects/ObjectList.jpg"/>
    </div>

</ol>

<h5 id="tga">Разрешение на подачу заявок</h5>
<p>При создании нового <strong>Объекта</strong> на форме находится флажок <strong>Разрешить подавать заявки по этому объекту</strong>.
    Включение этой функции позволяет подавать
    <strong>Заявки</strong> по <strong>Объекту</strong>. Если
    вы хотите добавить в систему <strong>Объект</strong>, который в данный момент не обслуживаете или который нуждается в дальнейшем
    редактировании, то влючить эту функцию можно
    позже. Это позволит оптимизировать список <strong>Объектов</strong> и
    рассматривать как те объекты, которые уже обслуживаются, так и те по которым вы еще не проводите работы.</p>
<p>Если флажок был установлен и <strong>Объект</strong> был записан, то снять флажок нельзя - он исчезает с формы записанного
    <strong>Объекта</strong>.</p>

<div>
    <img style="margin: 0 auto; display: block; max-width: 80%;"
         src="/attachments/images/FAQ/USER/CreatingObjects/AllowsCreateTicket.jpg"/>
</div>


</body>

### Следующие шаги:
- [Создание заказчика](./CreatingCustomer.md)
- [Использование МП Заказчика](./CustomerApp.md)
- [Создание плановой заявки](./PlannedTickets.md)


___
- [Перейти в меню](http://wiki.hubex.ru)
