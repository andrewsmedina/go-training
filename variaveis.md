# Variáveis

Em Go variáveis são declaradas explicitamente usando a `keyword` `var`:

```
package main

import "fmt"

func main() {
  var x int = 3
  var y int = 10
  fmt.Println(x + y)
}
```

É possível declarar várias variáveis de uma vez.


```
package main

import "fmt"

func main() {
  var x, y int = 3, 10
  x = 3
  y = 10
  fmt.Println(x + y)
}
```

Variáveis declaradas sem um valor inicial são inicializadas com `zero-value`.

```
package main

import "fmt"

func main() {
  var x int
  fmt.Println(x)
}
```

O `:=` é um atalho para declarar e inicializar uma variavel.

```
package main

import "fmt"

func main() {
  // var x int = 3
  x := 3
  y := 9
  fmt.Println(x + y)
}
```
