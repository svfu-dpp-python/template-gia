# Шаблон задания для ГИА

## Задание

1. На базе шаблона репозитория создайте свой персональный репозиторий.

2. Напишите код на HTML для шаблонов страниц:

   * `index.html` — шаблон главной страницы. Главная страница должна иметь заголовок (header) с картинкой. В основной части главной страницы должен быть информационный текст и перечень постов.

   * `show_post.html` — шаблон страницы для просмотра поста. Страница просмотра поста должна иметь ссылку для возвращения на главую страницу и текст поста. Для отображения текста поста используйте встроенный фильтр Jinja2 — `safe`.

   * `edit_post.html` — шаблон страницы редактирования поста. Страница редактирования поста должна иметь ссылку для возвращения на главную страницу и форму для редактирования текста поста.

   * `delete_post.html` — шаблон страницы для подтверждения удаления поста. Страница подтверждения удаления поста должна иметь ссылку для возвращения на главную страницу сайта и кнопку подтверждения удаления поста.

   Все страницы сайта должны иметь однотипные фоновые картинки. Основная часть страниц должна быть выведена в одну колонку посередине страницы с шириной 960 пикселей.

3. Напишите класс модели `Post` для создания в базе данных таблицы со следующими полями:

   * `id` — первичный ключ.
   * `title` — заголовок поста.
   * `text` — текст поста.
   * `created` — дата и время создания поста.
   * `modified` — дата и время изменения поста.

4. Напишите код на Python для следующих функций:

   * `index_page()` — Главная страница. На главную страницу должны быть выведены заголовки всех имеющихся в базе постов.
   * `show_post()` — Страница для просмотра поста. На странице поста должна быть кнопка для возвращения обратно на главную страницу сайта, а также должны быть выведены все данные из поста.
   * `edit_post()` — Страница для добавления или редактирования текста поста. Страница должна содержать кнопку возврата обратно на страницу поста (или на главную страницу сайта, если создается новый пост). Страница должна давать возможность отредактировать все поля модели кроме первичного ключа (`id`) и даты и времени изменения поста (`modified`). Дата и время изменения поста должны обновляться автоматически при сохранении изменений в посте.
   * `delete_post()` — Страница для подтверждения удаления поста. На странице должна быть кнопка для возвращения обратно на страницу поста, а также кнопка для подтверждения удаления поста.

5. 

