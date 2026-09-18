# Website for the Magic Stories app / Сайт приложения «Волшебные истории»

Публичный сайт размещается через GitHub Pages:

- https://enotessa.github.io/volshebnye-istorii-site/

English is the default language. Every page has an English URL and a matching Russian version with the `-ru` suffix. The language switch keeps visitors in the same section.

Английский язык используется по умолчанию. У каждой страницы есть английский адрес и соответствующая русская версия с суффиксом `-ru`. Переключатель языка сохраняет текущий раздел.

## Страницы / Pages

- `index.html` / `index-ru.html` — описание приложения, цены, контакты и ссылки на документы;
- `premium-terms.html` / `premium-terms-ru.html` — публичная оферта;
- `subscription-terms.html` / `subscription-terms-ru.html` — понятные условия Premium-подписки;
- `refund-policy.html` / `refund-policy-ru.html` — порядок отказа от услуги и возврата;
- `privacy.html` / `privacy-ru.html` — политика конфиденциальности;
- `premium-return.html` / `premium-return-ru.html` — возврат пользователя в приложение после оплаты;
- `premium-manage.html` / `premium-manage-ru.html` — переход к управлению подпиской;
- `app-ads.txt` — сведения для рекламных систем.

## Публикация

GitHub Pages публикует содержимое ветки `main` из корня репозитория. После изменения правовых документов необходимо также обновить `TERMS_VERSION` в платёжном backend, если новые условия требуют повторного согласия пользователя.

Секретные ключи платёжных, облачных и почтовых сервисов в этот репозиторий не добавляются.
