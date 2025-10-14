# Proceso de Investigación y Análisis de Información

## Planificación
### Definición de objetivos
Se deben determiner objetivos específicos, medibles, alcanzables, relevantes y limitados en el tiempo. Un objetivo bien definido orienta todo el proceso y evita la recolección innecesaria de información, agilizando el proceso.

### Alcance
Delimitar el proyecto, estableciendo fronteras temporales, geográficas y temáticas. Esto incluye definir el periodo de tiempo a estudiar, las áreas o regiones que serán analizadas y los temas o categorías relevantes. Un alcance bien definido optimiza recursos y mejora la precisión de los resultados. Además, un alcance demasiado amplio puede incluir información que sea ilegal obtener.

### Requerimientos de la información
Determinar qué tipo de datos se necesitan, cuantitativos o cualitativos, su nivel de detalle, el formato requerido, la frecuencia de actualización y las fuentes potenciales.  
También es esencial definir los criterios de calidad, veracidad y actualidad de los datos.

### Consideraciones legales y éticas
Antes de iniciar, se deben identificar las leyes, regulaciones y normas éticas aplicables. Esto incluye el cumplimiento de normativas de protección de datos, el respeto a la privacidad y la propiedad intelectual, así como la transparencia en los métodos de obtención y uso de información.

### Selección de Fuentes
Es importante localizar y clasificar las fuentes primarias, secundarias y terciarias que puedan aportar información relevante.  
Se debe analizar la credibilidad, actualidad, precisión y objetividad de cada fuente, verificando quién la emite, su propósito y si existen conflictos de interés.  
Fuentes institucionales, académicas o gubernamentales suelen ofrecer mayor fiabilidad.

---

## Recolección

### Ejecución
Consiste en recopilar la información de las fuentes previamente identificadas, aplicando los métodos definidos en la planificación. Se debe documentar todo el proceso para garantizar trazabilidad y reproducibilidad.

### Métodos
- **Pasivas:** sin interactuar directamente con el objetivo (p. ej. búsquedas en Google, redes sociales).
- **Activas:** implican interacción directa o rastreo más profundo (p. ej. escaneo de puertos, peticiones web).

### Herramientas OSINT Framework – Búsqueda por Categoría
Se incluyen herramientas como:
- **Hunter.io:** Encuentra correos asociados a un dominio.
- **Shodan:** Buscador de dispositivos conectados a Internet.
- **TinEye:** Búsqueda inversa de imágenes.
- **Namechk:** Verifica disponibilidad de usuario en múltiples plataformas.
- **TrueCaller:** Identifica propietarios de números telefónicos.
- **OpenCorporates:** Datos de empresas y registros públicos.
- **Google Maps, OpenStreetMap:** Búsqueda geográfica y localización.
- **Ahmia, DarkSearch.io:** Motores de búsqueda de la Dark Web.

### Organización
Uso de **Maltego** para organizar, relacionar y visualizar los datos obtenidos, facilitando la identificación de patrones y vínculos ocultos.

### Verificación
Comparar los datos obtenidos en distintas plataformas para identificar coincidencias o discrepancias.  
Los datos críticos se verifican por al menos dos fuentes independientes (*Cross-validation*).  
Imágenes, vídeos y documentos se analizan mediante herramientas como **ExifTool**, **FotoForensics** o **InVID-WeVerify**.

---

## Análisis y Procesamiento

### Procesamiento
Limpieza y normalización de datos. Eliminación de duplicados, errores o información irrelevante.

### Interpretación
Comprender el sentido de la información, su origen, intención y relación con los objetivos iniciales.

### Correlación
Vincular diferentes elementos (IPs, usuarios, dominios, imágenes, fechas) para detectar patrones o comportamientos.

### Evaluación
Valorar la fiabilidad de las fuentes y la veracidad de los datos obtenidos.

### Síntesis
Integrar todos los hallazgos para generar una narrativa coherente o conclusiones estratégicas.

**Herramientas:** OpenRefine, NVivo, Maltego, Power BI, Tableau.

---

## Diseminación de Resultados

### Comunicación
Adaptación del mensaje según la audiencia, usando un lenguaje claro y estructurado.

### Accionable
Transformar los resultados en información práctica para la toma de decisiones.

### Formato
Presentación mediante reportes, dashboards, presentaciones o artículos.

### Feedback
Revisión, mejora continua y retroalimentación del público o del equipo.

**Herramientas:** Microsoft Word, Canva, Power BI, Notion, Slack, Google Forms.

---

## Aspectos Legales

### Leyes de Protección de Datos y Privacidad
Cumplir con las leyes de protección de datos (RGPD u otras).  
Evitar recolectar datos sensibles sin justificación legal.  
No almacenar ni compartir información personal sin autorización expresa.  
Asegurar la confidencialidad y protección de los datos recopilados.

### Términos de Servicio (ToS)
Respetar los términos de uso de cada plataforma.  
No usar métodos o herramientas que los violen.  
Revisar periódicamente las políticas de uso.

### Acceso No Autorizado
El OSINT solo debe trabajar con información pública.  
Está prohibido vulnerar sistemas protegidos o intentar eludir mecanismos de autenticación.

### Propiedad Intelectual
Respetar derechos de autor y propiedad intelectual.  
Citar siempre las fuentes utilizadas.  
No reproducir contenido protegido sin permiso.

### Difamación / Calumnia
Basar los informes en datos verificables.  
Evitar afirmaciones no comprobadas o juicios de valor.  
No difundir información falsa o engañosa.

---

## Aspectos Éticos

### Privacidad
Aunque la información sea pública, se debe proteger la privacidad individual.  
Evitar divulgar datos personales que puedan causar daño o exposición indebida.

### Contexto
Interpretar la información dentro de su contexto original.  
No alterar el sentido ni presentar datos de forma engañosa.

### Precisión
Verificar y validar la información con múltiples fuentes confiables.  
Evitar difundir datos no confirmados.

### Sesgo
Mantener una postura neutral y consciente de posibles sesgos.  
Documentar las limitaciones o sesgos detectados.

### No Abusar
El OSINT debe emplearse solo con fines legítimos y profesionales.  
Está prohibido usar información para acosar, discriminar o manipular.

### Impacto
Evaluar el impacto social, reputacional o emocional antes de publicar resultados.  
Priorizar siempre la responsabilidad ética sobre la exposición pública.
