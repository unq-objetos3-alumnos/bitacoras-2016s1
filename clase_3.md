# Clase 30/03/2016

## Qué vimos

 - Durante la primer mitad de la clase hicimos corrección del primer trabajo de diseño utilizando mixins.
 - Vimos brevemente mixins en Scala.
 - Vimos cómo en un lenguaje con tipado explícito era necesario explicitar los requerimientos del mixin.
 - Por ejemplo:
 ```scala
    class Guerrero extends Atacante {
      def potencialOfensivo() = 40
      
      def recibirDaño(cantidad:Int){
          //...
      }
    }
    
    trait Atacante {
      // El Atacante requiere que quien lo incorpore tenga definido el mensaje potencialOfensivo
      this:{ def potencialOfensivo():Int} =>
      
      def atacar(otro:Guerrero){
        otro.recibirDaño(this.potencialOfensivo())
      }
    }
    
  ```


- Explicamos brevemente traits y su álgebra para resolución explícita.
- En scala llaman a los mixins `trait`, **pero son mixins!**. No confundir!
- La diferencia: Los traits tienen un álgebra para resolución explícita, los mixins tienen resolución implícita mediante linearización
- Mostramos una posible implementación de traits en Ruby
