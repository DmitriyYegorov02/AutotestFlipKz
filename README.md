# AutotestFlipKz
Автоматизированные тесты для сайта Flip.kz

Тест-кейс Gmail: https://docs.google.com/spreadsheets/d/1CQLGZglOFxvR6JpgHISxRnnyCnfCyzoZi8FLByNXxQE/edit?usp=sharing

 Шаги, для запуска тестов:
  1. Разархивировать проект "Test_Flip" в любое удобное место.
  2. Запустить IntelliJ IDEA Community Edition. 
  3. Открыть проект "Test_Flip" 
  4. Подгрузить библиотеку Selenium в файле "pom.xml"
  5. Запустить тесты в порядке очередности, тесты расположены по пути: (Test_Flip\src\main\java\org.example)
 
 Описание тестов:
  1. Test1_Flip_Login - авторизация на сайте Flip.kz.
  2. Test2_Flip_AddingToСart - добавление товара в корзину.
  3. Test3_RemovalFromCart - удаление товара из корзины.

  
 Версии всех инструментов для создания тестов:
   1. IntelliJ IDEA Community Edition 2023.1
   2. Библиотека Selenium-java 4.8.0 
   3. ChromeDriver 111.0.5563.64
   4. Google Chrome 111.0.5563.147
   
 Возникшие сложности при написании тестов:
   1. При запуске каждого теста будет проходить авторизация.
   2. Не удалось создать cookie для пропуска модуля авторизации.
