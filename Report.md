# Отчёт о тестировании функциональности валидации номера банковской карты

## Краткое описание

06.03.2021 - 06.03.2021 было проведено модульльное тестирование функциональности валидации номеров банковских карт.

На тестирование затрачено: 1.5 ч

В результате тестирования выявлены следующие дефекты:
 1. Номера карт с количеством цифр в номере отличным от 16 определяются программой как некорректные.
 * Diners Club - Carte Blanche - https://github.com/it-is-nice/Java-1.2/issues/2
 * Discover с длинной номера 19 цифр - https://github.com/it-is-nice/Java-1.2/issues/3
 * JCB с длинной номера 19 цифр - https://github.com/it-is-nice/Java-1.2/issues/4
 * Diners Club - International - https://github.com/it-is-nice/Java-1.2/issues/5

 2. Карты American Express имеют 16 цифр в номере, но также определяются как некорректные.
 * American Express- https://github.com/it-is-nice/Java-1.2/issues/1



## Описание процесса тестирования

В процессе тестирования использовались следующие артефакты:



В качестве тестовых данных использовались данные:
* Руководство по установке IntelliJ IDEA  
* Программа IntelliJ IDEA
* Программный код представленный на данной странице (https://github.com/netology-code/javaqa-homeworks/tree/master/intro)
* Онлайн генератор кредитных карт (https://www.freeformatter.com/credit-card-number-generator-validator.html)


Тестирование производилось в следующем окружении:
* Windows 10 и 64 версия 1909>
* версия Java "11.0.10"
* Программа IntelliJ IDEA 2020.3.2 (Community edition)


