# 📄 README - Instrucciones de instalación y ejecución

---

## 📦 Archivos incluidos

- `app.py` → Código principal de la aplicación.
- `config.py` → Configuración (APIs, parámetros, etc.).
- `icon.ico` → Ícono para el instalador o accesos directos.
- `lanzar_app.bat` → Script para lanzar la aplicación fácilmente.
- `requirements.txt` → Lista de librerías necesarias.

---

## 💻 Requisitos del sistema

- **Windows 10/11** (64 bits)
- **Python 3.10 o 3.11** instalado  
  (⚠️ Al instalar Python, asegurarse de activar la casilla **"Add Python to PATH"**)
- **Acceso a Internet** (solo para la primera instalación de librerías)

---

## 🛠️ Instalación paso a paso

1. **Abrir CMD** o **PowerShell**.

2. **Navegar a la carpeta del proyecto**:  
   (ajusta la ruta según donde copiaste la carpeta)

   ```bash
   cd C:\Ruta\A\Tu\Carpeta\pdf_ai_app
   ```

3. **Crear el entorno virtual**:

   ```bash
   python -m venv venv
   ```

4. **Activar el entorno virtual**:

   ```bash
   call venv\Scripts\activate
   ```

5. **Instalar las dependencias**:

   ```bash
   pip install -r requirements.txt
   ```

6. **Ejecutar la aplicación**:

   - Opcion 1: Manualmente

     ```bash
     streamlit run app.py
     ```

   - Opcion 2: Más fácil  
     **Doble clic en `lanzar_app.bat`** 🚀

---

## 🚀 Uso rápido

Una vez que la aplicación esté ejecutándose, tu navegador abrirá automáticamente la app.  
Si no se abre, ve manualmente a:

```
http://localhost:8501
```

---

## 🔥 Tips adicionales

- **No elimines** el archivo `icon.ico` (si quieres usar un instalador o acceso directo personalizado).
- **No necesitas copiar** la carpeta `venv` original de otra computadora.
- Siempre puedes regenerar `venv` y reinstalar dependencias usando `requirements.txt`.

---

## ❓ Problemas comunes

- **La consola se cierra inmediatamente**  
  → Ejecutar desde terminal manualmente para ver el error.

- **"Python no reconocido"**  
  → Python no fue agregado al PATH. Reinstalar asegurando marcar **"Add to PATH"**.

- **Problemas de permisos**  
  → Ejecutar CMD como **Administrador**.

---

📌 **Autor:** Tu Nombre o Equipo  
📌 **Fecha:** Abril 2025  

---

