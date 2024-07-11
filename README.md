# U2-T11: Complemento Flutter

Portafolio de evidencias para la clase Desarrollo de Dispositivos Inteligentes

## Ejercicios del 01 al 04

### **01.Hello World**

- Código

  ```dart
  void main() {
  print("Hello Word");
  }
  ```

- Captura
  ![Captura Hello World](imagenes/Imagen1.png)

### **02.Variables**

- Código

  ```dart
  int counter;
  String name;
  double note;
  bool isAdult;
  ```

- Captura
  ![Captura Hello World](imagenes/Imagen2.png)

### **03.Maps**

- Código

  ```dart
  // Crear un maps
  Map<String, int> verduras = {
   'Cilantro': 1,
   'Zanahoria': 3,
   'Apio': 5,
   'Coliflor': 2
  };
  print(verduras);
  ```

- Captura

  ![Captura Hello World](imagenes/Imagen3.png)

### **04.List, maps and Iterables**

- Código

  ```dart
   var numeros = [1, 3, 6, 8, 7];

   for (var i in numeros) {
    print(i);
   }

   numeros.forEach((i) {
    print(i);
   });

   Map<String, int> verduras = {
    'Cilantro': 1,
    'Zanahoria': 3,
    'Apio': 5,
    'Coliflor': 2
   };

   for (var verdura in verduras.entries) {
    print("${verdura.key} : ${verdura.value}");
   }
  ```

- Captura

  ![Captura Hello World](imagenes/Imagen3.png)
  ![Captura Hello World](imagenes/Imagen4.png)

## Ejercicios del 05 al 08

### **05.Functions**

- Código

  ```dart
  var suma = (int a, int b) {
   return a + b;
  };
  ```

- Captura
  ![Captura Hello World](imagenes/Imagen5.png)

### **06.Classes**

- Código

  ```dart
  class Vehiculo {
   String marca;
   int year;

   Vehiculo(this.marca, this.year);

   void mostrarDetalles() {}
   }
  ```

- Captura

### **07.Constructors and names**

- Código
- Captura

### **08.get and set**

- Código
- Captura

## Ejercicios del 09 al 15

### **09.Abstract class**

- Código
- Captura

### **10.Mixins**

- Código
- Captura

### **11.Futures**

- Código
- Captura

### **12.Async Await**

- Código
- Captura

### **13.Try catch finally**

- Código
- Captura

### **14.Streams**

- Código
- Captura

### **15.Stream await**

- Código
- Captura

## Aplicación HelloWorld

- Código
- Captura

## Aplicación YesOrNo

- Código
- Captura
