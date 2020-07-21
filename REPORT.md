Отчёт о тестировании OpenJDK11
Краткое описание
19.07.2020> - <20.07.2020> было проведено documentary testing, compatibility testing, installation testing приложения OPENJDK11.

На тестирование затрачено: 24 часа.

В результате тестирования выявлены следующие дефекты:

https://github.com/OlegSkrill/j-1.1/issues/1
https://github.com/OlegSkrill/j-1.1/issues/2
https://github.com/OlegSkrill/j-1.1/issues/3

Описание процесса тестирования
В процессе тестирования использовались следующие артефакты*:
Checklist
Bug Reports

В качестве тестовых данных использовались данные из руководства использования KeyValidator

Valid keys:
8f05e6a7-70e9-33d7-bfe7-b19eae0d8998 - OK
80b427f8-92cd-3aae-ba04-3927fbe17c6 - OK
b295bc63-9f03-3b4b-af80-969b39f8c262 - OK
387eedc6-12e9-3b32-9881-63b6b5e85317 - OK
c19a8cf9-5c3a-37c5-b7f3-d16d38a0c180 - OK

Invalid keys:
18252235-78e0-44a5-8720-556f0c7da17a - Fail
e66075b6-ddad-445e-baf6-161b3289522b - Fail
b6d53250-f07e-4352-a293-6102ddf7f1ca - Fail
c2bc778a-1cb9-46c6-b435-0489649d2a42 - Fail
2fb98b44-93e7-3bdd-a2ad-79347bfe4ad1 - Fail

Тестирование производилось в следующем окружении:

Windows 7 x64, Java 11.0.5, gitbash for windows, KeyValidator.class.
