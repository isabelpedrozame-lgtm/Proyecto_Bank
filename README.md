# Proyecto_Bank


## Objetivo general
- Esta es una aplicación de un banco. Es un API REST utilizando spring Boot en Java, esta muy bien estructurado por medio de paquetes.
---
## Extensiones 
En visual studio las extensiones son herramientas especializadas que transforman su editor de texto en un Entorno de Desarrollo, capaz de entender y construir una aplicación de banco con Java y Spring Boot.
Las extensiones principales que utlizamos son: 

-Java Extension Pack: Incluye el soporte básico para Java, debugging y el Test Runner.

-Spring Boot Tools: Proporciona autocompletado y navegación específicos para las clases y la configuración de Spring.

-Maven for Java: Herramienta esencial para gestionar el archivo pom.xml y las dependencias.

## ¿Que se encuentra?
-Una clase Customer para los clientes, una clase Account como base para las cuentas bancarias, de esas sale el CheckingAccount o sea cuenta corriente y SavingsAccount, cuenta de ahorro, que son muy utiles y necesarios para la aplicación.

## ¿Para que nos sirven los paquetes que tenemos?
- **El model**:Contiene las clases principales como Customer, Account, CheckingAccount y SavingsAccount.

- **service**: Aquí está la lógica del negocio, como crear cuentas, aplicar intereses o manejar retiros.

- **controller**: Se encarga de recibir las peticiones HTTP (por ejemplo, crear clientes o ver las cuentas).

- **repository**: Administra los datos y simula la conexión con una base de datos usando JSON.

- **exception**: Maneja errores personalizados para mostrar mensajes más claros cuando algo sale mal.
  
### Funcionamiento basico 
-Como se puede observar permite realkzar operaciones basicas de un banco como:
Registrar clientes, crear diferentes tipos de cuentas ahorros y corriente, retirar o depositar dinero, aplicar intereses o verificar límites de sobregiro.
Todo esto se hace por medio de peticiones HTTP, que se pueden probar con Postman o Thunder Client.
- **Como se prueba**:
- En Visual Studio Code, asegúrate de tener instalada la extensión Thunder Client.
- - **<img width="605" height="197" alt="image" src="https://github.com/user-attachments/assets/fcf65eff-9460-44ed-9887-f7757c503187" />**
- Crear una nueva petición, se da clic en New RequestEn la parte superior selecciona el método POST,En la barra de URL coloca la dirección de tu endpoint, casi siempre es  http://localhost:8080/api/bank/customers.
- **<img width="302" height="260" alt="image" src="https://github.com/user-attachments/assets/6dc3f31b-47d0-4be8-a6ce-151ab107809a" />**

- **<img width="770" height="383" alt="image" src="https://github.com/user-attachments/assets/1cd308b4-9c43-47b3-bb69-3c749860abca" />**
- Y de esta manera se puede ver, asi mismo se puede hacer la peticion de la cuenta bancaria.
