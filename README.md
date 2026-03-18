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
4.  **Ejecución:** Localice el archivo `Aplicacion de navegador.html` y ábralo con Microsoft Edge.

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

### **V008 - Release Actual (Estable)**
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
