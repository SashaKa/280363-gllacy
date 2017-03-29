# Личный проект «Глейси»

* Студент: [Sasha Katushkova](https://up.htmlacademy.ru/htmlcss/15/user/280363).
* Наставник: Ольга Одноколова.

# Техническое задание на вёрстку

* Название сайта: Глейси
* Домен: пока нет

---

1.  **Общие технические требования**

 * 1.1 Стандарты вёрстки: HTML5, CSS3, прогрессивное улучшение.
 * 1.2 Сетка: четыре колонки равной ширины (22.2%).
 * 1.3 Два варианта вёрстки:
	- под фиксированную ширину `900px` или `1200px`: с центровкой основного контента, с некоторыми блоками, которые тянутся на всю ширину;
	- с дополнительной резиновостью (необязательный вариант): диапазон ширин от `900px` до `1200px`.
 * 1.4 Используемые фреймворки: нет.
 * 1.5 Кроссбраузерность: IE10+, Chrome, Firefox, Opera, Safari.
 * 1.6 Типографика: частично определена в макете (прочее — на усмотрение разработчика).
 * 1.7 Используемый шрифт: Roboto (есть в папке с макетом и на Google Fonts).
 * 1.8 С макетом предоставлен `styleguide.psd`, содержащий прорисовку состояний элементов интерфейса. При любых расхождениях с макетами он должен иметь наивысший приоритет.

2.  **Пояснения для учащихся**

 * 2.1 В макетах есть скрытые слои с всплывающими окнами. Такие слои в блоке слоёв фотошопа выделены красным цветом.
 * 2.2 Макеты верстаются постепенно, не нужно сразу выполнять все требования.

3.  **Пожелания к поведению блоков**

   **Все макеты:**

  * 3.1 Контентная область центрируется и не может быть уже макетной ширины.
  * 3.2 Внутренние отступы слева и справа для обоих страницы — по 2.3% от ширины всей контентной области.
  * 3.3 Отступы между колонками сетки одинаковые — по 2.2% от ширины всей контентной области.
  * 3.4 При достижении `1200px` сетка перестаёт масштабироваться дальше.
  * 3.5 Главное меню — при наведении на пункт меню «Каталог» появляется подменю (смотрите папку слоёв «Ховеры» в `gllacy-index.psd`).
  * 3.6 Главное меню — пункт подменю «Сливочное» должен вести на внутреннюю страницу (`gllacy-catalog.psd`).
  * 3.7 Шапка — при наведении на кнопку поиска появляется форма для ввода текста (смотрите папку слоёв «Ховеры» в `gllacy-index.psd`).
  * 3.8 Шапка — при наведении на кнопку «Вход» появляется форма для авторизации (смотрите папку слоёв «Ховеры» в `gllacy-index.psd`).
  * 3.9 Шапка — Если пользователь добавил что-то в корзину, соответствующий пункт в шапке страницы меняет цвет фона на белый. При наведении на этот пункт появляется форма с товарами (смотрите папку слоёв «Ховеры» в `gllacy-index.psd`).
  * 3.10 Если пользователь сделал закладку или добавил что-то в корзину, соответствующий пункт в главной навигации меняет цвет фона на красный.

   **gllacy-index.psd:**

  * 3.11 Логотип не является ссылкой.
  * 3.12 Карусель под шапкой страницы: смена слайдов мгновенная, без промежуточных переходов. При смене слайдов происходит смена фонового цвета на всей странице (смотрите папку слоёв «Фон» в `gllacy-index.psd`).
  * 3.13 Блок карты — достаточная реализация — обычное изображение.
  * 3.14 Блок карты — реализация по желанию — интерактивная карта, которая также масштабируется на 100% ширины, на карте размещён маркер.
  * 3.15 Блок карты — по клику на кнопку «форма обратной связи» возникает модальное окно с формой отправки сообщения (смотрите папку слоёв «Ховеры» в `gllacy-index.psd`), окно позиционируется относительно вьюпорта, а не страницы. При вводе текста в поле формы, «плейсхолдер» должен отобразиться над полем (смотрите папку слоёв «Фидбек» в `styleguide.psd`). Достаточно реализации с обычными плейсхолдерами.
  * 3.16 Карточка товара: поведение этого элемента при наведении на главной странице аналогичны поведению на странице каталога (смотрите в `styleguide.psd`).

   **gllacy-catalog.psd:**

  * 3.17 Логотип — это ссылка на главную страницу.
  * 3.18 В хлебных крошках пункт «Главная» — это ссылка на главную страницу.
  * 3.19 Блок «Цена» — при наведении на любой из маркеров появляется указатель `cursor: pointer`, делать маркеры подвижными не обязательно, цена меняться не должна.
  * 3.20 Фильтр: верстать с помощью формы, кнопка «Применить» отвечает за отправку формы, при выключенном JavaScript должен осуществляться переход на отдельную страницу (отдельную страницу верстать не нужно).
  * 3.21 Количество товаров может быть любым, оно не должно ломать страницу.

=======
