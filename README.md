# Crear el archivo README.md con la invitación
readme_content = """
# 🎉 Promoción MARVEL 🎉

¡Te invitamos a disfrutar de nuestra increíble promoción MARVEL! 🦸‍♂️🦸‍♀️

## 📅 Fecha y Hora
🗓 **Fecha:** 22 de este mes  
⏰ **Hora:** 6:00 PM  

## 📍 Ubicación
**Lugar:** EN EL DORADO VIP  

## 🌟 Descripción
✨ **No faltes, te esperamos** ✨

## 🎵 Música
Disfruta de esta canción especial para la promoción:  
[🎵 Escucha la música aquí](Los_Graduados_39s.mp3)

## 📸 Promoción Visual
![Imagen de la Promoción](imagen.jpeg)

---

### 🚀 Instrucciones para cargar en GitHub
1. Sube el archivo `README.md` al repositorio de GitHub.
2. Sube también los archivos:
   - `imagen.jpeg` (la imagen adjunta).
   - `Los_Graduados_39s.mp3` (la música recortada).
3. Comparte el enlace del repositorio con tus invitados.

---
"""

# Guardar el contenido en un archivo README.md
readme_path = "/mnt/data/README.md"
with open(readme_path, "w") as readme_file:
    readme_file.write(readme_content)

readme_path
