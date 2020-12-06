# Отчёт о тестировании OpenJDK 11
## Краткое описание
03.11.2020 - 03.11.2020 было проведено *функциональное* тестирование установки приложения OpenJDK11.

На тестирование затрачено: 1 час

Задачи тестирования

* Нужно протестировать документацию
* Нужно протестировать установку
* Нужно протестировать совместимость


В результате тестирования выявлены следующие дефекты:



## Описание процесса тестирования

Шаги : 
1.Перейдите на сайт adoptopenjdk.net.
![Image alt](https://github.com/Cook1eM/screenshots/raw/main/win-adoptopenjdk.png
1.Выберите опции как на скриншоте ниже и нажмите на кнопку скачивания:
![Image alt](https://github.com/Cook1eM/screenshots/raw/main/win-step1.png
1.Запустите на установку скачанный MSI-файл и нажмите кнопку "Next":
![Image alt](https://github.com/Cook1eM/screenshots/raw/main/win-step2.png
1. Прочитайте и согласитесь с условиями лицензии:
![Image alt](https://github.com/Cook1eM/screenshots/raw/main/win-step3.png
1. Выберите опции как на экране (удостоверьтесь, что установка происходит в Program Files и опция Add to PATH выбрана):
![Image alt](https://github.com/Cook1eM/screenshots/raw/main/win-step4.png
1. Нажмите на кнопку "Install":
![Image alt](https://github.com/Cook1eM/screenshots/raw/main/win-step5.png
1. Дождитесь окончания установки и нажмите на кнопку "Finish":

1.
1.
1. 

### Ключи для проверки


Валидные ключи:

* 8f05e6a7-70e9-33d7-bfe7-b19eae0d8998
* 80b427f8-92cd-3aae-ba04-3927fbe17c6
* b295bc63-9f03-3b4b-af80-969b39f8c262
* 387eedc6-12e9-3b32-9881-63b6b5e85317
* c19a8cf9-5c3a-37c5-b7f3-d16d38a0c180

Невалидные ключи:

* 18252235-78e0-44a5-8720-556f0c7da17a
* e66075b6-ddad-445e-baf6-161b3289522b
* b6d53250-f07e-4352-a293-6102ddf7f1ca
* c2bc778a-1cb9-46c6-b435-0489649d2a42
* 2fb98b44-93e7-3bdd-a2ad-79347bfe4ad1

## Тестирование производилось в следующем окружении:

Windows 10 

openjdk version "11.0.9.1" 2020-11-04

OpenJDK Runtime Environment AdoptOpenJDK (build 11.0.9.1+1)

OpenJDK 64-Bit Server VM AdoptOpenJDK (build 11.0.9.1+1, mixed mode)
