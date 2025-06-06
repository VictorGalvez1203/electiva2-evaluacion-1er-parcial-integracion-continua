# electiva2-evaluacion-1er-parcial-integracion-continua

# 🧪 Evaluación 1er Parcial - Electiva 2  
### Integración Continua con Surge.sh y GitHub Actions

📚 **Asignatura:** Electiva 2  
👨‍💻 **Estudiante:** Victor Eulogio Galvez Faña | 2023-1836

---

## 🎯 Objetivo

Implementar un sistema de **Integración Continua (CI)** utilizando **GitHub Actions** y **Surge.sh** para desplegar automáticamente una página web sencilla cada vez que se realice un `push` a la rama `main`.

---

## 📋 Requisitos de la práctica

### ✅ Pasos a seguir:

1. **📁 Crear repositorio local**
   - Crear una carpeta de proyecto.
   - Dentro de ella, crear un archivo `index.html` con contenido básico

2. **☁️ Crear repositorio en GitHub**
   - Subir el proyecto local al repositorio remoto en GitHub.
   - Asegurarse de usar la rama `main`.

3. **⚙️ Crear el workflow en GitHub Actions**
   - Crear el directorio `.github/workflows/` dentro del proyecto.
   - Añadir un archivo `main.yaml` con la configuración de despliegue automático a Surge.sh.

4. **📦 Instalar Surge.sh**
   - Instalar Surge globalmente:
     ```bash
     npm install --global surge
     ```
   - Iniciar sesión:
     ```bash
     surge login
     ```

5. **🚀 Probar que todo funciona**
   - Hacer `git push` al repositorio.
   - Confirmar que GitHub Actions ejecuta correctamente el workflow.
   - Verificar que la página web está desplegada en Surge.

