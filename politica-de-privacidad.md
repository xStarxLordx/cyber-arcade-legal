---
title: Política de Privacidad — CYBER_ARCADE
---

# Política de Privacidad — CYBER_ARCADE

**Última actualización:** 26 de julio de 2026

Esta Política de Privacidad describe cómo **CYBER_ARCADE** ("la App"), desarrollada por
Francisco Lopez ("nosotros"), trata la información cuando usas la aplicación. Nos tomamos en
serio tu privacidad, especialmente porque la App tiene un público general que puede incluir
menores de edad.

## 1. Resumen

CYBER_ARCADE **no tiene cuentas de usuario, no tiene servidores propios y no envía tus
partidas, récords ni ajustes a ningún sitio**: todo eso vive únicamente en tu dispositivo.

La única excepción es la **publicidad**: la versión Android de la App muestra anuncios de
**Google AdMob**, y para ello el SDK de Google recoge en tu dispositivo ciertos datos técnicos
y publicitarios (incluido el identificador de publicidad). La sección 3 lo detalla.

| | |
|---|---|
| Datos que se quedan en tu dispositivo | ajustes, récords e iniciales, tickets y premios, misiones, diarias y racha, partidas guardadas |
| Datos que salen del dispositivo | únicamente los que recoge el SDK de anuncios de Google (sección 3) |
| Cuentas o registro | no existen |
| Servidores del Desarrollador | no existen |
| Publicidad | sí, en la versión Android (las versiones web y de escritorio no muestran anuncios) |

## 2. Datos que se guardan solo en tu dispositivo

| Dato | Dónde se guarda | ¿Se transmite a algún servidor? |
|---|---|---|
| Ajustes (tema visual, idioma, sonido, música, vibración, controles, calidad gráfica) | almacenamiento local del dispositivo | No |
| Récords locales (puntuación, nivel, fecha) e iniciales de 3 letras | almacenamiento local del dispositivo | No |
| Tickets acumulados y premios cosméticos desbloqueados | almacenamiento local del dispositivo | No |
| Progreso de misiones, misiones diarias y racha de días | almacenamiento local del dispositivo | No |
| Partidas guardadas (para "continuar") | almacenamiento local del dispositivo | No |
| Contadores internos de frecuencia de anuncios | almacenamiento local del dispositivo | No |

Estos datos permanecen exclusivamente en tu dispositivo, no se sincronizan en la nube, no se
asocian a tu identidad real y desaparecen si desinstalas la App o borras sus datos desde los
ajustes del sistema operativo. El Desarrollador no tiene acceso a esta información en ningún
momento.

## 3. Publicidad (Google AdMob)

La App integra el SDK de **Google AdMob** y muestra anuncios en dos situaciones, **nunca
durante una partida en curso**:

- **Anuncio con recompensa**, siempre opcional y a petición tuya: para continuar después de
  perder, o para duplicar los tickets ganados en la partida. Se te pregunta antes de mostrarlo
  y puedes rechazarlo sin perder nada de lo que ya tenías.
- **Anuncio intersticial**, ocasional, al salir de la pantalla de fin de partida — es decir,
  después de que hayas visto tu puntuación, nunca tapándola.

Para mostrar y medir esos anuncios, **Google** recoge y procesa en tu dispositivo los
siguientes tipos de datos:

- **Identificador de publicidad** (Google Advertising ID / AAID) y, en su ausencia,
  identificadores equivalentes proporcionados por el sistema operativo. Por este motivo la App
  declara el permiso `com.google.android.gms.permission.AD_ID`.
- **Datos de dispositivo**: modelo, sistema operativo, idioma, zona horaria, resolución de
  pantalla.
- **Datos de red**: dirección IP (usada para estimación de ubicación aproximada), operador
  móvil, tipo de conexión.
- **Datos de interacción con anuncios**: impresiones, clics, tiempo de visualización.
- **Datos de uso de la App** agregados para personalización publicitaria, únicamente cuando has
  dado tu consentimiento donde este es exigible (ver 3.1) o no lo has desactivado donde la
  plataforma lo permite.

Estos datos son recogidos y tratados por **Google** conforme a sus propias políticas, no por el
Desarrollador: nosotros no recibimos ni almacenamos ninguno de ellos, solo vemos informes
agregados de ingresos en el panel de AdMob. Puedes consultar:

- Política de Privacidad de Google: <https://policies.google.com/privacy>
- Cómo usa Google los datos de las apps que usan sus servicios:
  <https://policies.google.com/technologies/partner-sites>
- Configuración de anuncios de Google: <https://adssettings.google.com>

### 3.1 Consentimiento en el Espacio Económico Europeo (EEE), Reino Unido y Suiza (RGPD)

Para usuarios ubicados en el EEE, Reino Unido y Suiza, la App utiliza el **User Messaging
Platform (UMP) de Google** — una plataforma de gestión de consentimiento (CMP) certificada por
Google — que:

- Muestra el formulario de consentimiento **antes** de la primera solicitud de anuncio, para
  que decidas sobre el uso de identificadores de publicidad y los anuncios personalizados,
  conforme al **RGPD** y a la directiva ePrivacy.
- Sirve anuncios no personalizados ("contextuales") si no consientes el tratamiento de datos
  para personalización.
- Registra y respeta tu decisión. **Puedes revisarla, cambiarla o retirarla en cualquier
  momento** desde **AJUSTES → PRIVACIDAD DE ANUNCIOS** dentro de la App (esta opción aparece
  únicamente para los usuarios de las regiones en las que la normativa la exige).

### 3.2 Menores de edad y familias (COPPA / Google Play Families)

CYBER_ARCADE es una app de público general y **no está dirigida a menores de 13 años**, aunque
al tratarse de juegos arcade sin contenido sensible es razonable que la usen menores bajo
supervisión de un adulto. Por ello:

- Todas las solicitudes de anuncios se realizan con la clasificación de contenido **apta para
  todos los públicos** ("G" / *General audiences*), lo que excluye categorías de anuncios para
  adultos.
- Si en algún momento la App se declarase dirigida (total o parcialmente) a menores en Google
  Play Console, se activaría además el etiquetado **"Tagged for Child-Directed Treatment"**
  conforme a **COPPA** (EE. UU.) y a las políticas del **Programa Familias de Google Play**, lo
  que restringe la personalización publicitaria para esos usuarios.
- No solicitamos, de forma intencionada, información personal identificable a menores de edad
  (nombre real, correo, ubicación precisa, etc.). Las "iniciales" del récord son un campo libre
  de 3 caracteres, almacenado solo localmente, y no se pide ni se recomienda usar un nombre real.
- Si un padre, madre o tutor considera que un menor ha proporcionado datos personales
  identificables, puede contactarnos (sección 9). Dado que no existe almacenamiento en servidor,
  la eliminación se resuelve borrando los datos locales de la App en el dispositivo.

## 4. Notificaciones (recordatorio diario)

La App puede enviarte **una notificación local al día** recordándote que tus misiones diarias
se han renovado o que tienes una racha en curso.

- Es **opcional y está desactivada por defecto**: se activa desde AJUSTES, y es entonces cuando
  se te pide el permiso de notificaciones de Android.
- Es **100% local**: la programa tu propio dispositivo. No hay notificaciones push, no
  interviene ningún servidor y no se recoge ni se envía ningún dato para generarla.
- Puedes desactivarla cuando quieras desde AJUSTES o desde los ajustes de notificaciones de
  Android.

## 5. Compras dentro de la aplicación

**A fecha de esta versión, CYBER_ARCADE no incluye compras dentro de la aplicación.** Todos los
premios del catálogo (temas, trofeos, pistas de música y demás elementos cosméticos) se
obtienen jugando, con los tickets que se ganan en las partidas.

Si en el futuro se añade alguna compra (por ejemplo, una compra única para quitar los anuncios),
se procesará íntegramente a través de **Google Play Billing**:

- El Desarrollador **no recibe ni almacena** datos de tarjetas ni de cuentas bancarias.
- Google puede compartir con el Desarrollador información no sensible de la transacción (que la
  compra se realizó, un identificador de compra, el importe y la moneda) con fines de validación
  y soporte.
- Esta política y la declaración de Seguridad de los Datos de Google Play se actualizarían antes
  de activar esa función.

## 6. Datos que el Desarrollador NO recoge

Para que quede explícito, CYBER_ARCADE no recoge en ningún caso:

- Nombre real, correo electrónico o teléfono.
- Ubicación precisa (GPS).
- Contactos, fotos, archivos u otros datos del dispositivo.
- Datos de salud, biométricos o financieros.
- Ningún dato en servidores propios del Desarrollador (no operamos ningún backend).

## 7. Conservación y eliminación de datos

- Los datos locales (ajustes, récords, tickets, progreso) se conservan mientras la App esté
  instalada. Puedes eliminarlos en cualquier momento desde **Ajustes de Android → Aplicaciones →
  CYBER_ARCADE → Almacenamiento → Borrar datos**, o desinstalando la App. Esa acción es
  definitiva: no existe copia en la nube desde la que restaurarlos.
- Los datos tratados por Google con fines publicitarios se rigen por los plazos de conservación
  de Google. Puedes restablecer o eliminar tu identificador de publicidad desde **Ajustes de
  Android → Privacidad → Anuncios**.

## 8. Tus derechos

Dependiendo de tu jurisdicción (por ejemplo, el RGPD en la UE/EEE, o la Ley Estatutaria 1581 de
2012 de protección de datos personales en Colombia), puedes tener derecho a acceder, rectificar,
eliminar o limitar el tratamiento de tus datos, así como a oponerte a la personalización de
anuncios.

- Los datos almacenados localmente los controlas tú directamente (ver sección 7).
- Sobre el tratamiento que realiza Google (AdMob), ejerce tus derechos ante Google en
  <https://myaccount.google.com/privacy> o en <https://adssettings.google.com>; y, en el EEE,
  Reino Unido y Suiza, gestiona tu consentimiento desde AJUSTES → PRIVACIDAD DE ANUNCIOS en la
  propia App.
- Para cualquier otra consulta, escríbenos a la dirección de contacto de abajo.

## 9. Contacto

Si tienes preguntas sobre esta Política de Privacidad, puedes contactarnos en:

**Correo electrónico:** flopez@haipriori.com

## 10. Cambios en esta política

Podemos actualizar esta Política de Privacidad cuando cambien las funciones de la App (por
ejemplo, al activar compras). Publicaremos la versión vigente en esta misma URL y actualizaremos
la fecha de la parte superior del documento. Te recomendamos revisarla periódicamente.
