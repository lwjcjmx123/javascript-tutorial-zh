importance: 5

---

# Поймайте переход по ссылке

Сделайте так, чтобы при клике на ссылки внутри элемента `#contents` пользователю выводился вопрос о том, действительно ли он хочет покинуть страницу и если он не хочет, то прерывать переход по ссылке.

Так это должно работать:

[iframe height=100 border=1 src="solution"]

Детали:

- Содержимое `#contents` может быть загружено динамически и присвоено при помощи  `innerHTML`. Так что найти все ссылки и поставить на них обработчики нельзя. Используйте делегирование.
- Содержимое может содержать вложенные теги, *в том числе внутри ссылок*, например, `<a href=".."><i>...</i></a>`.
