### 💾 Bases de Datos - Evaluación Práctica.
---

### 📖 Descripción del Proyecto

Esta es un repositorio creado para mostrar los conocimientos adquiridos en la creación de repositorios y el uso de Github, como herramienta para manejar y gestionar los mismos

---

### ⚙️ Instrucciones de Instalación
---
Para poder clonar este repositorio, simplemente usa el link siguiente:

```bash
git clone https://github.com/armandomalave/BasesDeDatos-Practica.git
```

Luego puedes descargar los scripts de instalación y ejecutarlos en MySQL para poder recrear la base de datos.

---

### 🖥️ Uso
---
Cuando ya tengas creada la base de datos en MySQL, puedes hacer consultas de diversos tipos. Tomemos por ejemplo un Join de las tres tablas en donde se muestra los nombres de los empleados, su edad y el departamento donde trabajan.

  ```sql
    SELECT e.nombre_e AS Empleado, ed.edad AS Edad, d.nombred AS Departamento FROM empleado e 
    JOIN departamento d ON e.iddepartamento = d.iddepartamento
    JOIN edad ed ON e.idempleado = ed.empleado_idempleado;
```

---

### 🧑🏼‍💻 Contribución

Cómo Contribuir

1. **Has un Fork del Repositorio**
  
  - Haz clic en el botón “Fork” en la parte superior derecha del repositorio.
2. **Clona tu Fork**
  
  - Clona tu fork a tu máquina local:
    
    ```bash
    git clone https://github.com/tu-usuario/tu-repositorio.git
    ```
    
3. **Crea una Rama**
  
  - Crea una nueva rama para tu contribución:
    
    ```bash
    git checkout -b nombre-de-tu-rama
    ```
    
4. **Realiza Cambios**
  
  - Realiza los cambios necesarios en tu rama.
5. **Confirma tus Cambios**
  
  - Añade y confirma tus cambios:
    
    ```bash
    git add .
    git commit -m "Descripción de tus cambios"
    ```
    
6. **Sube tus Cambios**
  
  - Sube tus cambios a tu fork en GitHub:
    
    ```bash
    git push origin nombre-de-tu-rama
    ```
    
7. **Crea un Pull Request**
  
  - Ve a la página de tu fork en GitHub y haz clic en “New Pull Request”.

### Revisión de Código

- Asegúrate de que tu código sigue las guías de estilo del proyecto.
- Añade pruebas si es necesario.
- Espera la revisión y responde a cualquier comentario.

---

### 🧾 Licencia

Este proyecto se encuentra bajo la Licencia MIT. Para más detalles, consulta el archivo LICENSE.
