# qa_python

**test_add_new_book_added_book_has_no_genre()** - данный тест проверяет отсутствие жанра у только что добавленной книги.

**test_add_new_book_get_name_new_added_book_from_books_genre()** - данный тест проверяет добавление в словарь книги с нужным названием.

**test_get_books_with_specific_genre_get_list_of_books_with_genre_is_fantastic()** - данный тест проверяет длину списка книг по жанру "Фантастика" 
(добавлено 2 книги, соответственно, длина должна быть равной 2).

**test_set_book_genre_new_book_has_genre()** - параметризованный тест, написаны тестовые данные в виде пары "Название книги": "жанр".
Данный тест проверяет присвоение новой книге определенного жанра, проверяется каждый из жанров.

**test_get_book_genre_book_has_genre_is_detective()** - данный тест проверяет, что у полученной книги "Внутри убийцы" действительно жанр "Детективы".

**test_get_books_for_children_add_two_books_len_equals_two()** - данный тест проверяет, что при добавлении двух книг длина списка будет равна 2.

**test_get_books_genre_add_book_and_books_genre_not_empty()** - данный тест проверяет, что словарь books_genre при добавлении книги не является пустым, так как он содержит уже одну книгу.

**test_add_book_in_favorites_get_name_added_book_from_favorites()** - данный тест проверяет, что книга с нужным названием действительно добавлена в список Избранного.
Проверка названия только что добавленной книги в список, книга с определенным названием присутствует в данном списке.

**test_delete_book_from_favorites_is_empty_after_delete_book()** - данный тест проверяет, что список favorites после добавления и удаления книги пустой.

**test_get_list_of_favorites_books_is_not_empty_after_added_books()** - данный тест проверяет, что если добавить в список favorites книги, он не должен быть пустым.
