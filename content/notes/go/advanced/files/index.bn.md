---
title: Manipulacion de Documentos
weight: 40
menu:
  notes:
    name: Manipulacion de Documentos 
    identifier: notes-go-advanced-files
    parent: notes-go-advanced
    weight: 10
---

<!-- Condition -->
{{< note title="Condition">}}

```go
if day == "sunday" || day == "saturday" {
  rest()
} else if day == "monday" && isTired() {
  groan()
} else {
  work()
}
```

```go
if _, err := doThing(); err != nil {
  fmt.Println("Uh oh")
```

{{< /note >}}