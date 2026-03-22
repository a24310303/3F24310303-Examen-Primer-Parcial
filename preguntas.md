Preguntas de reflexión para el examen:

    ¿Qué tipo de relación existe entre "Vehículo" y "Camioneta"? ¿Es herencia, agregación o asociación?
    Es herencia porque una camioneta es un tipo de vehículo.

    ¿Cómo se representa la restricción de que un cliente solo puede alquilar un máximo de tres vehículos?
    Se representa con la multiplicidad 0..3 en la relación entre Cliente y Vehiculo indicando que un cliente puede alquilar de cero a tres vehículos.
    Cliente "1" o-- "0..3" Vehiculo

    ¿Qué modificadores de acceso serían adecuados para los atributos de cada clase?
    Los atributos de cada clase deberían ser privados (-) para que nadie los cambie directamente desde fuera de la clase.