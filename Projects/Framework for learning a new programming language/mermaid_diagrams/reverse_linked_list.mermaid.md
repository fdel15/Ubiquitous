`Curr` = 1
`Prev` = Null
`Next` = 2

```mermaid

graph LR

A[1]

B[2]

C[3]

D[4]

E[5]

A --> B --> C --> D --> E

```
---

`Curr` = 2
`Prev` = 1
`Next` = 3

```mermaid

graph LR

A[1]

B[2]

C[3]

D[4]

E[5]

B --> A

C --> D --> E

```
---
`Curr` = 3
`Prev` = 2
`Next` = 4

```mermaid

graph LR

A[1]

B[2]

C[3]

D[4]

E[5]

C --> B --> A

D --> E

```
---
`Curr` = 4
`Prev` = 3
`Next` = 5

```mermaid

graph LR

A[1]

B[2]

C[3]

D[4]

E[5]

D --> C --> B --> A

E

```
---
`Curr` = 5
`Prev` = 4
`Next` = Null

```mermaid

graph LR

A[1]

B[2]

C[3]

D[4]

E[5]

  

E --> D --> C --> B --> A

```
---
`Curr` = Null
`Prev` = 5
`Next` = Null
