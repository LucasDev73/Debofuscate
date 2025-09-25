🛡️ Phishing HTML JavaScript Deobfuscator

Este repositorio contiene un script en Python para desofuscar código JavaScript malicioso ofuscado, comúnmente utilizado en ataques de phishing. Está diseñado para campañas que usan archivos HTML con objetos de mapeo numérico (como el objeto dpsh).
🔍 Descripción

En un análisis reciente de phishing distribuido vía WhatsApp, se detectó un archivo HTML altamente ofuscado que generaba contenido fraudulento simulando una actualización oficial de Adobe Acrobat Reader. Este contenido soporta múltiples idiomas, realiza redirecciones maliciosas y utiliza plataformas legítimas como Google Drive para alojar documentos falsos.

El script permite interpretar y recuperar el código original, convirtiendo valores codificados en Unicode a texto legible, facilitando análisis forense y detección.
⚙️ Uso

   Clonar este repositorio.

   Colocar el archivo HTML ofuscado en la carpeta raíz (o especificar la ruta en el comando).

   Ejecutar el script:

    python deobfuscator.py archivo_ofuscado.html

  Revisar el archivo desofuscado generado para análisis.

✨ Beneficios

  Simplifica análisis manual complejo.

  Mejora la efectividad en detección y respuesta ante phishing.

  Facilita la generación de indicadores de compromiso (IoCs).

⚠️ Disclaimer

Este código es para fines educativos y de análisis únicamente. El autor no se responsabiliza por usos indebidos.
📁 Ejemplo Visual
mejora esto y añade iconos Phishing HTML JavaScript Deobfuscator

Este repositorio contiene un script en Python desarrollado para desofuscar código JavaScript malicioso ofuscado empleado en ataques de phishing, específicamente en campañas que involucran archivos HTML con objetos de mapeo numérico (como el objeto dpsh).
Descripción

En un reciente análisis de phishing distribuido vía WhatsApp, se detectó un archivo altamente ofuscado que generaba contenido HTML que simulaba una actualización oficial de Adobe Acrobat Reader, con soporte para múltiples idiomas, redirecciones maliciosas y uso de plataformas legítimas como Google Drive para alojar documentos fraudulentos.

Este script facilita la interpretación y recuperación del código original para análisis forense y detección, transformando valores codificados en Unicode a texto legible.
Uso
    Clonar repositorio 
    Colocar archivo HTML ofuscado en la carpeta raíz o especificar ruta
    Ejecutar el script:

    python deobfuscator.py archivo_ofuscado.html

  Revisar archivo desofuscado generado para análisis.

Beneficios

   Simplifica análisis manual complejo.

   Mejora efectividad de detección y respuesta.

   Facilita generación de indicadores de compromiso (IoCs).

Disclaimer

Este código es para fines educativos y de análisis. El autor no se responsabiliza por usos indebidos.

HTML ofuscado:

<img width="750" height="789" alt="imagen" src="https://github.com/user-attachments/assets/a0840b86-bd26-4ad0-96d0-adfeb01c61ad" />

HTML deobfuscado:

<img width="1176" height="711" alt="imagen" src="https://github.com/user-attachments/assets/0dc1756c-c1f1-4340-8b3d-197e132cd8f3" />
