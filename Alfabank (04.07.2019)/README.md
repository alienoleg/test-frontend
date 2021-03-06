# Тестовое задание на позицию стажера в Альфабанк
#### Город: Санкт-Петербург
#### Дата вакансии: 04.07.2019

#### Описание задачи:
Необходимо сделать прототип страницы оплаты банковской картой. Такие страницы часто можно увидеть в интернет-магазинах. На странице должны быть следующие обязательные поля: сумма платежа, номер карты, месяц и год истечения срока действия, имя держателя, CVV код, а также кнопка “Оплатить”.
При нажатии на кнопку данные формы должны отправляться AJAX запросом на сервер (можно сделать заглушку или имитацию ответа от сервера либо реализовать простой node.js сервер). Введенные в форму данные должны проходить валидацию - имя держателя не может содержать цифры, знаки препинания, спецсимволы, в поля номера карты, месяца, года нельзя ввести ничего кроме цифр, сумма платежа должна быть больше 0. Валидация может быть после нажатия кнопки оплаты, отдельным плюсом будет реализация проверки “на лету” при вводе. Если хотя бы одно поле не заполнено или заполнено неправильно, кнопка должна блокироваться, а под полем появляться текст ошибки. Исходный код можно выложить на GitHub/Bitbucket.

#### Обязательные требования: 
- Прототип должен быть реализован с использованием библиотеки компонентов Arui-Feather. 
- Библиотека здесь - https://github.com/alfa-laboratory/arui-feather
- Необходимо использовать React, по возможности также Redux
- Форма должна корректно работать в современных браузерах

#### Приветствуется:
- Использование других библиотек React-Redux экосистемы
- Реализация серверного рендеринга
- Дизайнерский подход к внешнему виду формы
- Дополнительные фичи к форме, не указанные в задании (например определение платежной системы по первым цифрам номера карты и вывод на экран).

#### Ссылки:
- <a target="_blank" href="https://docs.google.com/document/d/1CDCRrysvDINK1IR4PZFao4KTjUJ7YXR69CDT_JRLjI4/edit">Описание
</a> 


