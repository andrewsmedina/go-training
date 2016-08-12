# Primeiro programa em Go

```
// primeiro.go
package main

import "fmt"

func main() {
    fmt.Println("Ola mundo")
}
```

Executando o `primeiro.go`:

```
$ go run primeiro.go
Ola mundo
```

Compilando o `primeiro.go`:

```
$ go build -o primeiro
./primeiro
```
