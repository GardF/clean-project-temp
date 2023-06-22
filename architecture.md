## Simple flow chart 

```mermaid
  graph LR;
      A-->B;
      A-->C;
      B-->D;
      C-->D;
```


## Simple Sequence diagram 

```mermaid
sequenceDiagram
    box Alice & John
    participant A
    participant J
    end
    box Another Group
    participant B
    participant C
    end
    A->>J: Hello John, how are you?
    J->>A: Great!
    A->>B: Hello Bob, how is Charly ?
    B->>C: Hello Charly, how are you?
```
