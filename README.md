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
1. Проверяем валидацию ключей из руководства

### В качестве тестовых данных использовалось  [Руководство использования KeyValidator ](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/user-manual.md)

#### Валидные ключи:
* 00000000-0000-0000-0000-000000000000 
* 8f05e6a7-70e9-33d7-bfe7-b19eae0d8998 
* 80b427f8-92cd-3aae-ba04-3927fbe17c6 
* b295bc63-9f03-3b4b-af80-969b39f8c262 
* 387eedc6-12e9-3b32-9881-63b6b5e85317 
* c19a8cf9-5c3a-37c5-b7f3-d16d38a0c180 
#### Не валидные ключи:
* 00000000-0000-0000-0000-000000000001 
* 18252235-78e0-44a5-8720-556f0c7da17a 
* e66075b6-ddad-445e-baf6-161b3289522b 
* b6d53250-f07e-4352-a293-6102ddf7f1ca 
* c2bc778a-1cb9-46c6-b435-0489649d2a42 
* 2fb98b44-93e7-3bdd-a2ad-79347bfe4ad1 


### Ожидаемый результат :
* Инструкция по установке OpenJDK11 работает под вашу ОС
* Приложение запускается и совместимо с Java 11
* Приложение KeyValidator работает согласно руководству использования

### Фактический результат
* OpenJDK11 работает на Windows 10 64-bit
![Image alt](https://github.com/Cook1eM/screenshots/raw/main/win-step6.png)
* Приложение запускается и совместимо с Java 11
![Image alt](https://github.com/Cook1eM/screenshots/raw/main/win-step7.png)
* Приложение KeyValidator работает согласно руководству использования
* [Валидация ключей не соответствует руководству искользования](https://github.com/Cook1eM/-OpenJDK-11/issues/2)



## Тестирование производилось в следующем окружении:

Windows 10 64-bit

openjdk version "11.0.9.1" 2020-11-04

OpenJDK Runtime Environment AdoptOpenJDK (build 11.0.9.1+1)

OpenJDK 64-Bit Server VM AdoptOpenJDK (build 11.0.9.1+1, mixed mode)
