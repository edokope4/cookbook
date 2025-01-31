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

| Anotacion    | Descripción |
|:-------------|:------------:|
| @Repository | Anotación para repositorio |

#### Inyección dependencias automáticamente

| Anotacion    | Descripción |
|:-------------|:------------:|
| @Autowired | Anotación para repositorio |

