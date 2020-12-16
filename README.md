# Отчёт о тестировании OpenJDK 11 
## Краткое описание
06.11.2020 - 06.11.2020 было проведено *установочное тестрование*  и *функциональное* тестирование приложения OpenJDK11.

На тестирование затрачено: 3 часа

В результате тестирования выявлены следующие дефекты: 

* Валидация ключей не соответствует [руководству использования KeyValidator ](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/user-manual.md)


## Описание процесса тестирования

### Предисловие : 

* [Инструкция по установке OpenJDK11](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/openjdk11-manual.md)

* [Руководство использования KeyValidator ](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/user-manual.md)

### Шаги : 
1. Проходим по всем этапам установки OpenJDK11 (ссылка на инструкцию в предисловии)
1. После установки проверяем совместимость. Открываем терминал, вводим java -version 
1. Проверяем приложение KeyValidator согласно руководству (ссылка на инструкцию в предисловии)




### Ожидаемый результат :
* Инструкция по установке OpenJDK11 работает под вашу ОС
* Приложение запускается и совместимо с Java 11
* Приложение KeyValidator работает согласно руководству использования

### Фактический результат
* OpenJDK11 работает на Windows 10 64-bit

* Приложение запускается и совместимо с Java 11

* Приложение KeyValidator работает согласно руководству использования
* [Валидация ключей не соответствует руководству искользования](https://github.com/Cook1eM/-OpenJDK-11/issues/2)



## Тестирование производилось в следующем окружении:

Windows 10 64-bit

openjdk version "11.0.9.1" 2020-11-04

OpenJDK Runtime Environment AdoptOpenJDK (build 11.0.9.1+1)

OpenJDK 64-Bit Server VM AdoptOpenJDK (build 11.0.9.1+1, mixed mode)
