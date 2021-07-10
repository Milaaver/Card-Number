# Отчёт о тестировании <Credit Card Number Validator>

## Краткое описание

<10.07.2021> - <10.07.2021> было проведено функциональное тестирование приложения <Credit Card Number Validator>.

На тестирование затрачено: <1 час>

В результате тестирования выявлены следующие дефекты:
* https://github.com/Milaaver/Card-Number/issues


## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты*:
* <баг-репорт>
* <отчет о тестировании>

*Примечание\*: не указывайте артефакты "для галочки". Если вы сюда напишите **тест-план**, то мы попросим вас его показать (а если не покажете - то отправим работу на доработку). Пишите только то, что реально существует и требуется в задании.*

В качестве тестовых данных использовались данные <https://fakepersongenerator.com/credit-card-generator>:
* <4504938705130940 (visa) Result is OK>
* <4507512237046408 (visa) Result is OK>
* <4004551106360340 (visa) Result is OK>
* <4115635888492912 (visa) Result is OK>
* <4934313179960430 (visa) Result is OK>
* <4934313179960430 (Mastercard) Result is OK>
* <5463501895922462 (Mastercard) Result is OK>
* <5492398834620900 (Mastercard) Result is OK>
* <5309259352714033 (Mastercard) Result is OK>
* <5587610800133908 (Mastercard) Result is OK>
* <5587610800133908 (Discover) Result is OK>
* <6543845718170391 (Discover) Result is OK>
* <6011891504281607 (Discover) Result is OK>
* <6482004095796583 (Discover) Result is OK>
* <6544612862589522 (Discover) Result is OK>
* <378210532311429 (Amex) Result is OK>
* <379274577779741 (Amex) Result is OK>
* <376090705143334 (Amex) Result is OK>
* <376782339602186 (Amex) Result is OK>
* <379269872255371 (Amex) Result is OK>



Тестирование производилось в следующем окружении:
* <Windows 10 Домашняя
Версия ОС:                        10.0.19042 Н/Д построение 19042
Изготовитель ОС:                  Microsoft Corporation>
* <IntelliJ IDEA 2021.1.3 (Community Edition)
Build #IC-211.7628.21, built on June 30, 2021
Runtime version: 11.0.11+9-b1341.60 amd64
VM: OpenJDK 64-Bit Server VM by JetBrains s.r.o.

