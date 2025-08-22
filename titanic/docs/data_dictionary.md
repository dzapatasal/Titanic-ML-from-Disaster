# 📘 Diccionario de Datos

| Variable     | Descripción                                                                 |
|--------------|------------------------------------------------------------------------------|
| `survival`   | Supervivencia (0 = No, 1 = Sí)                                               |
| `pclass`     | Clase del boleto (1 = Primera, 2 = Segunda, 3 = Tercera)                     |
| `sex`        | Sexo                                                                         |
| `Age`        | Edad en años                                                                 |
| `sibsp`      | Número de hermanos/esposos a bordo                                           |
| `parch`      | Número de padres/hijos a bordo                                               |
| `ticket`     | Número de boleto                                                             |
| `fare`       | Tarifa del pasajero                                                          |
| `cabin`      | Número de cabina                                                             |
| `embarked`   | Puerto de embarque C = Cherbourg (Francia), Q = Queenstown (Irlanda), S = Southampton (Inglaterra)         |

# 📝 Notas sobre Variables

- **`pclass`**: Representa el estatus socioeconómico (SES)
  - 1st = Alta
  - 2nd = Media
  - 3rd = Baja

- **`age`**: 
  - Fraccional si es menor a 1 año
  - Si es estimada, se presenta como `xx.5`

- **`sibsp`**: Define relaciones familiares como:
  - Hermano(a), hermanastro(a)
  - Esposo(a) (se excluyen prometidos y amantes)

- **`parch`**: Define relaciones familiares como:
  - Padre/madre
  - Hijo(a), hijastro(a)
  - Algunos niños viajaban solo con niñera → `parch = 0`