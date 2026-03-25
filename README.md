#  Herramienta de Gestión Local - Analista B2B (Distribución)

##  Información General
Esta es la versión oficial de distribución de la **Herramienta de Gestión para Analistas de Conectividad B2B**. Diseñada para optimizar el flujo de trabajo mediante la automatización de diagnósticos, gestión de históricos y generación de reportes técnicos.

> **Nota de Seguridad:** El código en esta distribución ha sido ofuscado para proteger la lógica de negocio y garantizar la integridad del sistema. La herramienta funciona bajo una arquitectura **100% Client-Side** (Local), asegurando que los datos procesados nunca salgan de su estación de trabajo.

---

##  Descarga y Ejecución

Para garantizar la seguridad y privacidad, la aplicación se distribuye como un paquete comprimido y protegido.

1.  **Descarga:** Diríjase a la sección [**Releases**](https://github.com/crd10lop/Herramienta-Soporte-TG-CW-Dist/releases) de este repositorio.
2.  **Versión:** Descargue el archivo `.zip` de la versión que prefiera.
3.  **Descompresión:** Utilice la contraseña proporcionada por el administrador para extraer los archivos con 7zip. 
4.  **Ejecución:** Localice el archivo `Aplicacion de navegador.html` o `Soporte B2B - Herramienta` y ábralo con Microsoft Edge.

### 🌐 Modo "Aplicación de Escritorio" (Recomendado)

Para una mejor experiencia, puedes aislar la herramienta en su propia ventana, sin pestañas ni distracciones, funcionando exactamente como una aplicación nativa instalada en tu PC. 

Sigue estos 3 sencillos pasos para configurar el acceso directo usando **Microsoft Edge** (Navegador corporativo estándar):

**Paso 1: Copiar la ruta de la aplicación**
1. Abre la carpeta donde descargaste/descomprimiste esta herramienta.
2. Abre el archivo `index.html` en tu navegador.
3. Copia toda la dirección de la barra superior. Se verá algo así:
   `file:///C:/Users/TuUsuario/Ruta/Soporte-B2B/index.html`

**Paso 2: Crear el acceso directo**
1. Ve al Escritorio de tu PC, haz clic derecho en un espacio vacío > **Nuevo** > **Acceso directo**.
2. En la casilla de ubicación, pega el siguiente comando. **Atención:** Asegúrate de reemplazar `LA_RUTA_QUE_COPIASTE` por la ruta real de tu archivo del Paso 1, manteniendo las comillas:

   ```
   "C:\Program Files (x86)\Microsoft\Edge\Application\msedge.exe" --app="LA_RUTA_QUE_COPIASTE"
   ```

---

##  Funcionalidades Destacadas desde la V008.

* **Módulo de Auditoría Local:** Historial completo de casos gestionados con filtros inteligentes y autoguardado preventivo.
* **Rayo Mágico (P6):** Procesamiento de datos de CRM mediante expresiones regulares y detección automática de tecnología.
* **Reportes Inteligentes:** Generación de documentos `.docx` dinámicos que inyectan automáticamente descartes de diagnóstico o reprueba.
* **Geolocalización Offline:** Normalización de direcciones y asignación de barrios para Medellín y Bogotá sin necesidad de internet.
* **Persistencia de Datos:** Los datos se mantienen en el navegador, permitiendo recuperar gestiones en caso de cierres accidentales.

---

##  Gestión de Acceso (Hardware ID)
Para activar su usuario, la herramienta requiere el identificador único de su equipo. 
1. Ejecute el archivo `obtener_id.html` incluido en este repositorio o en su descarga.
2. Copie el **ID DE HUELLA** generado.
3. Envíe este ID al administrador para que su equipo sea autorizado en la base de datos de seguridad.

---

##  Historial de Versiones (Changelog)

### **V009 - Release Actual (Estable)** - Optimización de Búsqueda y Prevención de Pérdida de Datos
* Añadido: Motor de búsqueda independiente y aislado para "Enlaces de Aplicativos", con generación de botones dinámicos.
* Mejora: Rediseño del panel de ayuda lateral, dividiendo la "Base de Conocimientos" (teoría) y los "Enlaces Rápidos" para evitar la saturación visual.
* Corrección: Optimización en la lógica del botón "Limpiar Pantalla". Ahora previene la duplicación de casos en el historial y respalda de forma inteligente los datos como "Incompleto" únicamente cuando es necesario.

### **V008 - Panel de auditoria - Guardar casos y exportar a csv. 
* Implementación de panel de Auditoría y exportación masiva a `.csv`.
* Cierre de sesión automático por cambio de día (Hora Local CO).
* Optimización del motor de plantillas Word con lógica de inyección de imágenes.
* Limpieza de kernel y mejora en la velocidad de carga.

### **V007 - Interfaz y Preturno**
* Rediseño visual de la barra de navegación.
* Nuevos botones para gestión de Preturno e Imputabilidad.
* Ampliación de la base de usuarios autorizados.

### **V006 - Kernel de Seguridad**
* Actualización de algoritmos de seguridad y bases de datos locales.
* Refactorización de guiones técnicos para LC y N2.

### **V004 - V005 - El Botón Mágico**
* Lanzamiento del módulo de procesamiento rápido de texto (P6).
* Implementación de temporizador de gestión y alertas sonoras.

### **V002 - V003 - Reingeniería Geográfica**
* Estructura de ubicación en 3 filas (Empresa / Ciudad-Dir / Depto-Barrio).
* Lógica para direcciones complejas (Sur, Este, Circulares).
* Botón "IdCorp" y resúmenes de llamadas destacados.

### **V001 - Versión Inicial**
* Funcionalidad base de búsqueda de NE y generación de Word con hora actualizada.

---

##  Notas Técnicas
* **Compatibilidad:** Optimizada para navegadores basados en Chromium (Chrome/Edge).
* **Propiedad:** El código fuente original y la lógica de ofuscación son propiedad de **crd10lop**. Queda prohibida la redistribución no autorizada.
