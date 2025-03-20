
## 📝 Informe de Post-Laboratorio

---

### Introducción  
- **Git:** Sistema de control de versiones que permite gestionar cambios en el código, crear y fusionar ramas y mantener un historial detallado del proyecto. Es especialmente útil para el trabajo en equipo y proyectos de gran envergadura.  
- **GitHub:** Plataforma en la nube para alojar repositorios Git, colaborar con otros desarrolladores, compartir y visualizar proyectos. Su interfaz facilita el seguimiento de cambios y la gestión de issues.  

**Objetivo del laboratorio:**  
Familiarizarnos con el uso básico de Git y GitHub para gestionar repositorios y trabajar de manera colaborativa en futuros proyectos.

---

### Desarrollo  
1. **Creación y configuración del repositorio:**  
   - Creación de una carpeta de trabajo para inicializar el repositorio.  
   - Inicialización del repositorio Git con `git init`.  
   - Creación del archivo `README.md` en el bloc de notas y colocación en la carpeta del repositorio.  

2. **Gestión de cambios:**  
   - Prueba de comandos para guardar cambios en el *staging area*, confirmarlos y versionarlos con commits.  
   - Creación, cambio y combinación de ramas (*branches*).  

3. **Conexión con GitHub:**  
   - Creación de un repositorio remoto en GitHub.  
   - Conexión del repositorio local con el remoto mediante el comando `git remote add origin <URL>`.  

4. **Capturas de pantalla de los comandos ejecutados:**  
   - ![Comando 1](https://github.com/user-attachments/assets/0ed1c21b-7f7e-4a33-9033-9544145cd9bf)  
   - ![Comando 2](https://github.com/user-attachments/assets/d8e27e80-587c-40be-98dd-070822284454)  
   - ![Comando 3](https://github.com/user-attachments/assets/ca6c634a-5fd7-481f-8201-53b6b228cb75)  
   - ![Comando 4](https://github.com/user-attachments/assets/13d7a41f-df07-43ab-982a-00fd933d3d04)  
   - ![Comando 5](https://github.com/user-attachments/assets/e66cd1bc-35ae-4b75-97ea-fe1e21572256)  

---

### Explicación de comandos utilizados  
- **`git init`:** Inicializa un nuevo repositorio Git en la carpeta actual.  
- **`git add README.md`:** Intenta agregar el archivo `README.md` al *staging area*.  
- **`git add .`:** Agrega todos los cambios en la carpeta al *staging area*.  
- **`git commit -m "mensaje"`:** Crea un commit con el mensaje indicado.  
- **`git log`:** Muestra el historial de commits.  
- **`git branch develop`:** Crea una nueva rama llamada `develop`.  
- **`git checkout develop`:** Cambia a la rama `develop`.  
- **`git status`:** Verifica el estado de los archivos y cambios no confirmados.  
- **`git merge develop`:** Fusiona la rama `develop` en la rama actual.  
- **`git remote add origin <URL>`:** Vincula el repositorio local con el remoto en GitHub.  
- **`git push --set-upstream origin master`:** Envía los cambios de la rama `master` al repositorio remoto y establece la rama de seguimiento.

---

### Conclusiones  
- **Aprendizajes:** Refuerzo de conocimientos sobre comandos básicos de Git y GitHub, manejo de ramas y conexión de repositorios locales con remotos.  
- **Dificultades:**  
  - Problemas para ubicar correctamente el archivo `README.md`.  
  - Dificultad para conectar el repositorio local con el remoto.  
  - Resolución: Revisar la documentación oficial y errores en la consola para corregir comandos y rutas.  

---

### Anexos  
- [Enlace al repositorio remoto en GitHub](URL_DEL_REPOSITORIO)
```
