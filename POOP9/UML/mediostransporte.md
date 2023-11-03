@startuml
scale 3

abstract class MediosTransporte{

}

class TransporteAuatico{
    -velocidad: int
    -capacidad: String
    +aumentarVelocidad():void
}

class Barco{
    -puertoOrigen: String
    -puertoDestino: String
    +abordadPasajeros():void
}

MediosTransporte <|-- TransporteAuatico
TransporteAuatico <|-- Barco: interfaz
@enduml 

@startuml
scale 3

abstract class InstrumentoMusical{

}

class InstrumentoViento{
    +tocar():void
    +afinar() :void
    +tipoInstrumento() :String
}

class Flauta{
    +tipoInstrumento() :String
}

InstrumentoMusical <|-- InstrumentoViento
InstrumentoViento <|-- Flauta: interfaz
@enduml