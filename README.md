# hello-world
Repository for "Hello World" Guide

This account was created for "Java Web" course.

This line was created on github.

Another line created on github.

```mermaid
classDiagram
    class ICorExec
    <<interface>> ICorExec
    ICorExec : exec(context)
    
    class AbstractCorExec
    <<abstract>> AbstractCorExec
    
    class CorWorker
    class CorChain
    
    ICorExec <|-- AbstractCorExec
    AbstractCorExec <|.. CorWorker
    note for CorWorker "Одинарный обработчик"
    AbstractCorExec <|.. CorChain
    note for CorChain "Цепочка обработчиков, в т.ч. и вложенных chain"
```
