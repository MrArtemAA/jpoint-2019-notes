# Lost in transaction? Strategies to manage consistency in distributed systems
#### by Bernd Rücker (Camunda)

## [Аннотация](https://jpoint.ru/talks/3s5nqebrevpregacfijhra/)
You probably work on a distributed system. Even if you don't yet face a serverless microservice architecture using fancy NoSQL databases, you might simply call some remote services via REST or SOAP. This leaves you in charge of dealing with consistency yourself. ACID transactions are only available locally within components, and protocols like two-phase commit don't scale. Many projects either risk adventurous inconsistencies or write a lot of code for consistency management in the application layer.

In this talk Bernd discusses these problems and goes over possible solutions, including the Saga Pattern. He will discuss recipes and frameworks that ease the management of the right level of consistency. This allows you to write business logic code. Expect fun little live hacking sessions with open source components, but also real-life stories.

## Ключевые мысли доклада

## Собственные мысли, выводы
