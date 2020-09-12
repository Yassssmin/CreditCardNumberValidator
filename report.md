# Отчёт о тестировании Credit Card Number Validator

## Небольшое приложение написанно на языке java, которое проверяет номера бабновских карт на валидность.

12.09.2020 - 12.09.2020 было проведено <тестирование документации, тестирование установки, тестирование совместимости> приложения <Credit Card Number Validator>.

На тестирование затрачено: 3 часа

В результате тестирования выявлены следующие дефекты:
* <https://github.com/Yassssmin/CreditCardNumberValidator/issues/1>
* <https://github.com/Yassssmin/CreditCardNumberValidator/issues/4>
* <https://github.com/Yassssmin/CreditCardNumberValidator/issues/2>

## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты*:
* Баг-репорт

В качестве тестовых данных использовались данные:
<https://www.freeformatter.com/credit-card-number-generator-validator.html> 
<https://cartoved.ru/common/generator-kreditnyh-kart.html>

* **Номер:** 4929620110029696

  **ОР:**    
  ```
    Result is OK

    Process finished with exit code 0
  ```

* **Номер:** 4929373022438098

  **ОР:**    
  ```
    Result is OK

    Process finished with exit code 0
  ```
* **Номер:** 6011272813691341

  **ОР:**    
  ```
    Result is OK

    Process finished with exit code 0
  ```
* **Номер:** 6011277809354408

  **ОР:**    
  ```
    Result is OK

    Process finished with exit code 0
  ```
* **Номер:** 4485175836887725781

  **ОР:**    
  ```
    Result is OK

    Process finished with exit code 0
  ```
* **Номер:** 6011595896946209692

  **ОР:**    
  ```
    Result is OK

    Process finished with exit code 0
  ```
* **Номер:** 30112434075757

  **ОР:**    
  ```
    Result is OK

    Process finished with exit code 0
  ```
* **Номер:** 4508914158614116

  **ОР:**    
  ```
    Result is OK

    Process finished with exit code 0
  ```
* **Номер:** 5471638345185009

  **ОР:**    
  ```
    Result is OK

    Process finished with exit code 0
  ```
* **Номер:** 6378365017914845

  **ОР:**    
  ```
    Result is OK

    Process finished with exit code 0
  ```
* **Номер:** 344755614042855

  **ОР:**    
  ```
    Result is OK

    Process finished with exit code 0
  ```
* **Номер:** 5479305684963980

  **ОР:**    
  ```
    Result is OK

    Process finished with exit code 0
  ```
* **Номер:** 6763053947399476

  **ОР:**    
  ```
    Result is OK

    Process finished with exit code 0
  ```
* **Номер:** 5005 9156 3847 8357

  **ОР:**    
  ```
    Result is FAIL

    Process finished with exit code 0
  ```
* **Номер:** 5520 7170 8787 8855

  **ОР:**    
  ```
    Result is FAIL

    Process finished with exit code 0
  ```
* **Номер:** 0000000000000000

  **ОР:**    
  ```
    Result is FAIL

    Process finished with exit code 0
  ```
* **Номер:** RFGHVFDCGHJYFGVB

  **ОР:**    
  ```
    Result is FAIL

    Process finished with exit code 0
  ```
* **Номер:** 5520-7156-4429-2602

  **ОР:**    
  ```
    Result is OK

    Process finished with exit code 0
  ```

Тестирование производилось в следующем окружении:
* IntelliJ IDEA 2020.2.1 (Community Edition)
* Build #IC-202.6948.69, built on August 25, 2020
* Runtime version: 11.0.8+10-b944.31 x86_64
* VM: OpenJDK 64-Bit Server VM by JetBrains s.r.o.
* macOS 10.15.5
* GC: ParNew, ConcurrentMarkSweep
* Memory: 725M
* Cores: 4
