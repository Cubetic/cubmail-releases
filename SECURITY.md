# Política de seguridad de Cubmail

Cubmail es un cliente de correo para Windows desarrollado por **Cubetic**. Si crees haber encontrado un fallo de
seguridad en Cubmail, te agradecemos que nos lo cuentes. Esta página explica cómo hacerlo, qué te responderemos y en
cuánto tiempo.

## Cómo avisarnos

Escríbenos a **info@cubetic.com** con el asunto **«Seguridad Cubmail»**.

**No lo publiques** en un *issue* de GitHub, en redes sociales ni en ningún otro sitio público hasta que lo hayamos
arreglado: así los usuarios no quedan expuestos mientras preparamos la solución.

Para que podamos estudiarlo cuanto antes, incluye si puedes:

- La versión de Cubmail (Archivo › Acerca de) y la de Windows.
- Qué ocurre y qué podría hacer alguien que lo aprovechara.
- Los pasos para reproducirlo y, si lo tienes, un ejemplo (un correo, un archivo o una captura).
- Si sabes que alguien lo está aprovechando ya.
- Cómo quieres que te citemos en el aviso de seguridad, o si prefieres no aparecer.

## Qué te responderemos y en cuánto tiempo

| Paso | Plazo máximo |
| --- | --- |
| Acuse de recibo | 2 días laborables |
| Primera valoración (si es un fallo de seguridad y su gravedad) | 5 días laborables |
| Arreglo publicado de un fallo **crítico** | 30 días |
| Arreglo publicado del resto de fallos | 90 días |

Te mantendremos informado de cómo avanza el arreglo y te avisaremos antes de publicarlo. Si un arreglo necesitara más
tiempo, te lo diremos y lo acordaremos contigo.

**Divulgación coordinada:** te pedimos que esperes a que el arreglo esté publicado, o a que pasen **90 días** desde tu
aviso, lo que ocurra antes, para hacer público el fallo. Si lo prefieres, publicaremos tu nombre en el aviso de
seguridad como agradecimiento.

## Si el fallo ya se está aprovechando

Si un fallo de Cubmail se está aprovechando de forma activa, o se produce un incidente grave que afecte a su
seguridad, Cubetic lo notifica a las autoridades europeas (ENISA y el CSIRT competente) en los plazos del Reglamento
(UE) 2024/2847 de Ciberresiliencia, e informa a los usuarios afectados y de las medidas que pueden tomar.

## Versiones con soporte

| Versiones | Soporte de seguridad |
| --- | --- |
| **1.x** (clientes) | Arreglos de seguridad gratuitos durante al menos **5 años** desde la publicación de cada versión |
| **0.x** (marcadas «técnicos» o «Pre-release») | Versiones de prueba internas de Cubetic, no destinadas a clientes |

Los arreglos de seguridad se publican como una nueva versión en este repositorio, en
[Releases](../../releases), y las notas de la versión indican qué fallo corrigen. Cubmail busca actualizaciones
automáticamente una vez al día, y cada descarga se comprueba con su huella SHA-256 antes de instalarse. Recomendamos
tener siempre instalada la última versión 1.x.

## Al investigar un fallo

Te pedimos que:

- Pruebes solo con tus propias cuentas, equipos y datos.
- No accedas, modifiques ni borres datos de otras personas, y si te encuentras con ellos sin querer, pares y nos avises.
- No interrumpas ni degrades servicios (sin pruebas de denegación de servicio ni envíos masivos).
- No uses ingeniería social, *phishing* ni ataques físicos contra Cubetic, sus clientes o sus trabajadores.

## Confidencialidad

Tratamos tu aviso y tus datos de contacto de forma confidencial y solo para gestionar el fallo.

*Última revisión: 20 de noviembre de 2026.*
