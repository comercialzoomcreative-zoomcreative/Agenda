# Mi Agenda

Aplicación personal de **agenda y seguimiento de ventas** que funciona **100% sin internet**, con base de datos **SQLite** local. Se abre con doble clic en cualquier navegador (Edge o Chrome) y no necesita instalar nada.

## Cómo usarla

1. Descarga o copia la carpeta `AGENDA` (los 3 archivos juntos).
2. Haz doble clic en **`index.html`**.
3. Se abre en tu navegador y empieza a usarla de inmediato.

> No borres ni renombres `sql-wasm.js` ni `sql-wasm-b64.js`; deben estar en la misma carpeta que `index.html`.

## Funciones

- **Dashboard**: cumplimiento diario y semanal (porcentaje y horas), gráficas de 14 días, próximas semanas, reuniones y recordatorios próximos.
- **Registro diario**: marca tus actividades (cumplido sí/no), horas dedicadas y notas.
- **Skills / Actividades**: actividades con meta semanal (veces y horas) y **categorías con color**.
- **Reuniones**: fecha, hora, tema, lugar, estado, participantes (nombre y cargo) y **cliente asociado**.
- **Clientes**: lista de clientes con **color**, persona de contacto, correo y teléfono.
- **Ventas**: pipeline de negociación con estados y probabilidad, **"a quién hay que llamar"**, historial de seguimiento por venta, **resumen mensual con gráfica** (ganadas/perdidas) y **exportar a CSV** (Excel).
- **Contactos**: directorio de personas (cargo, empresa, correo, teléfono).
- **Recordatorios y alarmas**: avisos con sonido, repetición diaria/semanal y **notificación de Windows**.
- **Planificación**: metas semanales y cumplimiento de semanas pasadas, actuales y futuras.

## Horario laboral

La agenda está configurada de **lunes a viernes, de 8:00 a 17:00**:

- Reuniones, recordatorios y llamadas de ventas solo se pueden agendar en ese rango.
- Las alarmas y recordatorios **solo suenan dentro del horario laboral** (no te molestan de noche ni en fin de semana).
- Los recordatorios diarios saltan automáticamente los fines de semana.

## Respaldo y seguridad de datos

- Todo se guarda automáticamente en el navegador (IndexedDB) y en **SQLite**.
- **Respaldo automático**: pulsa el botón *Respaldo automático*, elige dónde guardar el archivo `.sqlite` y cada cambio se guarda ahí solo. Recomendado en una carpeta sincronizada (OneDrive, Google Drive, Dropbox).
- Puedes exportar/importar la base de datos en cualquier momento (botones *Exportar .sqlite* / *Importar*).
- Tus datos personales (reuniones, ventas, clientes) **no se guardan en GitHub**: solo se sube el código de la aplicación.

## Detalles técnicos

- Motor de base de datos: **SQLite** (SQL.js), incluido localmente.
- Sin servidores, sin conexión externa, sin publicidad.
- Compatible con Chrome y Edge (Windows).
- Un solo archivo de código: `index.html` (interfaz y lógica), más el motor SQLite.

---

Hecho con dedicación para uso personal y de negocio.
