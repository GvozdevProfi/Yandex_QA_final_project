<h2>✔️Финальный проект обучения на курсе Яндекса "Инженер по тестированию web-приложений на Python"</h2> 

Тестировался сервис Я Самокат. По заказу самокатов.

Реализация паттерна Page Object. Реализация работы с Selenium. Создание отчетов Allure

_____________________________________________________________________________________________________________________________________________________________


📜**test_Yandex_Orders.py.** Реализованы проверки: 

**1.** Нажать кнопку «Заказать». На странице две кнопки заказа.

**2.** Заполнить форму заказа.

**3.** Проверить, что появилось всплывающее окно с сообщением об успешном создании заказа.

**4.** Проверить: если нажать на логотип «Самоката», попадёшь на главную страницу «Самоката».

**5.** Проверить: если нажать на логотип Яндекса, в новом окне не откроется главная страница Яндекса. Так как произошел ребрендинг.


📜**tests_arrow.py** Реализованы проверки:

 — Выпадающий список в разделе «Вопросы о важном». Нужно проверить: когда нажимаешь на стрелочку, открывается
 соответствующий текст. Важно написать отдельный тест на каждый вопрос.
 
 
 📜**Описание файлов паттерна Page Object:**
 
— **conftest.py** - инициализация браузера и фикстуры

— **BaseApp.py** - определяем базовые методы для работы с WebDriver

— **PageObjects.py** - локаторы и методы 
