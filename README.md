-------------Тестове завдання для Front End розробника | Spendbase-------------

1. RTK для керування глобальним сейтом
2. Redux persist для зберігання даних в локал сторедж
3. Reselect для мемоізації селекторів
4. Playwright для e2e тесту
5. Iconify для використання іконок

-------------Встановлення-------------

1. git clone https://github.com/YaroslavRadiant/Folders-test-task.git
2. cd Folders-test-task
3. npm i
4. Для запуску npm start
5. Для тесту npm test

-------------Функціонал-------------

1. Виконана струкнура папок та файлів. Усі файли мають поле access, за допомогою якого доступ до файла може отримати юзер з певною роллю. 
Її можна змінити радіобатонами. Файли та папки без доступу не можна змінити і перемістити. Папки без доступу закриті.
2. При натисканні на + папка відкриється. на - : закриється.
3. При напитсканні на назву папки чи файла з'явиться контекстне меню. 
    1. Редагування назви
    2. Додавання папки (При додаванні використовується вибрана зараз роль)
    3. Додавання файла (При додаванні використовується вибрана зараз роль)
    4. Видалення
    5. Зміна батьківської папки
    Валідації немає.
4. Пусті папки не мають + та - для відкриття та закриття. 
5. Папки та файли без доступу мають іконку замка. Файли з доступом мають іконку відкритого замка.
6. Сині іконки - виключені кнопки.
7. Адмін має доступ до усього, юзер не має доступу до файлів та папок створених адміном.
8. При пошуку будуть знаходитись усі файли та папки, у яких ім'я відповідає символам в інпуті.
9. Написаний тест кейс для пошуку.

-------------Продуктивність-------------
1. Я використав аналогію зв'язного списку для зберігання даних. Це дозволило зберегти перфоманс на хорошому рівні,

так як ми можемо отримувати данні O(1).
2. З деяких мінусів можна відмітити невелику втрату в пам'яті, так як ми окремо зберігаємо id нащадків.

-------------Питання-------------

1. Я не зрозумів цілком завдання додати (індикатор у активному контейнері). Тому не виконав це. Якщо ви надасте мені більше інформації то я дороблю.
