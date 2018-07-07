# projecteuler.net
My progress in learning data science problem solving, work my way through 600+ problems

I'm working to get the build, coverage and chat status icons running soon.
Needless to say there is a lot to learn to get this working the right way.

[![Build Status](https://travis-ci.org/knsv/mermaid.svg?branch=master)](https://travis-ci.org/knsv/mermaid)
[![Coverage Status](https://coveralls.io/repos/github/knsv/mermaid/badge.svg?branch=master)](https://coveralls.io/github/knsv/mermaid?branch=master)
[![Join the chat at https://gitter.im/knsv/mermaid](https://badges.gitter.im/Join%20Chat.svg)](https://gitter.im/knsv/mermaid?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)

![banner](./img/header.png)

Generation of diagrams and flowcharts from text in a similar manner as markdown.

Ever wanted to simplify documentation and avoid heavy tools like Visio when explaining your code?

This is why mermaid was born, a simple markdown-like script language for generating charts from text via javascript.


### Flowchart

```
graph TD;
    A-->B;
    A-->C;
    B-->D;
    C-->D;
```
![Flowchart](./img/flow.png)


### Sequence diagram

```
sequenceDiagram
    participant Alice
    participant Bob
    Alice->>John: Hello John, how are you?
    loop Healthcheck
        John->>John: Fight against hypochondria
    end
    Note right of John: Rational thoughts <br/>prevail...
    John-->>Alice: Great!
    John->>Bob: How about you?
    Bob-->>John: Jolly good!
```
![Sequence diagram](./img/sequence.png)
