# TC1033-Test
# Leonardo Corona Garza (A00832792)
## Test de repo para la materia de TC1033, grupo 2.

**Texto en bold**

_Texto en itálica_

1. Fundamentos de GitHub
2. Método de calcular las frecuencias
3. Descargar los nuevos archivos de Serie y Episodio

- Lista sin orden
- Bullets con guiones

````cpp
//
// Created by Leonardo Corona Garza on 29/Nov/21.
// Matrícula: A00832792
//

#ifndef TC1033_FECHA_H
#define TC1033_FECHA_H

#include <string>


class Fecha {
private:
    int dia;
    int mes;
public:
    Fecha();
    Fecha(int dia, int mes);

    int getDia() const;
    void setDia(int _dia);

    int getMes() const;
    void setMes(int _mes);

    std::string str() const;
};


#endif //TC1033_FECHA_H
````

Línea horizontal
---

[Link aquí](https://www.jetbrains.com/clion/)
![Logo de CLion](https://resources.jetbrains.com/storage/products/clion/img/meta/clion_logo_300x300.png)

---

Editar el README desde mi branch.
