# Constantes

Constantes em Go são criadas em tempo de compilação e só podem serem "numbers",
"runes (caracteres)", "strings" ou "booleans".

```
package main

import "fmt"

const x int = 10

func main() {
  fmt.Println(x)
}
```

É possível criar constantes "enumerated" com o identificador pré definido "iota".

```
package main

import "fmt"

const (
  Sunday = iota
  Monday
  Tuesday
  Wednesday
  Thursday
  Friday
)

func main() {
  fmt.Println(Sunday)
  fmt.Println(Monday)
  fmt.Println(Tuesday)
  fmt.Println(Wednesday)
  fmt.Println(Thursday)
  fmt.Println(Friday)
}
```
