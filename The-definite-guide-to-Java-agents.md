# The definite guide to Java agents
#### by Rafael Winterhalter (Scienta AS)

## [Аннотация](https://jpoint.ru/talks/79c6yjo0q4q4esyosgeyoo/)
#### Комментарий Программного комитета:
> Расстановка точек над i от автора ByteBuddy — популярной и очень удобной библиотеки для кодогенерации. Будет полезно и тем, кто ни разу не писал Java-агенты, и тем, кто уже замарал руки.

Java agents and their instrumentation API offer developers the most powerful toolset to interact with a Java application. Using this API, it becomes possible to alter the code of running applications, for example, to add monitoring or to inject security checks as it is done by many enterprise products for the Java ecosystem.

In this session, developers will, however, learn how to program agents using Byte Buddy, a high level code generation library that does not require any knowledge of Java bytecode. Doing so, developers will see how Java classes can be used as templates for implementing highly performant code changes that avoid the boilerplate of alternative solutions such as AspectJ or Javassist while still performing better than agents implemented in low-level libraries such as ASM.

## Ключевые мысли доклада
* стратовая точка любого java-приложения - метода main
* но существует еще premain как раз для java. Они образуют цепочку 
* 3 типа java-агентов: (1) работают перед запуском в рамках jvm с приложением, (2) во время (?), и (3) в отдельном jvm-процессе и могут подключатся к одному или нескольким другим jvm-процессам
* есть ограничения на типы модификаций байт-кода для типа (3)

## Собственные мысли, выводы
