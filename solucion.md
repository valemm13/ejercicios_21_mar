``` mermaid
classDiagram

class Habitacion{
- int numero
- string tipo
- bool ocupada
+ Habitacion(int,string)
~ Habitacion
+ getNumero() int
+ getTipo() string
+ estaOcupada() bool
+ ocupar() void
+ desocupar()  void
}

class Cliente {
- int id
- string nombre
+Cliente(int,string)
}

class Hotel {
-string nombre
+Hotel (string)
}

Hotel *-- Habitacion
Hotel o-- Cliente
```
