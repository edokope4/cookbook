### Anotaciones para SpringBoot

#### Main Clase Main
| Anotacion    | Descripción |
|:-------------|:------------:|
| @SpringBootApplication | Para indicar que sera la clase principal de Springboot, la que hace iniciar todo, el génesis. |

#### Controllers

| Anotacion    | Descripción |
|:-------------|:------------:|
| @RestController | Definicion rest controller. |
| @RequestMapping("/ruta") | Explicacion de lo anterior |
| @CrossOrigin("*") | Descripcion de CrossOrigin * para recibir de toos lados las request | 
| @PostMapping("/login") | se pone antes de un metodo | 
| @GetMapping | Rutea la petición por GET para un metodo en particular. Se anota antes de la firma del método |

----

#### Servicios interface
| Anotacion    | Descripción |
|:-------------|:------------:|
| @Service | Definicion de servicio en Springboot. |


#### Servicios Implementación

| Anotacion    | Descripción |
|:-------------|:------------:|
| @Component | Componente para implementar el servicio de la interface. |


#### Entidades

| Anotacion    | Descripción |
|:-------------|:------------:|
| @Entity | Anotación para entidad |

#### Repositorios

Esta anotación indica que esta interfaz es un repositorio de Spring. Los repositorios en Spring son responsables de interactuar con la capa de persistencia (por ejemplo, una base de datos). Spring gestiona automáticamente la creación de una implementación de esta interfaz en tiempo de ejecución.

- **JpaRepository** es una interfaz proporcionada por Spring Data JPA que ofrece métodos CRUD (Crear, Leer, Actualizar, Eliminar) y de paginación para interactuar con la base de datos.

- **TransaccionInternaEntity** es la entidad (clase de modelo) con la que este repositorio trabajará. Esta entidad está mapeada a una tabla en la base de datos.

- **Long** es el tipo de dato de la clave primaria (id) de la entidad TransaccionInternaEntity.

```java
/** Repositorio para Ejemplo.*/
@Repository
public interface EjemploRepository extends JpaRepository<EjemploEntity, Long> {
}
```

----

| Anotacion    | Descripción |
|:-------------|:------------:|
| @Repository | Anotación para repositorio |

#### Inyección dependencias automáticamente

| Anotacion    | Descripción |
|:-------------|:------------:|
| @Autowired | Anotación para repositorio |

