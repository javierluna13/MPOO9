@startuml
class Animal{
    +nombre: String
    +lugarOrigen: String
    +color: String

    +sonido()
    +comer()
}

class Acuatico{
    +numeroAletas: int

    +nadar()
    +comer()
}

Animal <|-- Acuatico

class Terrestre{
    +numeroPatas: int

    +correr()
    +comer()
}

Animal <|-- Terrestre

class Aereo{
    +numeroAlas: int

    +colar()
    +comer()
}

Animal <|-- Aereo

class ballena{
    +largo:int

    +pelearConPinocho()
}

Acuatico <|-- ballena

class perro{
    +colorCollar: String

    +hacerTruco()
}

Terrestre <|-- perro

class pajaro{
    +tipoPico: String

    +recolectarRamas()
}

Aereo <|-- pajaro

@enduml