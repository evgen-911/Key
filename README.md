# Отчёт о тестировании KeyValidator

## Краткое описание

Начало тестирования 22.11.2020 - 22.11.2020 

Было проведено функциональное тестирование приложения KeyValidator на разпознавание валидных и невалидных ключей 

На тестирование затрачено: 2 часа

В результате тестирования выявлены следующие дефекты:

[Нет результата "FAIL" в результате ввода невалидного ключа](https://github.com/evgen-911/Key/issues/2#issue-748317344)

[Нет ответа "ОК" в результате ввода валидного ключа](https://github.com/evgen-911/Key/issues/1#issue-748272373)

## Описание процесса тестирования

В качестве тестовых данных использовались ключи

Валидные ключи:

- 8f05e6a7-70e9-33d7-bfe7-b19eae0d8998
- 80b427f8-92cd-3aae-ba04-3927fbe17c6
- b295bc63-9f03-3b4b-af80-969b39f8c262
- 387eedc6-12e9-3b32-9881-63b6b5e85317
- c19a8cf9-5c3a-37c5-b7f3-d16d38a0c180

Невалидные ключи:

- 18252235-78e0-44a5-8720-556f0c7da17a
- e66075b6-ddad-445e-baf6-161b3289522b
- b6d53250-f07e-4352-a293-6102ddf7f1ca
- c2bc778a-1cb9-46c6-b435-0489649d2a42
- 2fb98b44-93e7-3bdd-a2ad-79347bfe4ad1

Ключи поочередно вводились в консоль

Тестирование производилось в следующем окружении:

- Windows 10 Pro x64
- java version "11.0.9" 2020-10-20 LTS
- Google Crome Версия 86.0.4240.198 (Официальная сборка), (64 бит),
- Git Bash
