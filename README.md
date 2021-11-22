# Presto

Presto es una aplicación para gestionar el presupuesto personal y del hogar. Permite registrar gastos de manera diaria. Cada uno está compuesto por una categoría, una subcategoría y un importe. En el area de reportes se puede visualizar el gasto acumulado mensual a través de un gráfico de torta ordenado según las categorías.


## Listados de endpoints

### Manejo de usuarios
| Method  | Endpoint | Authorization |
| :-------------: | :-------------: | :--------------: |
| GET      | /users     | ❌ |
| POST      | /users     | ❌ |

#### Uso de endpoints

- [POST] /users
Recibe un objeto usuario de la siguiente manera:
```json
{}
```
Retorna un objeto usuario con el siguiente formato:
```json
{}
```

### Manejo de registros

| Method  | Endpoint | Authorization |
| :-------------: | :-------------: | :--------------: |
| GET      | /records     | ✅ |
| POST      | /records     | ✅ |

#### Uso de endpoints


### Manejo de categorias

| Method  | Endpoint | Authorization |
| :-------------: | :-------------: | :--------------: |
| GET      | /categories     | ❌ |
| POST      | /categories     | ❌ |

#### Uso de endpoints


### Manejo de reportes

| Method  | Endpoint | Authorization |
| :-------------: | :-------------: | :--------------: |
| GET      | /reports     | ✅ |
| POST      | /reports     | ✅ |

#### Uso de endpoints