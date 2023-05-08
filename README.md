# Diagrama de clases

El siguiente diagrame reprenta la esctructura de clases de la aplicacion

``` java
class Perro extends Animal{
   String raza;
   
   String morder(String cosa){
     return null
  }
} 

abstract class Animal{
  void alimentar(){

  }
  abstract void sonar();
}
```
```mermaid
classDiagram
class Animal
<<abstract>> Animal
Animal <|-- Perro
Animal: +alimentar()
Animal: +sonar()*
class Perro{
  +Strng raza
  +morder(cosa:String):String
 }
```
