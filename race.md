# Data Races

Data race é quando duas ou mais goroutines tentam escrever ou ler o mesmo
recurso no mesmo tempo. Isso faz com que a aplicação se comporte de maneira inesperada.

* Funções atomicas e mutexes são formas de sincronizar acesso.
* `-race` flag
