# MITRE ATT&CK® 

La Matriz de Mitre es una herramienta ampliamente utilizada en ciberseguridad para categorizar y clasificar tácticas, técnicas y procedimientos (TTP) utilizados por los actores de amenazas. Un APT (Amenaza Persistente Avanzada) es un tipo de ataque altamente sofisticado y dirigido, que generalmente es llevado a cabo por actores de amenazas con recursos significativos y objetivos específicos. 

Aquí tienes un ejemplo paso a paso del uso de la Matriz de Mitre con un APT ampliamente reconocido, como el grupo APT28, también conocido como Fancy Bear:

1. **Identificación del APT:** En este caso, tomamos el grupo APT28, conocido por sus actividades de ciberespionaje y por estar asociado con el gobierno ruso.

2. **Análisis de Información Pública:** Revisamos informes de seguridad, análisis de incidentes pasados y otras fuentes públicas para recopilar información sobre las tácticas, técnicas y procedimientos utilizados por el grupo APT28 en sus ataques.

3. **Mapeo de Tácticas, Técnicas y Procedimientos (TTP):** Utilizando la Matriz de Mitre, identificamos las tácticas y técnicas específicas empleadas por el grupo APT28. Por ejemplo:
   
   - **Táctica:** Acceso inicial (Initial Access)
     - **Técnica:** Spear Phishing (T1566.001)
     - **Descripción:** El grupo APT28 ha utilizado correos electrónicos de spear phishing para engañar a los usuarios y obtener acceso inicial a sistemas objetivo.

   - **Táctica:** Ejecución (Execution)
     - **Técnica:** Malware de Documentos (T1204.002)
     - **Descripción:** APT28 ha utilizado documentos maliciosos adjuntos en correos electrónicos de spear phishing para ejecutar malware en los sistemas de las víctimas.

   - **Táctica:** Persistencia (Persistence)
     - **Técnica:** Tareas programadas / Jobs de inicio (T1053.004)
     - **Descripción:** Una vez que obtienen acceso a un sistema, APT28 ha utilizado tareas programadas para mantener la persistencia en el sistema comprometido.

4. **Evaluación de Mitigaciones y Contramedidas:** Desarrollamos e implementamos medidas de seguridad para mitigar los riesgos asociados con las tácticas y técnicas identificadas. Por ejemplo:

   - Para abordar el riesgo de spear phishing, implementamos capacitación en concienciación de seguridad para empleados y utilizamos soluciones de filtrado de correo electrónico avanzadas para detectar y bloquear correos electrónicos maliciosos.

   - Para combatir el malware de documentos, utilizamos soluciones antivirus actualizadas y aplicamos políticas de restricción de ejecución de archivos en los sistemas.

   - Para prevenir la persistencia mediante tareas programadas, monitoreamos activamente las tareas programadas en los sistemas y aplicamos listas blancas de autorización para las tareas programadas permitidas.

5. **Monitoreo y Mejora Continua:** Implementamos sistemas de monitoreo de seguridad para detectar y responder rápidamente a posibles incidentes. También revisamos regularmente nuestras estrategias de mitigación y contramedidas para mejorar nuestra postura de seguridad contra amenazas como APT28.

Este ejemplo ilustra cómo se puede utilizar la Matriz de Mitre para comprender y mitigar las tácticas y técnicas empleadas por un APT ampliamente reconocido como APT28.

## REFERENCIAS.

[MITRE](https://attack.mitre.org/)

[EJEMPLO](https://natasec.com/que-es-mitre-attck-navigator-y-como-podemos-usarlo/)

[Navegador](https://mitre-attack.github.io/attack-navigator/)


## TALLER 

Desarrollar de manera individual el análisis de  la APT 28 ( https://attack.mitre.org/groups/G0007/ ) , de manera similar al anterior ejemplo.

Presentar informe en el espacio "Análisis APT 28".

