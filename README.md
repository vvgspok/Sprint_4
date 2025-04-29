## Описание
Данный файл содержит тесты для класса BooksCollector

## Тесты

### test_add_new_book_success
Тест проверяет добавление новой книги в коллекцию .В зависимости от длины названия книги

### test_add_new_book_add_with_the_same_name
Тест проверяет, что книга с тем же названием не может быть добавлена повторно

### test_set_book_genre_success
Тест проверяет, что жанр устанавливается правильно в разных ситуациях

### test_get_book_genre_success
Тест проверяет, что можно получить жанр книги после его установки

### test_get_books_with_specific_genre_success
Тест проверяет, что можно получить список книг с определённым жанром

### test_get_books_genre_success
Тест проверяет, что можно получить текущий словарь books_genre

### test_get_books_for_children_success
Тест проверяет, что можно получить книги, которые подходят детям

### test_get_books_for_children_fail
Тест проверяет, что нельзя получить книги, которые не подходят детям

### test_add_book_in_favorites_success
Тест проверяет добавление книги в избранное, если книга существует в словаре books_genre

### test_add_book_in_favorites_with_the_same_name
Тест проверяет, что книга с тем же названием не может быть добавлена в избранное повторно

### test_delete_book_from_favorites_success
Тест проверяет удаление книги из списка избранного

### test_delete_book_from_favorites_feil
Тест проверяет удаление книги не из списка избранного

### test_get_list_of_favorites_books_success
Тест проверяет получение списка избранных книг 