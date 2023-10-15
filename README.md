___
 # 1) Задание:
 **Представьте, что вы работаете над разработкой простого приложения для записной книжки 🗒, которое позволяет пользователям добавлять, редактировать и удалять контакты.
  Ваша задача - придумать как можно больше различных тестов (юнит-тесты, интеграционные тесты, сквозные тесты) для этого приложения.    
  Напишите название каждого теста, его тип и краткое описание того, что этот тест проверяет.**
___

 * Тест добавления контакта (юнит-тест):  Проверяет, правильно ли приложение добавляет новый контакт в записную книжку.
 * Тест редактирования контакта (юнит-тест):  Проверяет, правильно ли приложение обновляет существующий контакт в записной книжке.
 * Тест удаления контакта (юнит-тест):  Проверяет, правильно ли приложение удаляет контакт из записной книжки.  
 * Тест поиска контакта (юнит-тест):  Проверяет, правильно ли приложение находит контакт по заданному критерию поиска.  
 * Тест проверки уникальности контакта (юнит-тест):  Проверяет, что приложение не позволяет добавить два одинаковых контакта.   
 * Тест сохранения и загрузки данных (интеграционный тест): Проверяет, правильно ли приложение сохраняет данные в файл и загружает их обратно.   
 * Тест взаимодействия пользовательского интерфейса (сквозной тест): Проверяет, что пользовательский интерфейс работает корректно и соответствует ожиданиям пользователя.   
 * Тест производительности (сквозной тест): Проверяет, как приложение справляется с большим количеством контактов и операций.   
 * Тест обработки ошибок (сквозной тест): Проверяет, как приложение обрабатывает различные типы ошибок и исключений.   
 * Тест безопасности (сквозной тест): Проверяет, что приложение корректно обрабатывает попытки несанкционированного доступа или другие потенциальные угрозы безопасности.   
___

# 2) Задание:
**Ниже список тестовых сценариев.   
Ваша задача - определить тип каждого теста (юнит-тест,
интеграционный тест, сквозной тест) и объяснить, почему вы так решили.   
● Проверка того, что функция addContact корректно добавляет новый контакт в список контактов.   
● Проверка того, что при добавлении контакта через пользовательский интерфейс, контакт корректно
отображается в списке контактов".   
● Проверка полного цикла работы с контактом: создание контакта, его редактирование и
последующее удаление.**   
___

* Тест “Проверка того, что функция addContact корректно добавляет новый контакт в список контактов”  юнит-тест.
  Они предназначены для проверки отдельных “единиц” кода, таких как функции или методы. В данном случае, мы тестируем функцию addContact, которая является отдельной “единицей” в приложении.
  Цель этого теста - убедиться, что функция addContact работает правильно и добавляет новый контакт в список контактов. Это важно для обеспечения корректной работы основного функционала приложения.
