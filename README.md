# Sustituci-n-de-Liskov
En la estructura de productos la clase base Producto define las funciones que todos los productos comparten.
Las subclases Fisico y Digital respetan ese contrato sin alterar la logica esperada.

Cualquier funcion del programa que reciba un objeto de tipo Producto puede recibir un Fisico o un Digital y va a funcionar exactamente bien, sin necesidad de hacer comprobaciones raras ni parches en el codigo.
