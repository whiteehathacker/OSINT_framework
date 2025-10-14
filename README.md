# Proceso de Investigación y Análisis de Información

## 1. Planificación

### 1.1 Definición de Objetivos
Se deben determinar objetivos **específicos, medibles, alcanzables, relevantes y limitados en el tiempo**.  
Un objetivo bien definido orienta todo el proceso y evita la recolección innecesaria de información, agilizando el proceso.

### 1.2 Alcance
Delimitar el proyecto estableciendo **fronteras temporales, geográficas y temáticas**.  
Esto incluye definir el periodo de tiempo a estudiar, las áreas o regiones que serán analizadas y los temas o categorías relevantes.  
Un alcance bien definido optimiza recursos y mejora la precisión de los resultados. Además, un alcance demasiado amplio puede incluir información que sea ilegal obtener.

### 1.3 Requerimientos de la Información
Determinar qué tipo de datos se necesitan (cuantitativos o cualitativos), su nivel de detalle, formato, frecuencia de actualización y fuentes potenciales.  
También es esencial definir los criterios de **calidad, veracidad y actualidad** de los datos.

### 1.4 Consideraciones Legales y Éticas
Antes de iniciar, se deben identificar las **leyes, regulaciones y normas éticas aplicables**.  
Esto incluye el cumplimiento de normativas de protección de datos, el respeto a la privacidad y la propiedad intelectual, así como la transparencia en los métodos de obtención y uso de la información.

### 1.5 Selección de Fuentes
Localizar y clasificar las fuentes **primarias**, **secundarias** y **terciarias** que puedan aportar información relevante.  
Se debe analizar la **credibilidad, actualidad, precisión y objetividad** de cada fuente, verificando su propósito y posibles conflictos de interés.

Fuentes institucionales, académicas o gubernamentales suelen ofrecer mayor fiabilidad.

---

## 2. Recolección

### 2.1 Ejecución
Consiste en recopilar la información de las fuentes previamente identificadas, aplicando los métodos definidos en la planificación.  
Se debe documentar todo el proceso para garantizar **trazabilidad** y **reproducibilidad**.

### 2.2 Métodos
- **Pasivos**: sin interactuar directamente con el objetivo (por ejemplo, búsquedas en Google, redes sociales).  
- **Activos**: implican interacción directa o rastreo más profundo (por ejemplo, escaneo de puertos, peticiones web).

### 2.3 Herramientas OSINT por Categoría

| Categoría | Herramienta / Enlace | Descripción |
|------------|----------------------|--------------|
| Email Address | [Hunter.io](https://hunter.io) | Encuentra correos asociados a un dominio. |
| | [Have I Been Pwned](https://haveibeenpwned.com) | Comprueba si un correo ha sido filtrado. |
| | [EmailRep.io](https://emailrep.io) | Analiza reputación y riesgo de emails. |
| IP & MAC Address | [Shodan](https://www.shodan.io) | Buscador de dispositivos conectados a Internet. |
| | [IPinfo.io](https://ipinfo.io) | Muestra información sobre direcciones IP. |
| | [MACVendors.com](https://macvendors.com) | Identifica el fabricante según dirección MAC. |
| Images / Videos / Docs | [Google Reverse Image Search](https://images.google.com) | Búsqueda inversa de imágenes. |
| | [TinEye](https://tineye.com) | Encuentra versiones o fuentes de imágenes. |
| | [ExifTool](https://exiftool.org) | Extrae metadatos de imágenes y documentos. |
| Social Networks | [Social-Searcher](https://www.social-searcher.com) | Busca menciones en redes sociales. |
| | [Namechk](https://namechk.com) | Verifica disponibilidad de usuario en múltiples plataformas. |
| | [WhatsMyName](https://whatsmyname.app) | Rastrea alias en decenas de sitios. |
| | [Maigret (GitHub)](https://github.com/soxoj/maigret) | Identifica perfiles y analiza alias. |
| | [Sherlock (GitHub)](https://github.com/sherlock-project/sherlock) | Busca alias en cientos de sitios desde terminal. |
| User & Identity Search | [Pipl](https://pipl.com) | Buscador de personas con base de datos global. |
| | [PeekYou](https://www.peekyou.com) | Encuentra perfiles sociales asociados a un nombre. |
| | [WebMii](https://webmii.com) | Muestra visibilidad online y redes vinculadas a un usuario. |
| | [ThatsThem](https://thatsthem.com) | Búsqueda por nombre, email, IP o teléfono. |
| | [Spokeo](https://www.spokeo.com) | Agrega datos públicos, correos y redes sociales. |
| Telephone Numbers | [TrueCaller](https://www.truecaller.com) | Identifica propietarios de números telefónicos. |
| | [Sync.me](https://sync.me) | Revela información pública de números. |
| Public Records | [OpenCorporates](https://opencorporates.com) | Datos de empresas y registros públicos. |
| | [CourtListener](https://www.courtlistener.com) | Acceso a registros judiciales en EE.UU. |
| | [GovData](https://www.govdata.de) | Portal de datos abiertos gubernamentales. |
| Geolocation | [Google Maps](https://maps.google.com) | Búsqueda geográfica y localización. |
| | [GeoNames](https://www.geonames.org) | Base de datos global de ubicaciones. |
| | [OpenStreetMap](https://www.openstreetmap.org) | Mapa colaborativo libre. |
| Search Engines | [Google](https://www.google.com) | Búsquedas avanzadas con operadores. |
| | [DuckDuckGo](https://duckduckgo.com) | Motor privado sin rastreo. |
| | [Yandex](https://yandex.com) | Excelente para búsqueda inversa de imágenes. |
| Dark Web | [Ahmia](https://ahmia.fi) | Buscador de servicios onion (Tor). |
| | [DarkSearch.io](https://darksearch.io) | Motor de búsqueda de la Dark Web. |
| | [OnionScan](https://github.com/s-rah/onionscan) | Analiza servicios ocultos Tor. |
| Training | [Trace Labs OSINT Training](https://www.tracelabs.org/resources/training) | Recursos de formación OSINT práctica. |
| | [Bellingcat Training](https://www.bellingcat.com/category/resources/how-tos/) | Guías y cursos de investigación open source. |

---

### 2.4 Organización
La organización de la información es clave para mantener trazabilidad y facilitar el análisis. Se recomienda:

- **Registro estructurado:** utilizar hojas de cálculo o bases de datos con campos estandarizados (fecha, fuente, URL, autor, tipo de evidencia, nivel de confianza, notas).  
- **Etiquetado y taxonomía:** aplicar etiquetas y categorías (por ejemplo: dominio, correo, IP, persona, empresa, imagen) para facilitar búsquedas y filtros.  
- **Herramientas de gestión:** emplear plataformas como **Maltego**, **Lampyre** o **SpiderFoot** para mapear relaciones y visualizar grafos.  
- **Almacenamiento seguro:** mantener un repositorio controlado (con control de acceso y cifrado) para archivos y capturas, registrando hashes y metadatos.  
- **Control de versiones:** documentar cada modificación relevante en el registro de investigación (qué se añadió, quién y cuándo).

### 2.5 Verificación
La verificación debe ser sistemática y documentada. Pasos recomendados:

1. **Cross-validation:** verificar datos críticos con al menos dos fuentes independientes.  
2. **Comprobación temporal:** confirmar la coherencia de fechas y la cronología de eventos.  
3. **Validación técnica:** analizar metadatos (ExifTool), encabezados de correo y registros WHOIS.  
4. **Verificación visual:** comprobar origen de imágenes y videos (TinEye, Google Reverse Image).  
5. **Registro de resultados:** anotar el método, herramientas y conclusión de cada verificación (incluyendo nivel de confianza: alta, media, baja).

**Herramientas de Verificación**

| Tipo | Herramienta / Enlace | Uso principal |
|------|----------------------|---------------|
| Análisis de metadatos | [ExifTool](https://exiftool.org) | Extraer metadatos de imágenes y documentos. |
| Verificación de imágenes y vídeos | [InVID-WeVerify](https://www.invid-project.eu/tools-and-services/invid-verification-plugin/) | Comprobar integridad y contexto de multimedia. |
| | [TinEye](https://tineye.com) | Búsqueda inversa y versiones de imágenes. |
| Comprobación de dominios y correos | [Have I Been Pwned](https://haveibeenpwned.com) | Verificar filtraciones de correos. |
| | [EmailRep.io](https://emailrep.io) | Evaluar reputación de direcciones de email. |
| Cronología y contexto | [Wayback Machine](https://archive.org/web/) | Ver historial de páginas web. |
| | [WhoisXML](https://www.whoisxmlapi.com) | Historial y cambios en registros WHOIS. |
| Evaluación de fuentes | [Hoaxy](https://hoaxy.iuni.iu.edu) | Analizar propagación de información en medios. |
| | [NewsGuard](https://www.newsguardtech.com) | Evaluación de medios según criterios periodísticos. |

---

## 3. Análisis y Procesamiento

Los datos brutos recolectados deben limpiarse, correlacionarse y contextualizarse para producir conclusiones relevantes.

### 3.1 Procesamiento
- Limpieza y normalización de los datos (OpenRefine, Excel/Google Sheets).  
- Eliminación de duplicados y corrección de errores.  
- Enriquecimiento de registros (resolución de dominios, geolocalización de IPs).

### 3.2 Interpretación
Comprender el sentido de la información, su origen, intención y relación con los objetivos iniciales. Identificar narrativas, discrepancias y posibles sesgos.

### 3.3 Correlación
Vincular diferentes elementos (IPs, usuarios, dominios, imágenes, fechas) para detectar **patrones, vínculos o comportamientos**. Utilizar grafos para visualizar relaciones.

### 3.4 Evaluación
Valorar la fiabilidad de las fuentes y la veracidad de los datos obtenidos; asignar niveles de confianza y priorizar evidencia en función de su criticidad.

### 3.5 Síntesis
Integrar todos los hallazgos para generar una narrativa coherente, conclusiones y recomendaciones accionables. Preparar entregables (informes, dashboards, presentaciones).

---

### 3.6 Herramientas OSINT Framework – Análisis y Procesamiento

| Paso | Herramienta / Enlace | Descripción |
|------|----------------------|-------------|
| Procesamiento | [OpenRefine](https://openrefine.org) | Limpieza y normalización de datos. |
| | [Excel](https://www.microsoft.com/excel) / [Google Sheets](https://www.google.com/sheets/about/) | Manipulación y análisis tabular. |
| Interpretación | [NVivo](https://www.qsrinternational.com/nvivo-qualitative-data-analysis-software/home) | Análisis cualitativo y codificación de texto. |
| | [KH Coder](https://khcoder.net/en/) | Análisis de contenido y minería de texto. |
| Correlación | [Maltego](https://www.paterva.com) | Visualización de relaciones y grafos. |
| | [SpiderFoot](https://www.spiderfoot.net) | Recolección y correlación automática de inteligencia. |
| Síntesis / Visualización | [Tableau](https://www.tableau.com) | Visualización interactiva y dashboards. |
| | [Power BI](https://powerbi.microsoft.com) | Dashboards y reporting interactivo. |

---

## 4. Diseminación de Resultados

### 4.1 Objetivos
La fase de diseminación de resultados busca comunicar eficazmente los hallazgos obtenidos durante el proceso OSINT.  
El objetivo es transformar la información analizada en **conocimiento útil, claro y orientado a la acción**.

### 4.2 Herramientas de Diseminación

| Aspecto | Herramienta / Enlace | Descripción |
|----------|----------------------|--------------|
| Comunicación | [Microsoft Word](https://www.microsoft.com/word) | Adaptación del mensaje según la audiencia. |
| | [Canva](https://www.canva.com) | Diseño de informes visuales. |
| | [Notion](https://www.notion.so) | Redacción colaborativa. |
| Accionable | [Trello](https://trello.com) | Organización de tareas y seguimiento. |
| | [Miro](https://miro.com) | Colaboración visual en tiempo real. |
| Formato | [Power BI](https://powerbi.microsoft.com) | Dashboards interactivos. |
| | [Tableau](https://www.tableau.com) | Visualización de datos avanzada. |
| | [PowerPoint](https://www.microsoft.com/powerpoint) | Presentaciones profesionales. |
| Feedback | [Google Forms](https://forms.google.com) | Recopila retroalimentación de usuarios. |
| | [Slack](https://slack.com) | Comunicación en equipo. |
| | [Microsoft Teams](https://www.microsoft.com/microsoft-teams) | Colaboración corporativa. |

---

## 5. Aspectos Legales

### 5.1 Leyes de Protección de Datos y Privacidad
Toda actividad deberá cumplir con las leyes de protección de datos personales vigentes (como el **RGPD** u otras normativas nacionales).  
- Evitar recolectar datos sensibles sin justificación legal.  
- No almacenar ni compartir información personal sin autorización expresa.  
- Asegurar la confidencialidad de los datos recopilados.

### 5.2 Términos de Servicio (ToS)
El acceso a plataformas digitales debe realizarse respetando los **Términos de Servicio** de cada sitio.  
- No usar herramientas o métodos que los violen.  
- Revisar periódicamente las políticas de uso.

### 5.3 Acceso No Autorizado
Las prácticas OSINT se limitan a información pública y accesible sin vulnerar sistemas protegidos.  
- Está prohibido eludir mecanismos de seguridad o autenticación.  
- Cualquier intento de acceso no autorizado puede implicar responsabilidades penales.

### 5.4 Propiedad Intelectual
- Respetar las leyes de propiedad intelectual y derechos de autor.  
- Citar las fuentes en informes y análisis.  
- No reproducir contenido protegido sin permiso.

### 5.5 Difamación / Calumnia
- Basar los informes en datos verificables.  
- Evitar juicios de valor no comprobados.  
- Publicar información falsa puede acarrear sanciones legales.

---

## 6. Aspectos Éticos

### 6.1 Privacidad
Aunque la información sea pública, debe protegerse la **privacidad individual**.  
No divulgar datos personales que puedan causar daño o exposición indebida.

### 6.2 Contexto
Interpretar la información dentro de su contexto original.  
No alterar el sentido ni presentar los datos de forma engañosa.

### 6.3 Precisión
El trabajo OSINT requiere **verificación rigurosa**.  
Contrastar la información con múltiples fuentes confiables.

### 6.4 Sesgo
Ser consciente de los posibles sesgos personales o de las fuentes.  
Mantener una postura neutral durante el análisis.

### 6.5 No Abusar
El OSINT debe usarse únicamente con **fines legítimos y profesionales**.  
Prohibido usar la información para acosar, discriminar o manipular.

### 6.6 Impacto
Evaluar el posible impacto social, reputacional o emocional antes de difundir resultados.  
Priorizar siempre la **responsabilidad ética** sobre la exposición pública.
