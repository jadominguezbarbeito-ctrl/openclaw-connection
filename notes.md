Decisiones de configuración tomadas y problemas encontrados

Decisiones:

- Cuenta de Google de prueba y no la personal.
- La autorización de Zapier hecha desde la terminal con un túnel SSH, porque por el chat fallaba.

Problemas:

- Falta de memoria en el VPS (1 GB) con VS Code conectado: el gateway no arrancaba.
- Fallos del modelo y sesión rota por escribir mientras Goat trabajaba. Se resolvió con /new y un solo mensaje completo.
- Goat intentó usar un plugin de Google en vez de Zapier, y hubo que indicárselo.
- El evento se creó a las 11:00 en vez de a las 10:00: Zapier usa la hora UTC y no la de España.
