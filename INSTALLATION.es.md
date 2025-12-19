# Guía de instalación de OPTIMAEUS

## Instrucciones paso a paso para todas las plataformas

---

## 🍎 Instalación macOS

### Paso 1: Descarga
1. Ve a la [Última versión](https://github.com/octavieploye/optimaeus-release/releases/latest)
2. Haz clic en `OPTIMAEUS_1.0.0_aarch64.dmg` (Apple Silicon) o `OPTIMAEUS_1.0.0_x64.dmg` (Intel)
3. Espera a que se complete la descarga

### Paso 2: Instalación
1. **Haz doble clic** en el archivo `.dmg` descargado
2. Se abrirá una ventana mostrando la aplicación OPTIMAEUS
3. **Arrastra** el icono de OPTIMAEUS a la carpeta Aplicaciones
4. Cierra la ventana

### Paso 3: Primer inicio (¡Importante!)
Como OPTIMAEUS no es de la App Store, macOS pedirá permiso:

1. Abre **Finder** → Ve a **Aplicaciones**
2. Encuentra **OPTIMAEUS**
3. **Clic derecho** (o Control-clic) en OPTIMAEUS
4. Haz clic en **"Abrir"** en el menú
5. Aparecerá un diálogo diciendo que la app es de un desarrollador no identificado
6. Haz clic en **"Abrir"** para confirmar

> ⚠️ **Nota:** Solo necesitas hacer el paso del clic derecho una vez. Después de eso, puedes abrir OPTIMAEUS normalmente.

### Paso 4: Configuración
1. La aplicación se abrirá y te pedirá crear una **Contraseña de padre**
2. Ingresa una contraseña que recordarás (esto protege la configuración de padres)
3. ¡Estás listo para comenzar!

---

## 🪟 Instalación Windows

### Paso 1: Descarga
1. Ve a la [Última versión](https://github.com/octavieploye/optimaeus-release/releases/latest)
2. Haz clic en `OPTIMAEUS_1.0.0_x64_en-US.msi` o `OPTIMAEUS_1.0.0_x64-setup.exe`
3. Espera a que se complete la descarga

### Paso 2: Instalación
1. **Haz doble clic** en el archivo `.msi` o `.exe` descargado
2. Windows puede mostrar una advertencia de seguridad:
   - Haz clic en **"Más información"**
   - Haz clic en **"Ejecutar de todos modos"**
3. Sigue las indicaciones del instalador
4. Elige la ubicación de instalación (la predeterminada está bien)
5. Haz clic en **"Instalar"**
6. Haz clic en **"Finalizar"** cuando termine

### Paso 3: Inicio
1. Encuentra OPTIMAEUS en tu **Menú Inicio**, o
2. Haz doble clic en el **acceso directo del escritorio** (si se creó)

### Paso 4: Configuración
1. La aplicación se abrirá y te pedirá crear una **Contraseña de padre**
2. Ingresa una contraseña que recordarás
3. ¡Estás listo para comenzar!

---

## 🐧 Instalación Linux

### Opción A: Ubuntu/Debian (.deb)

1. Descarga el archivo `.deb` desde la [Última versión](https://github.com/octavieploye/optimaeus-release/releases/latest)
2. Abre Terminal en la carpeta de descarga
3. Ejecuta:
```bash
sudo dpkg -i OPTIMAEUS_1.0.0_amd64.deb

# Si ves errores de dependencias:
sudo apt-get install -f
```

Inicia desde el menú de tu aplicación o ejecuta: `optimaeus`

### Opción B: Fedora/RHEL (.rpm)

1. Descarga el archivo `.rpm` desde la [Última versión](https://github.com/octavieploye/optimaeus-release/releases/latest)
2. Abre Terminal en la carpeta de descarga
3. Ejecuta:
```bash
sudo dnf install OPTIMAEUS_1.0.0_amd64.rpm
# O:
sudo rpm -i OPTIMAEUS_1.0.0_amd64.rpm
```

Inicia desde el menú de tu aplicación o ejecuta: `optimaeus`

### Opción C: AppImage (Universal - No requiere instalación)

1. Descarga el archivo `.AppImage` desde la [Última versión](https://github.com/octavieploye/optimaeus-release/releases/latest)
2. Abre Terminal en la carpeta de descarga
3. Ejecuta:
```bash
# Hacerlo ejecutable
chmod +x OPTIMAEUS_1.0.0_amd64.AppImage

# Ejecutarlo
./OPTIMAEUS_1.0.0_amd64.AppImage
```

> **Consejo:** Puedes mover el AppImage a cualquier carpeta y ejecutarlo desde allí. ¡No se requiere instalación!

---

## 🤖 Descargando el modelo de IA

Después de instalar OPTIMAEUS, necesitarás descargar un modelo de IA (aproximadamente 4-5 GB):

### Paso 1: Abrir el Panel de Control de Padres
1. Inicia OPTIMAEUS
2. Ingresa tu contraseña de padre
3. Ve a **Configuración** o **Configuración del modelo**

### Paso 2: Descargar modelo recomendado
1. La aplicación mostrará modelos recomendados según tu computadora
2. Haz clic en **"Descargar"** junto al modelo recomendado
3. Espera la descarga (puede tomar 10-30 minutos según la velocidad de internet)

### Paso 3: Establecer ruta del modelo
1. Después de la descarga, la aplicación preguntará dónde guardaste el modelo
2. Navega al archivo `.gguf` descargado
3. Haz clic en **"Seleccionar"** o **"Abrir"**

### Paso 4: Probar que funciona
1. Ve a la Sala de Niños
2. Crea un perfil de prueba
3. Envía un mensaje como "¡Hola!"
4. Si la IA responde, ¡estás listo! 🎉

---

## 👨‍👩‍👧‍👦 Configuración de perfiles de niños

### Agregar un niño
1. Abre OPTIMAEUS e inicia sesión como padre
2. Ve al **Panel de Control de Padres**
3. Haz clic en **"Agregar niño"**
4. Ingresa el nombre del niño
5. Crea un PIN de 4 dígitos para ellos
6. Haz clic en **"Guardar"**

### Inicio de sesión del niño
1. En la pantalla principal, el niño selecciona su nombre
2. Ingresa su PIN de 4 dígitos
3. Elige un compañero (Tareas, Arte, o Investigación)
4. ¡Puede comenzar a chatear!

---

## 🗑️ Desinstalando OPTIMAEUS

### macOS
1. Abre **Finder** → **Aplicaciones**
2. Encuentra **OPTIMAEUS**
3. Arrástralo a la **Papelera**
4. Vacía la Papelera

Para eliminar todos los datos:
```bash
rm -rf ~/Library/Application\ Support/com.optimaeus.desktop
```

### Windows
1. Abre **Configuración** → **Aplicaciones** → **Aplicaciones instaladas**
2. Encuentra **OPTIMAEUS**
3. Haz clic en los **tres puntos** (⋮) → **Desinstalar**
4. Confirma la desinstalación

O usa Panel de control → Programas → Desinstalar un programa

### Linux

**Debian/Ubuntu:**
```bash
sudo apt remove optimaeus
```

**Fedora/RHEL:**
```bash
sudo dnf remove optimaeus
```

**AppImage:** Simplemente elimina el archivo AppImage (no se necesita desinstalación)

Para eliminar todos los datos:
```bash
rm -rf ~/.local/share/com.optimaeus.desktop
```

---

## ❓ Solución de problemas

### "La aplicación no se abre" (macOS)
- Asegúrate de haber hecho **clic derecho** y seleccionado "Abrir" (ver Paso 3 arriba)
- Prueba: Preferencias del Sistema → Seguridad y privacidad → Haz clic en "Abrir de todos modos"

### Advertencia "Editor desconocido" (Windows)
- Esto es normal para aplicaciones que no son de Microsoft Store
- Haz clic en "Más información" → "Ejecutar de todos modos"

### "La aplicación es lenta" (Windows/Linux)
- Esto es esperado - la versión actual usa CPU para el procesamiento de IA
- Los tiempos de respuesta de 10-30 segundos son normales
- macOS es más rápido porque usa aceleración GPU

### "Archivo de modelo no encontrado"
- Asegúrate de haber descargado un archivo de modelo `.gguf`
- Verifica que la ruta del archivo no tenga caracteres especiales
- Prueba colocar el modelo en una ruta simple como `Documents/models/`

### Error "Memoria insuficiente"
- Cierra otras aplicaciones
- Prueba un modelo más pequeño (Q4 en lugar de Q6)
- Necesitas al menos 8 GB de RAM

---

## 🆘 ¿Aún necesitas ayuda?

Contáctanos:
- Email: octavie.ploye@timaeus-consulting.com

¡Estamos felices de ayudarte a configurarlo! 😊
