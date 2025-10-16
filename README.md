# Taller 2 (Laboratorio): Configuración de uso de Git y GitHub
# Cambio en GitHub
* Este cambio fue hecho directamente en GitHub
## Actividades

En el presente repositorio realizar la siguientes tareas:

1. Clonar (git clone) el repositorio en sus máquinas personales; usar git-bash

<img width="717" height="158" alt="image" src="https://github.com/user-attachments/assets/00a09000-b21f-4e06-afc7-3dfc4a221536" />

2. Crear un proyecto con el **IDE de programación Netbeans**, llamado **proyecto01**, el proyecto debe **ser ubicado en la carpeta** creada mediante el proceso de clonación.
3. En la clase Java (.java) creada mediante el proyecto de Netbeans, agregar el siguiente texto, **dentro del método main**, para que se presente dicha información al ejecutar el programa:

```
Ejemplo básico de Java
Versionado a través de Git
Manejado desde GitHub
```
  Recuerde usar la sentencia

```java
System.out.println("Ejemplo básico de Java Versionado a través de Git Manejado desde GitHub");
```

<img width="1110" height="542" alt="image" src="https://github.com/user-attachments/assets/0acfdb98-9b02-45aa-97cc-79239938c280" />

4. Regresar al git-bash (verificar que estemos dentro de la carpeta clonada, pwd)

<img width="412" height="66" alt="image" src="https://github.com/user-attachments/assets/c2118bfe-0507-4c62-b467-851bbb43a780" />

5. Ejecutar el comando

```
git status
```
Analizar la salida en consola

<img width="626" height="162" alt="image" src="https://github.com/user-attachments/assets/2cdcb365-65a8-4c2f-be18-2d9cbb7854ec" />

6. Ejecutar el comando

```
git add .
```

7. Ejecutar el comando

```
git commit -a -m "primer commit"
```

8. Ejecutar el comando

```
git push
```
Es posible que deba usar el proceso de autenticación con el token (creado previamente)

<img width="701" height="327" alt="image" src="https://github.com/user-attachments/assets/5a93f27c-9260-425f-9156-1d9c77958bac" />

9. Verificar que el repositorio en su cuenta de GitHub esté actualizado; en caso de no estar actualizado, **debe revisar los casos previos**.

<img width="1123" height="280" alt="image" src="https://github.com/user-attachments/assets/8da7d6cd-ac32-44eb-9ed2-dc757b051f8c" />

10. Regresar al IDE Netbeans, en su máquina persona y modificar la clase de Java creada en el proyecto de Netbeans, con el siguiente texto, para que se muestre cuando se ejecute el programa:

```
Ejemplo de Java
Manejado desde GitHub
Versionado a través de Git
Creado por <ubicar su usuario de github>
```

<img width="1103" height="552" alt="image" src="https://github.com/user-attachments/assets/7bc98aa7-ba61-4917-9eea-f5f1ca582b50" />

11. Ejecutar el comando

```
git add .
```
En esta **circunstacia el comando git add sería opcional**; pues, no hay archivos nuevos que gestionar, solo archivos modificados.

12. Ejecutar el comando

```
git commit -a -m "segundo commit"
```

13. Ejecutar el comando

```
git push
```

<img width="697" height="332" alt="image" src="https://github.com/user-attachments/assets/8342b4a3-c116-40ce-bd44-f3e164a0ea55" />

14. Verificar que el repositorio en su cuenta de github esté actualizado.

<img width="1135" height="282" alt="image" src="https://github.com/user-attachments/assets/f36bb9de-67c0-475d-992d-cf969a355e61" />

15. Crear un proyecto con el **IDE de programación Netbeans**, llamado proyecto02, el proyecto debe ser ubicado en la carpeta creada mediante el proceso de clonación.
16. En la clase de Java creada mediante el proyecto de Netbeans, agregar el siguiente texto, para que se presente al ejecutar el programa:

```
Ejemplo dos básico de Java
Versionado a través de Git
Manejado desde GitHub
Además se usar GitHubClassroom
```

<img width="720" height="482" alt="image" src="https://github.com/user-attachments/assets/19b09a20-d554-4341-8b84-3b5bb3e1500a" />

17. Regresar al git-bash (verificar que estemos dentro de la carpeta clonada)

<img width="647" height="58" alt="image" src="https://github.com/user-attachments/assets/95f494d2-3d38-4c64-9502-2627e28a6b71" />

18. Ejecutar el comando

```
git status
```
Analizar la salida en consola

19. Ejecutar el comando

```
git add .
```

<img width="628" height="270" alt="image" src="https://github.com/user-attachments/assets/1b20b762-561a-4add-8d0a-28113d0ebb8b" />

20. Ejecutar el comando

```
git commit -a -m "tercer commit, trabajando con Git y GitHubClassroom"
```

21. Ejecutar el comando

```
git push
```

<img width="702" height="377" alt="image" src="https://github.com/user-attachments/assets/446d6286-c0ec-4c49-a653-8bace2c78cbf" />

22. Verificar que el repositorio en su cuenta de **GitHub** esté actualizado.

<img width="1131" height="278" alt="image" src="https://github.com/user-attachments/assets/b1f68057-179a-4204-a761-30347a588a85" />

23. Simular un cambio remoto, para ello se generará un cambio directo en la plataforma GitHub

* Localiza el archivo README.md
* Haz clic en el ícono de edición (lápiz) para modificar el archivo directamente en GitHub.
* Agrega una línea de texto simple, como:

```md
# Cambio en GitHub
* Este cambio fue hecho directamente en GitHub
```
* Haz Commit del cambio directamente en la interfaz web de GitHub (usando el botón "Commit changes")
* **Atención**: El repositorio en GitHub tiene un commit que tu máquina local aún no tiene.

<img width="602" height="111" alt="image" src="https://github.com/user-attachments/assets/9e26d900-9ee1-4518-9aa3-19fab8000908" />

24. Sincronizar cambios a la Máquina Local (Usando git pull)
* Regresar a Git-Bash en tu máquina local (dentro de la carpeta clonada)
* Analizar la salida en consola: Git mostrará que ha descargado un commit y ha fusionado (merged) los cambios en tu rama local.

25. Verificar la integración del Cambio

<img width="677" height="352" alt="image" src="https://github.com/user-attachments/assets/9e3fcec6-8687-4c64-9427-245460e9af32" />

* Abrir el archivo README.md y verificar que la línea que agregaste en GitHub

<img width="588" height="113" alt="image" src="https://github.com/user-attachments/assets/6825f2d5-5dbb-40a9-8033-2f03eba81f0d" />

