# Тема для сайта [shikimori.org](https://shikimori.org)
Современная тема по мотивам [Material Design](https://material.io/guidelines/) (в меру возможностей CSS). Тема работает только в современных браузерах и не поддерживает UC Browser и Opera Mobile в силу технической невозможности подстроить элементы для каждого из них. Главной особенностью темы является, нет, не обложка в профиле, а удобство пользования: шрифт и активные элементы увеличены, чтобы соответствовать области нажатия на тачскрине. Также увеличено пространство между элементами, изменено положение некоторых элементов, изменена главная страница сайта: теперь это не отправная точка в любой закоулок сайта, а сборник активности пользователей – в центре внимания популярные темы и аниме, новости, опросы, рецензии и ссылки на форум.

Так как сайт часто меняется, в теме могут возникать ошибки, поэтому настоятельно рекомендуется следить за обновлениями темы.

## Установка
Удобнее всего воспользоваться специальным [сайтом-сборщиком](https://grin3671.github.io/shiki-theme/), где можно настроить цвета, обложку и фон по своему вкусу. Нажмите создать тему, и после завершения сборки скопируйте готовый код в настойки внешнего вида сайта.

Важно! Чтобы узнать свой ID, скачайте свою аватарку: цифры в названии файла – это ваш ID.

Все свои настройки указывайте в конце стиля в разделе "Мои настройки":
```css
/* МОИ НАСТРОЙКИ */

/* Фон меню */
.l-top_menu:before {
  background-color: #212121;
}
```

Если по каким-то причинам использовать сборщик не представляется возможным, используйте старый метод установки: выберите из списка готовых стилей, скопируйте код себе в настройки и замените все `2727` на ваш ID.

Список готовых стилей:
* [Светлая тема](../master/prepared/theme-light.css)
* [Светлая тема + Обложка](../master/prepared/theme-light-cover.css)
* [Темная тема](../master/prepared/theme-dark.css)
* [Темная тема + Обложка](../master/prepared/theme-dark-cover.css)

Выберите подходящий вам готовый вариант, скопируйте исходный код в настройки вашего профиля.

#### Установка обложки
Чтобы обложка отображалась в вашем профиле, замените все вхождения `2727` на ваш ID. Вы можете воспользоваться поиском по странице (сочетание клавиш `Ctrl+F` или `Command+F`). Чтобы узнать свой ID, скачайте свою аватарку: цифры в названии файла – это ваш ID. Ссылка на изображение указывается в самом конце файла:
```css
/* Моя обложка в профиле */
.p-profiles .profile-head[data-user-id = "2727"] .c-brief:before {
  /* background-image: url(//i.imgur.com/bd8W6VB.jpg); /* Пример */
  background-image: url(); /* Моя обложка */
  background-position: center;
}
```

## Дополнения
Некоторые задумки, к сожалению, не включены в основную тему из-за неопределенного влияния на остальной дизайн или недостаточного тестирования, однако они могут быть весьма полезны и удобны. Список:
* [Шрифт Roboto](../master/part/font-roboto.css)

    > Для темы больше подходит шрифт Roboto, однако это он может долго грузится на медленном интернете.
    

## Превью
Альбом со скриншотами темы: https://imgur.com/a/tc7uV

## Благодарности
В тестировании темы принимало участие большое количество пользователей, отзывы которых помогли довести дело до победного конца и сделать тему действительно приятной для использования. Большое вам спасибо!

### Поддержать проект
Поддержать создание темы можно сообщив о найденных ошибках и неточностях [автору](https://shikimori.org/grin3671) или создав issue, либо материально:

Яндекс.Деньги: `41001258665103`
