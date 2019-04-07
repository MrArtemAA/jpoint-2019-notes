# Decomposing Java applications
#### by Milen Dyankov (Liferay)

## [Аннотация](https://jpoint.ru/talks/6fhvshh187ayscc7ahpeju/)
#### Комментарий Программного комитета:
> Хороший архитектурный доклад, посвященный модульности и способам ее внедрения в конкретных случаях. У Милена в этой области большой опыт.

Most Java developers happily use libraries in their applications. Many developers split their own code into what they call modules hoping that brings benefits. Yet way too often they end up having a (distributed?) big ball of mud sooner or later? This session aim to answer the question: why simply cutting things down into smaller pieces and calling them libraries, modules, microservices, ... does not work?

In this talk we'll go one abstraction level above and look at the process of decomposing a Java application into reusable components. We'll examine different ways to organize Java code in methods, classes, packages and modules. We'll talk about APIs, SPIs, hiding implementation details and enforcing module boundaries. Some of you will be surprised how well SOLID principles fits into the picture. But most important of all, we'll end up with application design that has good chance to evolve over the years without introducing additional accidental complexity.

## Ключевые мысли доклада
https://github.com/azzazzel/DecomposingJavaApplications
* Что если инвертировать закон Конвея
* Проблематика
  * не смотря на все наши красивые архитектурные схемы, пока сам код будет позволять делать запрещенные ходы, они буду делаться
* важно не просто сказать, что в коде должен быть порядок, а объяснить, что это значит и чем полезно

## Собственные мысли, выводы
* хороший кодовый пример следования принципам clean architecture
* определение домена
* опрежеление процессов в виде интерфейсов
* определение вариантов использования
* сокрытие тех моментов, которые не должны быть доступны во внешних модулях
* использование модулей java 9 и соответственно переход на java 9/11
