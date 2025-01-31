### Anotaciones para SpringBoot

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

@Component

#### Entidades

@Entity

#### Repositorios

@Repository

#### Inyección dependencias automáticamente

@Autowired