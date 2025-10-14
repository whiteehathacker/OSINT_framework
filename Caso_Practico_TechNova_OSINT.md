# Caso Práctico OSINT: TechNova Solutions

## 1. Planificación

### Definición de Objetivos

**Objetivo general:**  
Analizar la presencia digital de la empresa *TechNova Solutions* para detectar posibles indicios de fraude o actividades engañosas.

**Objetivos específicos:**  
- Verificar la legitimidad de su sitio web y dominios asociados.  
- Identificar redes sociales y comprobar autenticidad.  
- Analizar correos corporativos y su reputación.  
- Evaluar coherencia entre presencia digital y actividad comercial declarada.

### Alcance

- **Temporal:** Enero 2023 – Octubre 2025.  
- **Geográfico:** Latinoamérica y España.  
- **Temático:** Legitimidad corporativa, identidad digital, reputación y huella en línea.  

Un alcance bien definido evita recopilar información innecesaria o ilegal.

### Requerimientos de Información

- **Datos requeridos:** cuantitativos (fechas, registros, IPs) y cualitativos (contenido, contexto, reputación).  
- **Criterios:** actualidad, fiabilidad, veracidad.  
- **Fuentes:** institucionales, académicas, corporativas, redes sociales y bases de datos OSINT.

### Consideraciones Legales y Éticas

- Cumplir con el **RGPD** y las leyes nacionales de protección de datos.  
- No obtener información privada ni acceder a sistemas restringidos.  
- Transparencia en la recolección y uso de datos.

### Selección de Fuentes

- **Primarias:** Sitios web, redes sociales oficiales, registros [WHOIS Lookup](https://whois.domaintools.com/).  
- **Secundarias:** Artículos periodísticos, bases de datos corporativas.  
- **Terciarias:** Compilaciones, resúmenes o reportes de terceros.  

Las fuentes se evalúan por **credibilidad, actualidad, precisión y objetividad**.

---

## 2. Recolección de Información

### Ejecución

Se recopila la información de las fuentes previamente identificadas, documentando cada paso (fecha, fuente, enlace, descripción, nivel de fiabilidad).

### Métodos

- **Pasivos:** Búsquedas avanzadas, revisión de redes sociales, [WHOIS Lookup](https://whois.domaintools.com/).  
- **Activos:** Validación directa mediante [Hunter.io](https://hunter.io), [EmailRep.io](https://emailrep.io), entre otras.

### Herramientas Utilizadas

| Categoría | Herramienta | Descripción |
|------------|-------------|-------------|
| Email | [Hunter.io](https://hunter.io), [Have I Been Pwned](https://haveibeenpwned.com) | Verifica correos asociados a un dominio y filtraciones. |
| IP | [Shodan](https://www.shodan.io), [IPinfo.io](https://ipinfo.io) | Busca dispositivos conectados y ubicación IP. |
| Web | [WHOIS Lookup](https://whois.domaintools.com), [OpenCorporates](https://opencorporates.com) | Consulta registros de dominios y empresas. |
| Redes Sociales | [Sherlock](https://github.com/sherlock-project/sherlock), [Maigret](https://github.com/soxoj/maigret) | Rastrea perfiles por alias en múltiples plataformas. |
| Imágenes | [TinEye](https://tineye.com), [ExifTool](https://exiftool.org) | Analiza metadatos y fuentes de imágenes. |
| Geolocalización | [Google Maps](https://maps.google.com), [GeoNames](https://www.geonames.org) | Verifica direcciones o ubicaciones asociadas. |

### Organización

Se emplea **Maltego** para representar entidades y relaciones (dominios, IPs, correos, redes) en forma de grafo, facilitando la identificación de vínculos entre elementos investigados.

### Verificación

- Se comparan datos en distintas fuentes (**cross-validation**).  
- Se comprueba coherencia temporal y contextual.  
- Se analizan metadatos y procedencia de imágenes con [ExifTool](https://exiftool.org) y [TinEye](https://tineye.com).  
- Se clasifican datos según su nivel de credibilidad (**alta**, **media**, **baja**).

**Ejemplo de verificación:**  
- El dominio *technova-solutions.com* fue creado hace 3 meses, pero la empresa afirma existir hace 5 años.  
- Correos corporativos filtrados en *Have I Been Pwned*.  
- Imágenes del sitio web son tomadas de bancos de imágenes libres.  
- En redes sociales se detectan seguidores falsos y fechas incoherentes.

---

## 3. Análisis y Procesamiento

### Procesamiento

- Limpieza y normalización de datos con [OpenRefine](https://openrefine.org).  
- Eliminación de duplicados y corrección de errores.

### Interpretación

- Identificación de inconsistencias entre la información pública y la actividad declarada.  
- Se infiere que la empresa presenta una huella digital artificial.

### Correlación

- En **Maltego**, se vincula el correo *contact@technova-solutions.com* con otra empresa (*NovaTech Global*) registrada en Panamá, compartiendo la misma IP.  
- Esto sugiere una **infraestructura digital duplicada o fraudulenta**.

### Evaluación

- **Fuentes gubernamentales:** alta fiabilidad.  
- **Publicaciones en foros o redes:** baja fiabilidad.  
- **Nivel de riesgo estimado:** alto.

### Síntesis

Los hallazgos apuntan a que *TechNova Solutions* es una empresa de fachada creada recientemente con posible intención fraudulenta.  
El análisis cruzado de fuentes y metadatos permitió construir una narrativa coherente y fundamentada.

---

## 4. Diseminación de Resultados

### Comunicación

El informe final se redacta en **Microsoft Word**, con lenguaje claro y visualizaciones extraídas de **Maltego**.  
Se enfatizan hallazgos clave, riesgos y recomendaciones.

### Accionable

- Se recomienda **no establecer relaciones comerciales** con la empresa.  
- Notificar a **autoridades de consumo** y registrar el dominio en listas de vigilancia.

### Formato

- **Dashboard** en [Power BI](https://powerbi.microsoft.com) para mostrar redes y correlaciones.  
- **Presentación** en *PowerPoint* para exposición ejecutiva.

### Feedback

El informe se distribuye a los equipos de seguridad y se recopila retroalimentación mediante [Google Forms](https://forms.google.com) y *Notion Comments*.

---

## 5. Aspectos Legales y Éticos

### Aspectos Legales

- Cumplimiento del **RGPD** y leyes de protección de datos.  
- Prohibición de acceso a sistemas protegidos.  
- Respeto a la **propiedad intelectual** y **términos de servicio**.  
- Citar siempre las fuentes y evitar contenido protegido.  
- Basar conclusiones en datos verificables.

### Aspectos Éticos

- Proteger la **privacidad individual**, incluso si los datos son públicos.  
- No alterar el contexto ni manipular los resultados.  
- Verificar y contrastar información antes de difundirla.  
- Mantener una postura **neutral y objetiva**.  
- Evaluar el **impacto social y reputacional** antes de publicar resultados.

---

## 6. Conclusión

La investigación OSINT permitió descubrir que *TechNova Solutions* era una **fachada digital** creada recientemente con fines posiblemente fraudulentos.  
La **trazabilidad de la información**, la **verificación cruzada** y el **análisis visual en Maltego** fueron claves para determinar la falta de legitimidad de la empresa, cumpliendo en todo momento con los principios **legales y éticos** del análisis OSINT.
