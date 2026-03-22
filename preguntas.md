    ¿Qué tipo de relación existe entre "Vehículo" y "Camioneta"? ¿Es herencia, agregación o asociación?
        La relación entre Vehículo y Camioneta es de herencia, porque Camioneta es un tipo de Vehículo, o sea hereda sus características
    ¿Cómo se representa la restricción de que un cliente solo puede alquilar un máximo de tres vehículos?
        La restricción de máximo tres vehículos se representa con la multiplicidad, por ejemplo poniendo 1..3 en la relación entre Alquiler y Vehiculo
    ¿Qué modificadores de acceso serían adecuados para los atributos de cada clase?
        Los atributos deberían ser privados, usando el modificador -, para proteger los datos y que no se puedan modificar directamente desde fuera de la clase