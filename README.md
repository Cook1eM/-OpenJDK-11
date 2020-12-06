# Отчёт о тестировании OpenJDK 11 на Win 10
## Краткое описание
06.11.2020 - 06.11.2020 было проведено *функциональное* тестирование приложения OpenJDK11.

На тестирование затрачено: 3 часа

Задачи тестирования

* Нужно протестировать документацию
* Нужно протестировать установку
* Нужно протестировать совместимость






## Описание процесса тестирования

### Ожидаемый результат :
* Инструкция по установке OpenJDK11 работает под вашу ОС
* Приложение запускается и совместимо с Java 11
* Приложение работает согласно руководству использования

### Докумантация : 

* [Инструкция по установке OpenJDK11](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/openjdk11-manual.md)

* [Руководство использования KeyValidator ](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/user-manual.md)

### Шаги : 
1.Перейдите на сайт adoptopenjdk.net


2.Выберите опции как на скриншоте ниже и нажмите на кнопку скачивания:

![Image alt](https://github.com/Cook1eM/screenshots/raw/main/win-adoptopenjdk.png)

3.Запустите на установку скачанный MSI-файл и нажмите кнопку "Next":

![Image alt](https://github.com/Cook1eM/screenshots/raw/main/win-step1.png)

4. Прочитайте и согласитесь с условиями лицензии:

![Image alt](https://github.com/Cook1eM/screenshots/raw/main/win-step2.png)

5. Выберите опции как на экране (удостоверьтесь, что установка происходит в Program Files и опция Add to PATH выбрана):

![Image alt](https://github.com/Cook1eM/screenshots/raw/main/win-step3.png)

6. Нажмите на кнопку "Install":

![Image alt](https://github.com/Cook1eM/screenshots/raw/main/win-step4.png)


7. Дождитесь окончания установки и нажмите на кнопку "Finish":

![Image alt](https://github.com/Cook1eM/screenshots/raw/main/win-step5.png)

8. Отройте командную строку введите: java -version

![Image alt](https://github.com/Cook1eM/screenshots/raw/main/win-step6.png)

9. Скачайте приложение [KeyValidator.class](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/artifacts/KeyValidator.class)

10. Проверить ключи по [руководству использования KeyValidator ](https://github.com/netology-code/javaqa-homeworks/blob/master/intro/user-manual.md)
![Image alt](https://github.com/Cook1eM/screenshots/raw/main/win-step7.png)

### Фактический результат
* OpenJDK11 работает на Windows 10 64-bit
![Image alt](https://github.com/Cook1eM/screenshots/raw/main/win-step6.png)
* Приложение запускается и совместимо с Java 11
![Image alt](https://github.com/Cook1eM/screenshots/raw/main/win-step7.png)
* Приложение работает согласно руководству использования


## Тестирование производилось в следующем окружении:

Windows 10 64-bit

openjdk version "11.0.9.1" 2020-11-04

OpenJDK Runtime Environment AdoptOpenJDK (build 11.0.9.1+1)

OpenJDK 64-Bit Server VM AdoptOpenJDK (build 11.0.9.1+1, mixed mode)
