# Principio-POO

# Principio- S

Una clase debe tener una única responsabilidad, es decir, una única función. Si una clase tiene varias responsabilidades, esto implica que el cambio en una responsabilidad provocará la modificación en otra responsabilidad.

![image](https://github.com/user-attachments/assets/4ac636ff-98d2-4fd5-b62c-7e1420483307)

![image](https://github.com/user-attachments/assets/ba2ed56a-e81f-469a-ad98-fb3f595098ff)

El Principio de Responsabilidad Única (SRP) en la programación orientada a objetos establece que una clase debe tener una única responsabilidad o razón para cambiar. Es decir, cada clase debe encargarse de una sola tarea o funcionalidad en el sistema.


# Ejemplo e JAVA

Supongamos que tenemos un sistema que debe gestionar la creación de informes en una empresa y, además, debe enviar estos informes por correo electrónico.
  - Si no aplicamos el SRP, podríamos tener una clase que hace ambas tareas (gestionar informes y enviar correos), lo cual no sería recomendable porque estaríamos mezclando     responsabilidades. Vamos a aplicar el SRP dividiendo las responsabilidades en dos clases: una para gestionar los informes y otra para gestionar el envío de correos electrónicos.


![image](https://github.com/user-attachments/assets/d0bf79e3-9d52-4541-b43a-8796ae843c17)



![image](https://github.com/user-attachments/assets/44f62e89-38f0-43a5-a862-b7d0b86ea83b)


Informe: Se encarga únicamente de gestionar el contenido y la generación del informe.
ServicioDeCorreo: Se encarga únicamente de enviar los correos electrónicos.


