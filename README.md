# Практическая 5 - Календарь

Необходимо в приложении WPF реализовать календарь учета чего-либо. Тема может быть произвольная

Необходимый функционал:

- Программа должна начинаться с главной страницы - календаря. По умолчанию календарь стоит на текущем месяце
- Должна быть возможность изменения месяца
- Количество карточек с днями должно быть таким же как количество дней в месяце
- По нажатию на карточку открывается страница, где можно выбрать что пользователь в этот день делал (ел, пил, занимался. В данном примере - календаре еды - что именно пользователь ел)
- Из страницы с выбором должна быть возможность выхода без сохранения и выхода с сохранением обратно в страницу с календарем
- Выбранные пункты сохраняются в файл JSON или XML. 
- Иконка первого выбранного пункта должна отображаться в карточке дня
- При повторном заходе на карточку дня в пункты должна выгрузится информация - что было выбрано, а что нет. 
- Значения внутри выбранной карточки дня можно менять, все должно повторно сохраняться
- При повторном открытии приложения вся старая информация выгружается в приложение

Необходимая структура кода:

- Главное окно и окно выбора пунктов должно быть реализовано через страницы
- Квадратик с днем и иконкой элемента должен быть реализован через пользовательский элемент управления
- Внутри квадратика должна быть иконка в качестве картинки
- Пункт выбора должен быть реализован через пользовательский элемент управления
- Внутри пункта должна быть иконка в качестве картинки
- Один пункт должен быть своим типом данных, который содержит в себе название пункта, путь до иконки и выделение (выбран ли пункт или нет).
- Должен быть еще один тип данных - выбор пользователя на день. Он состоит из даты и листа выбранных пунктов
- Должен быть отдельный файл с generic-методами для сериализации и десериализации
- Верстка должна быть адаптивной. За невыполнение этого пункта минус 0,4 балла
- Кроме методов событий должны быть также реализованы отдельные приватные методы (весь код вы пишете не только в методах-событиях)

За каждый невыполненный пункт - минус 0,2 балла. Ниже 2 оценка быть не может
