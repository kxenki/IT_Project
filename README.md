# Описание веб-приложения "DATA PROTECTION"

Данное ПО разработано в рамках лабораторных работ по дисциплине "Интернет-технологии".

❗ Проект участвует в конкурсе - команда "Звёздочки Станкина" ❗

## ✅ Описание проекта:

В рамках проекта разработано веб-приложение со следующем функционалом:
1. Работа с электронной подписью (ЭП):
   * создание ЭП;
   * простановка подписи ЭП на файл;
   * проверка подписи ЭП по ее открытому ключу;
   * удаление подписи ЭП.
2. Шифрование/расшифровка файлов.
3. Онлайн-чат между зарегистрированными пользователями (обмен сообщениями, файлами, картинками).

## ✅ Актуальность проекта:

Информационная безопасность — практика предотвращения несанкционированного доступа, использования, раскрытия, искажения, изменения, исследования, записи или уничтожения информации. Это универсальное понятие применяется вне зависимости от формы, которую могут принимать данные.

Обеспечение информационной безопасности помогает защитить информацию пользователя от негативных воздействий. Результатом таких вмешательств может стать потеря важной информации, ее несанкционированное изменение или использование третьими лицами. Поэтому информационная безопасность — это важный аспект защиты пользователей.

Для обеспечения защиты данных пользователей можно использовать следующие методы:
* Электронная подпись (ЭП) позволяет подтвердить авторство электронного документа. Подпись связана как с автором, так и с самим документом с помощью криптографических методов, и не может быть подделана с помощью обычного копирования. 
* Шифрования файлов помогает защитить ваши данные путем шифрования. Расшифровать их может только тот, у кого есть нужный ключ шифрования.  Шифрование данных происходит с помощью какого-либо метода шифрования или ключа (пароля) шифрования/дешифрования, который известен только двум сторонам: отправителю и получателю.

## ✅ Используемые средства разработки ПО:

* Backend:
   + язык программирования С#;
   + платформа разработки веб-приложений ASP.NET Core;
   + технология доступа к данным Entity Framework Core;
   + библиотека ASP.NET для работы в режиме реального времени SignalR;
   + библиотека для работы с ЭП Portable.BouncyCastle.
* Frontend:
   + язык программирования JavaScript;
   + язык гипертекстовой разметки HTML;
   + язык таблиц стилей CSS;
   + фреймворк для создания адаптивного дизайна сайта Bootstrap.
* Совместная разработка ПО и контроль изменений:
   + распределённая система управления версиями Git;
   + веб-сервис для хостинга IT-проектов и их совместной разработки GitHub.

## ✅ Состав команды:

+ ИДМ-22-01:
   * Герасименко Светлана - ***КО (консалтинг)*** - доработка логики ПО, разработка мессенджера. 
   * Помазан Наталья - ***ВН (внедрение)*** - разработка логики ПО по взаимодействию с веб-интерфейсом приложения.
+ ИДМ-22-02:
   * Александр Уколов - ***РП (управление проектами) и СП (системное программирование)*** - координация работы команды, закладка архитектуры ПО, разработка основной логики ПО.
   * Гаврилкин Тимофей - ***АД (администрирование)*** - создание контента и управление системными параметрами приложения, добавление начальных данных для работы ПО, доработка механизмов для работы с веб-интерфейсом.
   * Шукуров	Фарахманд - ***ПП (прикладное программирование)*** - разработка landing page, помощь в создании веб-интерфейса приложения.
   * Сырич Ксения - ***БА (бизнес-анализ)*** - выбор наиболее актуальной сферы для разработки ПО, разработка моделей для взаимодействия клиентской и серверной части приложения.
   * Васильева Татьяна - ***НИ (научные исследования)*** - анализ алгоритмов шифрования (выбор наиболее востребованных) и изучение работы цифровой подписи для передачи данных команде разработки для их реализации, разработка шаблона ответа сервера для клиентской части приложения.

Распределение ролей также показано в Google-таблице:
[Кондуит ИДМ-22](https://docs.google.com/spreadsheets/d/1ypxgDUpNsaAK5PH90dTfGKdtDnWaeEDWfupEbDokN6A/edit?usp=sharing)

## ✅ Landing Page: 
[Landing Page](https://kxenki.github.io/IT_Project/)

## ✅ Дополнительные материалы по проекту:
* [Техническое задание на разработку программного программного продукта](https://github.com/kxenki/IT_Project/blob/main/documents/%D0%A2%D0%B5%D1%85%D0%BD%D0%B8%D1%87%D0%B5%D1%81%D0%BA%D0%BE%D0%B5%20%D0%B7%D0%B0%D0%B4%D0%B0%D0%BD%D0%B8%D0%B5%20%D0%BD%D0%B0%20%D1%80%D0%B0%D0%B7%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D0%BA%D1%83%20%D0%BF%D1%80%D0%BE%D0%B3%D1%80%D0%B0%D0%BC%D0%BC%D0%BD%D0%BE%D0%B3%D0%BE%20%D0%BF%D1%80%D0%BE%D0%B4%D1%83%D0%BA%D1%82%D0%B0.pdf)
* [Календарный график работ по разработке программного продукта](https://github.com/kxenki/IT_Project/blob/main/documents/%D0%9A%D0%B0%D0%BB%D0%B5%D0%BD%D0%B4%D0%B0%D1%80%D0%BD%D1%8B%D0%B9%20%D0%B3%D1%80%D0%B0%D1%84%D0%B8%D0%BA%20%D1%80%D0%B0%D0%B1%D0%BE%D1%82%20%D0%BF%D0%BE%20%D1%80%D0%B0%D0%B7%D1%80%D0%B0%D0%B1%D0%BE%D1%82%D0%BA%D0%B5%20%D0%BF%D1%80%D0%BE%D0%B3%D1%80%D0%B0%D0%BC%D0%BC%D0%BD%D0%BE%D0%B3%D0%BE%20%D0%BF%D1%80%D0%BE%D0%B4%D1%83%D0%BA%D1%82%D0%B0.pdf)
* [Техническая документация программного продукта](https://github.com/kxenki/IT_Project/blob/main/documents/%D0%A2%D0%B5%D1%85%D0%BD%D0%B8%D1%87%D0%B5%D1%81%D0%BA%D0%B0%D1%8F%20%D0%B4%D0%BE%D0%BA%D1%83%D0%BC%D0%B5%D0%BD%D1%82%D0%B0%D1%86%D0%B8%D1%8F%20%D0%BF%D1%80%D0%BE%D0%B3%D1%80%D0%B0%D0%BC%D0%BC%D0%BD%D0%BE%D0%B3%D0%BE%20%D0%BF%D1%80%D0%BE%D0%B4%D1%83%D0%BA%D1%82%D0%B0.pdf)
* [Акт сдачи-приемки программного продукта](https://github.com/kxenki/IT_Project/blob/main/documents/%D0%90%D0%BA%D1%82%20%D1%81%D0%B4%D0%B0%D1%87%D0%B8-%D0%BF%D1%80%D0%B8%D0%B5%D0%BC%D0%BA%D0%B8%20%D0%BF%D1%80%D0%BE%D0%B3%D1%80%D0%B0%D0%BC%D0%BC%D0%BD%D0%BE%D0%B3%D0%BE%20%D0%BF%D1%80%D0%BE%D0%B4%D1%83%D0%BA%D1%82%D0%B0.pdf)
