# Política de privacidad: Calendario lunar

**Fecha de entrada en vigor:** 26 de noviembre de 2026

Idiomas: [English](privacy.html) · [Български](privacy.bg.html) · [Deutsch](privacy.de.html) · **Español**

Esta política explica qué información trata la aplicación para Android **Calendario lunar** (en búlgaro, «Лунен календар»; paquete `com.stoyanov.dev.android.moon`, versión 4.0 y posteriores; las versiones anteriores se publicaron como «Moon Phases & Sky Events»). La aplicación la desarrolla Zdravko Stoyanov, desarrollador independiente («nosotros»), que es el responsable de la aplicación.

Si hay diferencias entre las versiones de idioma, prevalece la [versión en inglés](privacy.html).

## Resumen

- La aplicación **no tiene cuentas, inicio de sesión, analítica, informes de errores ni servidores propios**. No recibimos ninguno de tus datos personales.
- Todos los cálculos de la Luna, el Sol y el cielo se hacen **sin conexión, en tu teléfono**.
- Tu lugar (ciudad o coordenadas) y tus ajustes se guardan **solo en tu dispositivo** y están excluidos de la copia de seguridad en la nube de Android.
- El acceso a la ubicación es **opcional y aproximado**, y se usa una sola vez cuando tocas «Usar mi ubicación». Tu ubicación no se nos envía ni se pasa a los anuncios.
- Las notificaciones se programan **localmente en el teléfono**; no hay servidor de notificaciones push.
- La aplicación muestra **anuncios nativos de Google AdMob**, marcados como «Anuncio». Google puede recopilar datos del dispositivo (como el ID de publicidad y la dirección IP) para mostrar y medir anuncios. Donde es obligatorio (por ejemplo, en el EEE, el Reino Unido y Suiza), primero pedimos tu consentimiento con la herramienta de consentimiento de Google.
- No vendemos datos.

## 1. Información guardada en tu dispositivo

La aplicación guarda sus ajustes en su almacenamiento privado del teléfono:

- tu lugar: una ciudad de la lista integrada o coordenadas (redondeadas a 0,01°, aproximadamente 1 km) y una zona horaria;
- tus preferencias: idioma, tema, imagen de la Luna, qué fenómenos celestes y consejos tradicionales mostrar;
- tus opciones de notificaciones (cuáles y a qué hora) y la lista de notificaciones programadas en el dispositivo;
- si has terminado la introducción.

Estos ajustes están **excluidos de la copia de seguridad en la nube de Android y de la transferencia a otro dispositivo**, así que se quedan solo en este teléfono. La aplicación no los envía a ningún sitio y no tenemos forma de leerlos.

## 2. Información que recopilamos

**Ninguna.** La aplicación no nos envía ningún dato. No pide tu nombre, correo electrónico, contactos, fotos ni ninguna otra información personal. La lista de ciudades y todos los datos astronómicos forman parte de la aplicación, por lo que buscar una ciudad no usa internet.

### Ubicación (opcional)

Puedes fijar tu lugar de tres formas: elegir una ciudad de la lista integrada, introducir coordenadas a mano o tocar **«Usar mi ubicación»**. Solo en este último caso la aplicación pide a Android la **ubicación aproximada** (`ACCESS_COARSE_LOCATION`). No pide la ubicación precisa ni la ubicación en segundo plano.

Si lo permites, la aplicación obtiene tu posición aproximada una sola vez, mientras está abierta, la redondea a 0,01° y la guarda en los ajustes descritos arriba. Solo se usa para calcular la salida y la puesta de la Luna y otras horas para tu lugar. La aplicación **no envía tu ubicación ni a nosotros ni a nadie, y no la pasa a los anuncios.** Puedes denegar el permiso y seguir usando la aplicación con una ciudad o coordenadas.

### Notificaciones (opcional)

Si activas las notificaciones (fases de la Luna, eclipses, conjunciones de planetas, lluvias de meteoros, días favorables), la aplicación pide permiso para mostrar notificaciones (`POST_NOTIFICATIONS`, Android 13+). Las notificaciones se calculan y programan **en el dispositivo**; la aplicación también usa `RECEIVE_BOOT_COMPLETED` para restaurarlas tras reiniciar el teléfono. No se envía ningún dato para las notificaciones.

## 3. Anuncios: Google AdMob y consentimiento de Google

La aplicación incluye kits de desarrollo de software (SDK) de Google. Estos SDK envían datos **directamente a Google, no a nosotros**. Cómo trata Google esos datos se describe en la [Política de privacidad de Google](https://policies.google.com/privacy?hl=es) y en [Cómo utiliza Google la información de sitios web o aplicaciones que usan sus servicios](https://policies.google.com/technologies/partner-sites?hl=es).

### Google AdMob (Google Mobile Ads SDK)

La aplicación muestra como máximo un pequeño anuncio nativo por pantalla, integrado en el contenido y marcado como «Anuncio». No hay anuncios a pantalla completa ni anuncios en la introducción o en Ajustes. Para mostrar, limitar y medir los anuncios y prevenir el fraude, según la propia información de Google, el SDK recopila:

- la **dirección IP** del dispositivo, que puede usarse para estimar tu ubicación general;
- **interacciones con anuncios y con la aplicación**, como aperturas de la aplicación, toques y visualizaciones de anuncios;
- **información de diagnóstico** sobre el rendimiento de la aplicación y del SDK;
- **identificadores del dispositivo**, como el ID de publicidad de Android y el ID del conjunto de aplicaciones.

La aplicación solo añade a las solicitudes de anuncios unas pocas palabras clave fijas (luna, calendario, jardín); no añade tu ubicación ni ninguna otra información personal. Google indica que estos datos se cifran en tránsito. Los anuncios pueden ser personalizados o no personalizados según tu consentimiento y los ajustes del dispositivo. Puedes restablecer o eliminar tu ID de publicidad, o desactivar los anuncios personalizados, en Android **Ajustes > Privacidad > Anuncios** (el menú exacto depende del teléfono).

### Google User Messaging Platform (consentimiento)

Si estás en el Espacio Económico Europeo, el Reino Unido o Suiza (o en otra región donde Google lo exija), la aplicación muestra el formulario de consentimiento de Google antes de solicitar cualquier anuncio. Los anuncios solo se solicitan cuando la herramienta de consentimiento lo permite. Según tu elección, Google muestra anuncios personalizados, no personalizados o limitados. El SDK de Google guarda tu elección en el dispositivo. Para ello, el SDK envía a Google algunos datos del dispositivo (como la dirección IP e identificadores del dispositivo o la aplicación).

Puedes cambiar tu elección en cualquier momento: abre **Ajustes** en la aplicación y, en **«Anuncios y privacidad»**, toca **«Ajustes de privacidad»**. Esta opción aparece siempre que la herramienta de consentimiento de Google indique que es necesaria en tu región.

## 4. Base jurídica (EEE/Reino Unido)

Nosotros no recopilamos datos personales. El tratamiento descrito en la sección 3 lo realiza Google. Cuando la publicidad personalizada requiere consentimiento, se pide mediante el formulario de Google y puedes retirarlo en cualquier momento como se indica arriba. Los anuncios no personalizados pueden seguir usando datos para fines como limitar la frecuencia, prevenir el fraude y medir, según describe Google. La ubicación en tu dispositivo solo se usa porque tú lo has pedido (con «Usar mi ubicación»).

## 5. Cesión y venta de datos

No vendemos, alquilamos ni compartimos tus datos personales: no tenemos ninguno. Los datos que recopilan los SDK publicitarios de Google los recopila Google, como se describe en la sección 3.

## 6. Menores

La aplicación es un calendario lunar para el público general. **No está dirigida a menores de 13 años** y no recopilamos a sabiendas información personal de menores. Si crees que un menor usa la aplicación, un padre, madre o tutor puede desactivar los anuncios personalizados en los ajustes del dispositivo o contactarnos (sección 10).

## 7. Conservación de los datos

- Los ajustes y tu lugar permanecen en el dispositivo hasta que los borres (ver sección 8).
- Los datos que recopila Google se conservan según las políticas de Google; consulta [Cómo conserva Google los datos](https://policies.google.com/technologies/retention?hl=es).

## 8. Tus opciones y eliminación de datos

- **Borrar los datos de la aplicación:** desinstala la aplicación o ve a Android **Ajustes > Aplicaciones > Calendario lunar > Almacenamiento > Borrar datos**. Así se borran tu lugar, los ajustes y las notificaciones programadas. Como no se incluyen en copias de seguridad, no queda nada en nuestro poder ni en tu copia de Google.
- **Ubicación:** deniega o revoca el permiso de ubicación cuando quieras en los ajustes de Android; usa una ciudad o coordenadas en su lugar.
- **Notificaciones:** desactívalas en los Ajustes de la aplicación o en los ajustes de Android.
- **Consentimiento para anuncios:** cámbialo con **«Ajustes de privacidad»** en los Ajustes de la aplicación (ver sección 3).
- **ID de publicidad:** restablécelo, elimínalo o desactiva los anuncios personalizados en los ajustes de Android.
- **Datos que guarda Google:** consulta los [controles de privacidad de Google](https://myaccount.google.com/data-and-privacy?hl=es).

Según el RGPD, tienes derecho de acceso, rectificación, supresión y portabilidad de tus datos personales, a limitar el tratamiento u oponerte a él, a retirar tu consentimiento y a presentar una reclamación ante una autoridad de protección de datos. Como no guardamos datos personales tuyos, no podemos acceder a los datos que guarda Google ni borrarlos, pero te ayudaremos con gusto a encontrar el lugar adecuado.

## 9. Cambios en esta política

La versión 4.0 es una aplicación completamente nueva. Las versiones anteriores de «Moon Phases & Sky Events» usaban Google Analytics for Firebase; la versión 4.0 y posteriores no incluyen ninguna analítica. Si esta política cambia, actualizaremos esta página y la fecha indicada arriba.

## 10. Contacto

- Zdravko Stoyanov
- Correo electrónico: **stoyanov.dev@gmail.com**
- Sitio web: [https://stoyanov.dev](https://stoyanov.dev)
