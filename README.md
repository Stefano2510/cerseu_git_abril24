# Evaluación Curso "Control de Versiones con Git y GitHub" de Abril 2024

Esta evaluación examina algunos conocimientos teóricos y habilidades prácticas en el uso de Git y GitHub.

## Plazo de entrega

02 de Mayo de 2024.

**IMPORTANTE**: las respuestas deben guardarse en un repositorio en GitHub que cada participante debe crear. El link de tal repositorio se debe enviar a los docentes del curso.

## Puntaje

**IMPORTANTE**: la nota aprobatoria mínima es **11**.

| Parte   | Puntaje|
|:--------|:------:|
| Teorica | 10     |
| Practica| 10     |
| ======= |======  |
| Total   | 20     |

## Parte teórica

Marcar la(s) respuestas correctas.

1. **¿Qué es git?**
	- [ ] Un nombre alternativo de GitHub
	- [ ] Un lenguaje de programación
	- [X] Un sistema de control de versiones
	- [ ] Una plataforma que almacena repositorios remotos
2. **¿Cuáles son locaciones de git?**
	- [X] Working tree
	- [X] Área de preparación
	- [ ] Repositorio Remoto
	- [X] Repositorio Local
3. **¿Cuál es el comando usado para determinar la versión de git que tenemos instalada en nuestro sistema?**
	- [X] `git --version`
	- [ ] `git -help version`
	- [ ] `gitVersion`
	- [ ] `git help Version`
4. **¿Qué comando usamos para añadir todos los files del working tree al área de preparación?**
	- [ ] `git add "file"`
	- [X] `git add .`
	- [ ] `git add`
5.  **¿Cuál es el comando para verificar el status del repositorio?**
	- [X] `git status`
	- [ ] `git status repository`
	- [ ] `git --status`
6. **¿Cuál es el comando usado para inicializar un repositorio git en una carpeta?**
	- [ ] `git start`
	- [X] `git init`
	- [ ] `git initialize`
	- [ ] `git --start`
7. **¿Qué comando se usa para hacer un snapshot de nuestro repositorio?**
	- [ ] `git save`
	- [ ] `git snapshot`
	- [X] `git commit`
	- [ ] `git --save`
8. **¿Qué resultado se observa si se usa el comando `git log`?**
	- [X] La historia de los commits del repositorio
	- [ ] El status del repositorio
	- [ ] El número de ramas (branches) de un repositorio
	- [ ] Los archivos dentro del área de preparación
9. **¿Qué acción se ejecuta cuando se usa el comando `git checkout mi_branch`?**
	- [X] Uno se traslada hacia la rama "mi_branch"
	- [ ] Uno se traslada de la rama mi_branch a la rama master
	- [ ] Se ve la historia de la rama "mi_branch"
	- [ ] Se crea una rama denominada "mi_branch"
10. **¿Cuál es el objetivo de usar el comando `git merge`?**
	- [X] Unir dos o más ramas de un repositorio
	- [ ] Unir dos repositorios globales
	- [ ] Corregir una commit errado o incompleto

## Parte práctica

1. Usando la interface web de GitHub, crear un repositorio publico llamado "cerseu_git_abril24". Indicar el URL del repositorio creado


2. Desde su computadora local, clonar el repositorio creado en GitHub en la pregunta anterior. Indicar los comandos utilizados y la salida en la consola del sistema

![image](https://github.com/Stefano2510/cerseu_git_abril24/assets/95462072/13b196a3-be1c-4e53-9098-bb3079d2c26e)

3. En el directorio local de trabajo, crear tres o cuatro archivos conforme al siguiente formato: `<primer-nombre>.txt`, `<segundo-nombre>.txt`, `<apellido-paterno>.txt`, `<apellido-materno>.txt` (ejemplo: `juan.txt`, `perez.txt`, `garcia.txt`). Dichos archivos pueden tener cualquier texto como contenido. Indicar los comandos utilizados y la salida en la consola del sistema


4. Guardar esos archivos en su repositorio remoto (es decir, en GitHub). Indicar los comandos utilizados y la salida en la consola del sistema


5. Añadir un archivo `.gitignore` que permita ignorar cualquier archivo con extensión `*.pdf`, `*.xml`, y `*.zip` de nuestro repositorio.  Guardar esos archivos en su repositorio remoto. Indicar los comandos utilizados y la salida en la consola del sistema


6. Crear una rama de git (branch) llamada "bio". En esta rama añadir el archivo `biografia.md`. El contenido de este archivo debe ser su propia biografia en no mas de tres oraciones.  Guardar este archivo en su repositorio remoto. Indicar los comandos utilizados y la salida en la consola del sistema


7. Usando la interface web de GitHub, crear un _Pull Request_ para incorporar los cambios de la rama "bio" en la rama "main". Aprobar el _Pull Request_. Mostrar las capturas de pantalla relevantes

![Captura de pantalla 2024-05-01 224434](https://github.com/Stefano2510/cerseu_git_abril24/assets/95462072/870c52f6-ba40-4143-800d-b54ffa0c7f18)

![Captura de pantalla 2024-05-01 224533](https://github.com/Stefano2510/cerseu_git_abril24/assets/95462072/ba7e1a45-dc3f-4d78-bb86-995c48ba46b7)

![Captura de pantalla 2024-05-01 224602](https://github.com/Stefano2510/cerseu_git_abril24/assets/95462072/71a8605b-21e5-4408-81fa-a085adbf0b31)

![Captura de pantalla 2024-05-01 224618](https://github.com/Stefano2510/cerseu_git_abril24/assets/95462072/7fd15286-02b5-4ffa-b540-c5c379bc5713)

8. En el directorio local de trabajo, ejecutar `git pull`. Indicar los comandos utilizados y la salida en la consola del sistema

![image](https://github.com/Stefano2510/cerseu_git_abril24/assets/95462072/96a4f98b-5cb6-4d07-b0b5-6246fe98a2f0)

![image](https://github.com/Stefano2510/cerseu_git_abril24/assets/95462072/b1e7ea2f-4ae4-4fa1-a9fd-17f5bc4e935d)
