# proyecto-seguridad-en-redes-corporativas-pedro-y-jose
proyecto-seguridad-en-redes-corporativas-pedro-y-jose created by GitHub Classroom


Proyecto Integral de Seguridad y Alta Disponibilidad
Seguridad en entornos empresariales.
Sprint 3 - Copias de seguridad

US4: (fecha tope 4 noviembre) CA 2. Copias de seguridad. Actualmente, existe una gran variedad de soluciones backup en el mercado. Es muy importante elegir un software que nos aporte tranquilidad y se ajuste a las necesidades que tenemos, por ello, lo principal es asegurarnos que el programa que seleccionamos nos ofrece la fiabilidad y cubre nuestras necesidades, por tanto, es imprescindible probarlo bien, y comprobar la restauración de las copias es correcta. 

Probablemente, en la actualidad el software que está utilizando la mayoría de las medianas y grandes empresas, es la herramienta Veam backup Community Edition (si te interesa puedes ojear este tutorial). Debido a su complejidad, y la cantidad de recursos que utiliza, descartaremos su uso en esta ocasión.

Duplicati, aunque no es una herramienta tan potente, es mucho más liviana y sencilla de utilizar, por tanto, aprovecharemos esta herramienta para cubrir las necesidades de nuestro proyecto.
Entre sus principales características podemos destacar:
Duplicati funciona con protocolos estándar como FTP, SSH, WebDAV, así como con servicios populares como Backblaze B2 , Tardigrade , Microsoft OneDrive, Amazon S3, Google Drive, box.com, Mega, hubiC y muchos otros .
Copia de seguridad de archivos y carpetas con fuerte encriptación AES-256. Ahorre espacio con copias de seguridad incrementales y deduplicación de datos. Ejecute copias de seguridad en cualquier máquina a través de la interfaz basada en web o mediante la interfaz de línea de comandos. Duplicati tiene un programador incorporado y un actualizador automático.
Duplicati es software libre y de código abierto. Puede utilizar Duplicati de forma gratuita incluso con fines comerciales. El código fuente tiene licencia bajo LGPL. Duplicati se ejecuta en Windows, Linux, MacOS.
Duplicati fue diseñado para realizar copias de seguridad en línea desde cero. No solo es eficiente con los datos, sino que también maneja los problemas de la red muy bien. Por ejemplo, las copias de seguridad interrumpidas se pueden reanudar y Duplicati prueba el contenido de las copias de seguridad periódicamente. De esa manera, las copias de seguridad rotas en sistemas de almacenamiento corruptos pueden detectarse antes de que sea demasiado tarde.

Por ello, se solicita realizar dos copias de seguridad diferente:
La copia 1 llamada “copia documentos”, tendrá las siguientes características:
copia cifrada con origen en la carpeta Documentos del servidor y destino de tu cuenta de Google Drive. 
Para esta carpeta solo podemos aceptar la pérdida de datos de máximo 1 hora de tiempo, y se genera información en esta carpeta de lunes a viernes. 
Ten en cuenta que además de configurar la copia, es imprescindible comprobar la recuperación. Por ello se solicita una batería de pruebas con el fin de conocer el programa y comprobar que funciona correctamente.

La copia 2 llamada “copia imágenes”, tendrá las siguientes características:
Copia sin cifrar con origen en la carpeta Imágenes del servidor y destino tu cuenta de Google Drive. 
Para esta carpeta solo podemos aceptar la pérdida de datos de máximo 1 día de tiempo, y se genera información en esta carpeta de lunes a domingo. 
Ten en cuenta que además de configurar la copia, es imprescindible comprobar la recuperación. Por ello se solicita una batería de pruebas con el fin de conocer el programa y comprobar funciona correctamente.

US 5 Recuperación de datos perdidos.
Lectura recomendada 2	
Instala dos herramientas de recuperación estilo Recuva, y realiza una prueba para comprobar la recuperación de los datos con ambos. Para ello, utiliza una unidad extraíble y comprueba los resultados.	
¿Has podido recuperar los datos cuando estos aparentemente estaban 	eliminados? 		
Si utilizamos una unidad extraíble y realizamos el "formateo 		rápido" ofrecido por Windows, ¿podemos recuperar la 		información con ambas herramientas? 		
¿Y si hacemos un formateo completo?	
Prueba la siguiente aplicación de sobrescritura, y comprueba si puedes 	recuperar la información del dispositivo con el software anterior. 	
