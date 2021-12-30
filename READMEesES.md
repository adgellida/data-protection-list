<a href="https://github.com/adgellida/data-protection-list/blob/main/READMEfrFR.md" target="_blank"><img src="https://raw.githubusercontent.com/adgellida/data-protection-list/main/images/languages/france.png" width="80" img align="right"></a>
<a href="https://github.com/adgellida/data-protection-list/blob/main/READMEesES.md" target="_blank"><img src="https://raw.githubusercontent.com/adgellida/data-protection-list/main/images/languages/spain.png" width="80" img align="right"></a>
<a href="https://github.com/adgellida/data-protection-list" target="_blank"><img src="https://raw.githubusercontent.com/adgellida/data-protection-list/main/images/languages/united-kingdom.png" width="80" style="vertical-align:middle;margin:0px 50px" img align="right"></a>

<img src="https://raw.githubusercontent.com/adgellida/data-protection-list/main/images/privacy-first.png" width="80"> data-protection-list
=============================================

Manual de resistencia al capitalismo de vigilancia

# Índice

* [0 Comentarios del fork](#0-comentarios-del-fork)
* [1 Introducción](#1-introducción)
* [2 Reglas de oro](#2-reglas-de-oro)
* [3 Computadora](#3-computadora)
* [3-1 Sistemas operativos](#3-1-sistemas-operativos)
* [3-2 Servicios y programas](#3-2-servicios-y-programas)
* [4 Smartphone](#4-smartphone)
* [4-1 Sistemas operativos](#4-1-sistemas-operativos)
* [4-2 Aplicaciones](#4-2-aplicaciones)
* [5-Navegadores](#5-navegadores)
* [5-1 Firefox](#5-1-firefox)
* [5-2 Tor Browser](#5-2-tor-browser)
* [6 Instancias de servicios](#6-instancias-de-servicios)
* [6-1 Searx](#6-1-searx)
* [6-2 Invidious](#6-2-invidious)
* [6-3 Videoconferencia](#6-3-videoconferencia)
* [6-4 Servidores DNS](#6-4-servidores-dns)
* [7 Recursos adicionales (fuentes destacadas)](#7-recursos-adicionales-fuentes-destacadas)
* [8 Configuraciones](#8-configuraciones)
* [8-1 Sistemas operativos](#8-1-sistemas-operativos)
* [8-2 F-Droid](#8-2-f-droid)
* [8-3 Aplicaciones y programas](#8-3-aplicaciones-y-programas)
* [8-4 Firefox](#8-4-firefox)

## 0 Comentarios del fork

Me he visto en la necesidad de forkear este documento de **Valentin Delacour** hospedado [aquí](https://codeberg.org/PrivacyFirst/PrivacyFirst/issues) bajo su aprobación y licencia para darle más visibilidad, legibilidad, comodidad, mejora en algunos aspectos y participación. Si otra persona forkea tanto el suyo como este debe hacer lo mismo

Pienso que debemos compartir cuánto más mejor y los conocimientos sobre las buenas prácticas a seguir referente a la seguridad, privacidad y open source que se detallan no son una excepción.

Estamos abiertos a que este documento se cambie de formato, por ahora he pensado que esta es una buena forma, pero mejorable.

No me considero ningún experto sobre el tema. De hecho no sigo todas las recomendaciones al pie de la letra. Pero sí que me gustaría con el tiempo ir dejando de lado servicios que considero no debería usar por diversas causas, cambiar formas de acceso a cierto contenido, usar otras estrategias, etc.

Para participar activamente puedes:

* [Crear pull requests](https://github.com/adgellida/data-protection-list/pulls)
* [Generar tus cuestiones o incidencias](https://github.com/adgellida/data-protection-list/issues)

Os recomiendo participar en:

* <img src="./icons/telegram.png" width="30">[Official Telegram Group](https://t.me/privacid)
* <img src="./icons/discord.png" width="30">[Official Discord Group](https://t.me/privacid) - Aunque debido a varias razones de privacidad, seguridad no lo recomendamos.
* <img src="./icons/matrix.png" width="30">[Official Group on Matrix](https://t.me/privacid)- #privacidadlibre:matrix.org - Pedir invitación

El objetivo del grupo es promover colectivamente buenas costumbres en cuanto a la privacidad, seguridad y tambien programas/apps, servicios y sistemas operativos open source/libres para resistir a la recolección y explotación de datos personales por empresas privadas.

Yo pienso que se aprovechan del desconocimiento de la mayoría para hacer cosas que no deberían y beneficiarse de ello a nuestras espaldas. Lo bueno es que hay gente que se da cuenta porque entiende del tema y lo comparte con la comunidad.

Este documento ha sido copiado 1:1 con muy ligeras modificaciones en la versión 7/12/2020 y a partir de ahora sufrirá modificaciones siguiendo las siguientes estrategias:

* Siguientes actualizaciones del fichero original
* Pull requests de la comunidad
* Descubrimientos propios

Las mejoras más destacables son:

* Fomenta una participación más ordenada, efectiva, pública.
* Imágenes de las apps para identificarlas mejor.
* Enlaces a las mismas para encontrarlas rápidamente.

Ahora sí, empieza el documento. Póngase el cinturón que vienen curvas!

## 1 Introducción

Este documento tiene como objetivo principal proponer herramientas y alternativas para proteger los datos y la privacidad de la predación de empresas privadas bajo el sistema actual de capitalismo de vigilancia. Ahora bien, seguir las siguientes
recomendaciones permite también mejorar, en ciertas medidas, la protección contra otras entes tales como servicios de Estados o piratas, por ejemplo.

Esta lista se destina a todas las personas conscientes o tomando consciencia de la importancia de la protección de datos en nuestra sociedad, independientemente de sus conocimientos del tema. No se destina a las personas necesitando un anonimato
total de parte de su función a riesgos tales como opositores políticos o algunos periodistas, aún si algunas opciones propuestas podrían convenirles. Efectivamente, la privacidad no necesariamente es igual al anonimato.

El formato de lista fue escogido con el afán de hacer su consulta lo más eficiente posible. Este enfoque impide detallar verdaderas explicaciones. Así que les invito a buscar las que les sean necesarias por sí mismos o en los recursos adicionales
mencionados en el punto 6 del documento. Teniendo el propósito de proponer las opciones más reputadas y prácticas sin estar demasiado cargada, la lista no tiene por vocación ser exhaustiva y permanece subjetiva a pesar de buscar tener la mayor
objetividad posible.

Esta lista propone una primera priorización (orden de aparición y presencia o no de paréntesis) subjetiva basada en el reporte privacidad/usabilidad con el fin de ayudarles a escoger entre las diferentes opciones citadas. Una segunda priorización
(colores) se basa unicamente en la privacidad estimada :

🟢verde (verdadero respeto de la privacidad)

🔵azul (respeto de la privacidad bajo condiciones o presencia de un elemento problemático)

🔴rojo (no garantiza el respeto de la privacidad pero sigue siendo preferible a las opciones de los GAFAM)

⚫incoloro (falta de elementos para formar una estimación, o una priorización no es pertinente para la entrada en cuestión). La presencia de un asterisco indica que la opción mencionada sigue enfase de desarrollo.

Espero que este documento les servirá para mejorar la protección de sus datos personales y de los de sus cercanos. Aunque siendo el fruto de varios años de búsquedas y experimentos, este trabajo permanece obviamente perfectible.
Cualquier sugerencia o comentario es entonces más que bienvenido al correo : “privacyfirst@ik.me”. Varios meses después de la presente versión del documento, se debe asumir que ciertas informaciones dadas serán obsoletas. El documento siendo
actualizado frecuentemente, están invitados a conseguir la última versión en la página web siguiente : “https://codeberg.org/PrivacyFirst/PrivacyFirst/issues”.

## 2 Reglas de oro

* Evitar usar servicios y programas de los GAFAM (Google, Amazon, Facebook, Apple y Microsoft) SIEMPRE que sea posible. Lo más recomendable es eliminar sus eventuales cuentas.
* Siempre revisar todos los ajustes y autorizaciones de lo que se utiliza y optimizarlos para limitar al máximo la recolección de datos personales.
* Solo instalar los programas/aplicaciones necesarios pues son accesos potenciales a sus datos personales.
* Usar programas libres/open source (sus códigos son públicos y así mismo verificables) en vez de los propietarios/closed source siempre que es posible.
* Favorecer las opciones libres populares a las desconocidas (serán más revisadas/confiables).
* Si una empresa propone sus servicios gratuitamente, en general, el producto que vende es usted (sus datos personales). Por causa del modelo impuesto por el capitalismo de vigilancia, pagar ya ni les protege de también ser el producto.
* Actualizar sus programas/sistemas operativos frecuentemente para beneficiar de los últimos correctivos de fallas de seguridad explotables y pensar en reemplazar los que ya no parecen ser actualizados.
* No usar antivirus de terceros, son verdaderas aspiradoras de datos personales. Su aporte es desdeñable con tal de que se mantengan buenas costumbres numéricas. La prudencia y una buena configuración son los mejores antivirus.
* Privilegiar Web Apps o atajos desde el navegador para acceder a servicios en vez de aplicaciones a instalar para limitar el acceso y las posibilidades de recolección de datos personales.
* Utilizar correos temporales para crear cuentas para sitios/servicios poco importantes.
* Siempre desactivar el Wi-Fi, Bluetooth y geolocalización de su smartphone cuando no están usados y no conectarse a Wi-Fi públicos sin el uso de un VPN.
* No usar objetos conectados (su propósito es recolectar la mayor cantidad posible de datos personales) o no conectarlos a internet cuando son imprescindibles.

## 3 Computadora

### 3-1 Sistemas operativos

Windows es actualmente el peor sistema operativo en términos de privacidad y de seguridad. Los únicos SO fáciles de uso y protegiendo realmente los datos son las distribuciones libres (por lo tanto gratuitas) de Linux. Existe una multitud de ellas cuyas características varían considerablemente. Aquí una pequeña selección de las ofreciendo la mejor experiencia para el usuario (siempre respetando la privacidad) o garantizando la mayor protección de datos.
Cabe recordar que cada una de ellas propone una o varias interfaces (entornos de escritorio) diferentes en términos de experiencia, de consumo de recursos y de apariencia. Existe una documentación abundante en linea para escoger cual distribución y entorno de escritorio convendrán mejor a las capacidades de su computadora y a sus preferencias así como para saber como instalarla fácilmente en su computadora.

**Desktop :**

🟢<img src="./icons/linuxmint.png" width="30">[Linux Mint](https://linuxmint.com) : ideal para principiantes

🟢<img src="./icons/mxlinux.png" width="30">[MX Linux](https://mxlinux.org) : conviene a los principiantes

🟢<img src="./icons/parrotos.png" width="30">[Parrot Home OS](https://www.parrotsec.org) : seguridad y privacidad mejoradas (usuarios confirmados)

🟢<img src="./icons/zorinos.png" width="30">[Zorin OS](https://zorin.com/os) : ideal para principiantes viniendo de Windows o macOS (soporte comercial)

🟢<img src="./icons/qubeos.png" width="30">[Qubes OS](https://www.qubes-os.org) : seguridad extrema (usuarios avanzados)

🟢<img src="./icons/whonix.png" width="30">[Whonix](https://www.whonix.org) : anonimato por Tor y seguridad extrema (usuarios avanzados)

**USB live (RAM) :**

🟢<img src="./icons/mxlinux.png" width="30">[MX Linux](https://mxlinux.org) : conviene a los principiantes

🟢<img src="./icons/tails.png" width="30">[Tails](https://tails.boum.org) : anonimato por Tor (usuarios confirmados)

🟢<img src="./icons/parrotos.png" width="30">[Parrot Home OS](https://www.parrotsec.org) : seguridad y privacidad mejoradas (usuarios confirmados)

**Raspberry Pi :**

🟢<img src="./icons/libreelec.png" width="30">[LibreELEC](https://libreelec.tv) : centro multimedia para TV

🟢<img src="./icons/batocera.png" width="30">[Batocera](https://batocera.org) : emulador de consolas, retrogaming

🟢<img src="./icons/raspberrypios.png" width="30">[Raspberry Pi OS](https://www.raspberrypi.org/software) : sistema operativo clásico

🟢<img src="./icons/plasmabigscreen.png" width="30">[Plasma BigScreen*](https://plasma-bigscreen.org) : centro multimedia para TV (comando de voz con Mycroft AI)

🟢<img src="./icons/nymphcast.png" width="30">[Nymphcast*](http://nyanko.ws/product_nymphcast.php) : alternativa libre y respetuosa a Chromecast

**Hardware :**

Las marcas siguientes venden computadoras con Linux preinstalado :

TUXEDO Computers

Slimbook

Librem

System76

Linux Mint

PINE64

ThinkPenguin

Dell (pocos modelos)

También existen otros vendedores menos conocidos de computadoras con Linux preinstalado. En cuanto a los vendedores de computadoras con Windows
preinstalado, los modelos de Dell, Asus y HP son reputados por tener una buena compatibilidad con Linux. Es recomendable evitar comprar computadoras que vienen con una tarjeta gráfica Nvidia dado que son conocidas por padecer de problemas de compatibilidad.

### 3-2 Servicios y programas

Navegador :

🔵<img src="./icons/firefox.png" width="30">[Firefox](https://www.mozilla.org)

🟢<img src="./icons/torbrowser.png" width="30">[Tor Browser](https://www.torproject.org/download)

🟢<img src="./icons/librewolf.png" width="30">[LibreWolf*](https://librewolf-community.gitlab.io)

🔴<img src="./icons/brave.png" width="30">[Brave](https://brave.com)

🔵<img src="./icons/ungoogledchromium.png" width="30">[Ungoogled Chromium*](https://ungoogled-software.github.io/ungoogled-chromium-binaries/)

🔵<img src="./icons/iridiumbrowser.png" width="30">[Iridium Browser](https://iridiumbrowser.de)

Buscador :

🔵<img src="./icons/duckduckgo.png" width="30">[DuckDuckGo](https://duckduckgo.com)

🔵<img src="./icons/searxme.png" width="30">[searx.me](https://searx.me)

🔵<img src="./icons/qwant.png" width="30">[Qwant](https://www.qwant.com)

🔵<img src="./icons/swisscows.png" width="30">[Swisscows](https://swisscows.com)

🔴<img src="./icons/startpage.png" width="30">[Startpage](https://www.startpage.com) (proxy Google)

⚫<img src="./icons/brave.png" width="30">[Brave Search](https://search.brave.com/)

Ofimática :

🟢<img src="./icons/libreoffice.png" width="30">[LibreOffice](https://www.libreoffice.org)

🟢<img src="./icons/onlyoffice.png" width="30">[Onlyoffice](https://www.onlyoffice.com)

🟢<img src="./icons/collaboraoffice.png" width="30">[Collabora Office - LibreOffice prof.](https://www.collaboraoffice.com)

🟢<img src="./icons/calligra.png" width="30">[Calligra](https://calligra.org)

🟢<img src="./icons/cryptpad.png" width="30">[CryptPad](https://cryptpad.fr)

Correo :

<img src="./icons/tutanota.png" width="30">[Tutanota](https://tutanota.com) 🔵gratuito 🔴de pago

<img src="./icons/protonmail.png" width="30">[ProtonMail](https://protonmail.com) 🔵gratuito 🔵de pago

<img src="./icons/disroot.png" width="30">[Disroot](https://disroot.org/en/services/email) 🔵gratuito

<img src="./icons/posteo.png" width="30">[Posteo](https://posteo.de) 🔵de pago

Plataforma vídeo :

🔵<img src="./icons/lbry.png" width="30">[LBRY - desktop](https://lbry.com)

🔴<img src="./icons/odysee.png" width="30">[Odysee - LBRY web](https://odysee.com)

🟢<img src="./icons/peertube.png" width="30">[PeerTube](https://joinpeertube.org)

Proxy Youtube :

🔵<img src="./icons/invidious.png" width="30">[Invidious](https://invidio.us)

🔵<img src="./icons/cloudtube.png" width="30">[CloudTube](https://cadence.moe/cloudtube/subscriptions)

🔵<img src="./icons/freetube.png" width="30">[FreeTube](https://freetubeapp.io) (cliente Youtube)

Mensajería instantánea :

🟢<img src="./icons/threema.png" width="30">[Threema](https://threema.ch/en)

🔵<img src="./icons/signal.png" width="30">[Signal](https://signal.org)

🟢<img src="./icons/session.png" width="30">[Session*](https://getsession.org)

🔴<img src="./icons/telegram.png" width="30">[Telegram](https://telegram.org)

🔵<img src="./icons/element.png" width="30">[Element](https://app.element.io)

🔵<img src="./icons/jami.png" width="30">[Jami](https://jami.net)

🔵<img src="./icons/gajim.png" width="30">[Gajim](https://gajim.org/)

Videoconferencia :

🟢<img src="./icons/jitsimeet.png" width="30">[Jitsi Meet](https://meet.jit.si)

🔵<img src="./icons/signal.png" width="30">[Signal](https://signal.org)

🔵<img src="./icons/bigbluebutton.png" width="30">[BigBlueButton](https://bigbluebutton.org)

🟢<img src="./icons/jami.png" width="30">[Jami](https://jami.net)

🔵<img src="./icons/element.png" width="30">[Element](https://app.element.io)

🔵<img src="./icons/whereby.png" width="30">[Whereby](https://whereby.com)

🔴<img src="./icons/telegram.png" width="30">[Telegram](https://telegram.org)

Red social respetuosa:

🔵<img src="./icons/mastodon.png" width="30">[Mastodon](https://mastodon.social)

🔵<img src="./icons/telegram.png" width="30">[Telegram*](https://telegram.org)

🔵<img src="./icons/element.png" width="30">[Element](https://app.element.io)

🔵<img src="./icons/pixelfed.png" width="30">[PixelFed](https://pixelfed.org)

🔵<img src="./icons/lemmy.png" width="30">[Lemmy](https://join.lemmy.ml/)

🔵<img src="./icons/pleroma.png" width="30">[Pleroma](https://pleroma.social/)

🔵<img src="./icons/movim.png" width="30">[movim](https://movim.eu/)

🔵<img src="./icons/friendica.png" width="30">[Friendica](https://friendi.ca)

Proxy de red social abusiva:

🔵<img src="./icons/nitter.png" width="30">[Nitter](https://nitter.net) (Twitter)

🔵<img src="./icons/libreddit.png" width="30">[Libreddit](https://libredd.it/) (Reddit)

🔵<img src="./icons/bibliogram.png" width="30">[Bibliogram](https://bibliogram.art) (Instagram)

Traductor :

🟢<img src="./icons/libretranslate.png" width="30">[LibreTranslate](https://libretranslate.com/)

<img src="./icons/deepl.png" width="30">[DeepL](https://www.deepl.com/translator) 🔴gratuito 🔵de pago

🟢<img src="./icons/apertium.png" width="30">[Apertium](https://www.apertium.org)

🔴<img src="./icons/lingva.png" width="30">[Lingva Translate](https://lingva.ml) (proxy Google
Translate)

Bloqueador de publicidad/rastreadores y controlador de trafico red :

⚫<img src="./icons/portmaster.png" width="30">[Portmaster*](https://safing.io/portmaster)

Administrador de contraseñas :

🟢<img src="./icons/keepassxc.png" width="30">[KeePassXC](https://keepassxc.org)

🔵<img src="./icons/bitwarden.png" width="30">[Bitwarden](https://bitwarden.com)

Mapas :

🟢<img src="./icons/openstreetmap.png" width="30">[OpenStreetMap](https://www.openstreetmap.org)

🔵<img src="./icons/qwant.png" width="30">[Qwant Maps*](https://www.qwant.com/map)

🔵<img src="./icons/duckduckgo.png" width="30">[DuckDuckGo](https://duckduckgo.com)

🔴<img src="./icons/mapsme.png" width="30">[Maps.me](https://maps.me)

VPN :

🟢<img src="./icons/protonvpn.png" width="30">[ProtonVPN](https://protonvpn.com)

🟢<img src="./icons/ivpn.svg" width="30">[IVPN](https://www.ivpn.net)

🔵<img src="./icons/mullvad.png" width="30">[Mullvad](https://mullvad.net)

🔵<img src="./icons/windscribe.png" width="30">[Windscribe](https://windscribe.com/)

Películas y series en linea :

🔵<img src="./icons/stremio.png" width="30">[Stremio](https://www.stremio.com) 🔵sin cuenta 🔴con cuenta

🟢<img src="./icons/kodi.png" width="30">[Kodi](https://kodi.tv)

Compartición de archivos :

🟢<img src="./icons/disroot.png" width="30">[Disroot](https://upload.disroot.org)

🟢<img src="./icons/onionshare.png" width="30">[OnionShare](https://onionshare.org)

🟢<img src="./icons/syncthing.png" width="30">[Syncthing](https://syncthing.net)

🔵<img src="./icons/tresoritsend.png" width="30">[Tresorit Send](https://tresorit.com/)

🔴<img src="./icons/swisstransfer.png" width="30">[Swiss Transfer](https://swisstransfer.com)

Cloud :

🔵<img src="./icons/kdrive.png" width="30">[Kdrive](https://www.infomaniak.com/es/kdrive)

🔵<img src="./icons/mega.png" width="30">[Kdrive](https://www.https://mega.nz)

🟢<img src="./icons/nextcloud.png" width="30">[Nextcloud](https://nextcloud.com)

🔴<img src="./icons/cozycloud.png" width="30">[Cozy Cloud](https://cozy.io)

<img src="./icons/icedrive.png" width="30">[Kdrive](https://icedrive.net) 🔴gratuito 🔵pago

🔴<img src="./icons/disroot.png" width="30">[Disroot](https://cloud.disroot.org)

Herramienta de sincronización Peer-to-peer :

🟢<img src="./icons/syncthing.png" width="30">[Syncthing](https://syncthing.net)

Agenda :

🟢<img src="./icons/tutanota.png" width="30">[Tutanota](https://f-droid.org/es/packages/de.tutao.tutanota)

🟢<img src="./icons/protonmail.png" width="30">[ProtonCalendar*](https://protonmail.com)

Correo temporal :

⚫<img src="./icons/tempmail.png" width="30">[Temp Mail](https://temp-mail.org)

⚫<img src="./icons/guerrillamail.png" width="30">[Guerrillamail](https://guerrillamail.com)

⚫<img src="./icons/emailondeck.png" width="30">[EmailOnDeck](https://www.emailondeck.com)

Gestor de alias para correo :

🟢<img src="./icons/forwardemail.png" width="30">[forwardemail](https://forwardemail.net)

Colaboración y organización:

🟢<img src="./icons/cryptpad.png" width="30">[CryptPad](https://cryptpad.fr)

🟢<img src="./icons/mobilizon.png" width="30">[Mobilizon](https://mobilizon.org/en/)

Wikipedia :

🟢<img src="./icons/wikiless.png" width="30">[Elisa](https://wikiless.org) (proxy Wikipedia)

Reproductor audio :

🟢<img src="./icons/elisa.png" width="30">[Elisa](https://elisa.kde.org)

🟢<img src="./icons/audacious.png" width="30">[Audacious](https://audacious-media-player.org)

🟢<img src="./icons/strawberry.png" width="30">[Strawberry Music Player](https://www.strawberrymusicplayer.org)

Reproductor multimedia :

🟢<img src="./icons/mpv.png" width="30">[mpv](https://mpv.io)

🟢<img src="./icons/vlc.png" width="30">[VLC](https://www.videolan.org)

Notas :

🟢<img src="./icons/standardnotes.png" width="30">[Standard Notes](https://standardnotes.org)

🟢<img src="./icons/joplin.png" width="30">[Joplin](https://joplinapp.org)

🟢<img src="./icons/knotes.png" width="30">[Knotes](http://knotesapp.com)

🟢<img src="./icons/gnome.png" width="30">[Gnote](https://wiki.gnome.org/Apps/Gnote)

Antivirus (ClamAV) :

🟢ClamTK (Linux)

🟢ClamWin (Windows)

Limpieza y optimización de sistema :

🟢<img src="./icons/stacer.png" width="30">[Stacer](https://oguzhaninan.github.io/Stacer-Web)

🟢<img src="./icons/ubunsys.png" width="30">[ubunsys](https://github.com/adgellida/ubunsys)

🟢<img src="./icons/bleachbit.png" width="30">[BleachBit](https://www.bleachbit.org)

Herramienta de cifrado :

🟢<img src="./icons/veracrypt.png" width="30">[VeraCrypt](https://www.veracrypt.fr)

🟢<img src="./icons/cryptomator.png" width="30">[Cryptomator](https://cryptomator.org)

Supresión de metadatos :

🟢<img src="./icons/exifcleaner.png" width="30">[ExifCleaner](https://exifcleaner.com)

Edición de imágenes y dibujo :

🟢<img src="./icons/gimp.png" width="30">[Gimp](http://www.gimp.org)

🟢<img src="./icons/krita.png" width="30">[Krita](https://krita.org)

🟢<img src="./icons/drawing.png" width="30">[Drawing](https://maoschanz.github.io/drawing)

Procesamiento de fotografías :

🟢<img src="./icons/darktable.png" width="30">[Darktable](https://www.darktable.org)

🟢<img src="./icons/rawtherapee.png" width="30">[RawTherapee](https://rawtherapee.com)

Edición gráfica vectorial :

🟢<img src="./icons/inkscape.png" width="30">[Inkscape](https://inkscape.org)

🟢<img src="./icons/karbon.png" width="30">[Karbon](https://calligra.org/karbon)

Maquetación de páginas :

🟢<img src="./icons/scribus.png" width="30">[Scribus](https://www.scribus.net)

Edición audio :

🟢<img src="./icons/lmms.png" width="30">[LMMS](https://www.lmms.io)

🟢<img src="./icons/ardour.png" width="30">[Ardour](https://www.ardour.org)

🔵<img src="./icons/audacity.png" width="30">[Audacity](https://www.audacityteam.org)

Edición video :

🟢<img src="./icons/openshot.png" width="30">[OpenShot](https://www.openshot.org)

🟢<img src="./icons/kdenlive.png" width="30">[Kdenlive](https://kdenlive.org)

🟢<img src="./icons/avidemux.png" width="30">[Avidemux](https://www.avidemux.org)

🟢<img src="./icons/pitivi.png" width="30">[Pitivi](http://www.pitivi.org)

🟢<img src="./icons/cinelerra.png" width="30">[Cinelerra](http://cinelerra.org)

Grabación de CD/DVD :

🟢<img src="./icons/k3b.png" width="30">[k3b](https://apps.kde.org/k3b)

🟢<img src="./icons/brasero.png" width="30">[Brasero](https://wiki.gnome.org/Apps/Brasero)

Transcodificación :

🟢<img src="./icons/handbrake.png" width="30">[Handbrake](https://handbrake.fr)

🟢<img src="./icons/mkv.png" width="30">[MKV](https://www.matroska.org/index.html)

Interfaz de conexión entre computadora y celular :

🟢KDE Connect

🟢Zorin Connect

Programas/juegos Windows bajo Linux :

⚫<img src="./icons/playonlinux.png" width="30">[PlayOnLinux](https://www.playonlinux.com)

⚫<img src="./icons/wine.png" width="30">[Wine](https://www.winehq.org)

⚫<img src="./icons/winapps.svg" width="30">[WinApps*](https://github.com/Fmstrat/winapps)

Análisis de trafico de red :

🟢<img src="./icons/wireshark.png" width="30">[Wireshark](https://www.wireshark.org)

Ecosistema todo en uno :

🔵Infomaniak

🔵Proton*

🔵Cozy Cloud

## 4 Smartphone

### 4-1 Sistemas operativos

Android, en su configuración por defecto, es actualmente el peor sistema operativo en cuanto a la privacidad. Su propósito es mandar continuamente datos personales hacia los servidores de Google para explotarlos y venderlos. La solución más recomendable en la actualidad es usar una versión de Android modificada (custom ROM) para respetar la privacidad.

Si no desean instalar o comprar un smartphone con un sistema operativo respetuoso (grave error) y que a pesar de todo desean usar Android de origen, sigan los consejos detallados en el punto 8.1 de este documento en el afán de limitar al máximo la recolección de datos personales.

El sistema operativo de Apple (iOS), a pesar de su marketing basado en el respeto de la privacidad, también recolecta y explota los datos personales de sus usuarios además de limitar considerablemente su libertad.

Las opciones basadas en Linux son respetuosas de la privacidad y prometedoras en términos de independencia pero no ofrecen las mismas garantías en términos de seguridad que Android. Además, en su estado de desarrollo actual, no son recomendables para usuarios promedios (a excepción de Sailfish OS).

**Android modificado para la privacidad :**

🟢<img src="./icons/calyxos.png" width="30">[CalyxOS](https://calyxos.org) : Android degooglizado y seguro con microG para una mejor compatibilidad

🟢<img src="./icons/grapheneos.png" width="30">[GrapheneOS](https://grapheneos.org) : el Android degooglizado más privado y seguro disponible

🔵<img src="./icons/e.png" width="30">[/e/ OS](https://e.foundation) : LineageOS degooglizado pero con microG y servicios integrados (cuenta /e/)

🔵<img src="./icons/divestos.png" width="30">[DivestOS](https://divestos.org/) : LineageOS parcialmente mejorado para la seguridad y privacidad

🔵<img src="./icons/lineageosmicrog.png" width="30">[LineageOS for microG](https://lineage.microg.org) : LineageOS con microG para una mejor compatibilidad

🔵<img src="./icons/vollaos.png" width="30">[Volla OS](https://volla.online): Android seguro, sin Google apps pero no totalmente degooglizado

🔵<img src="./icons/lineageos.png" width="30">[LineageOS](https://lineageos.org) : Android sin Google apps pero no totalmente degooglizado

**Linux :**

🔵<img src="./icons/sailfishos.png" width="30">[Sailfish OS](https://sailfishos.org) (partialmente proprietario)

🔵<img src="./icons/ubuntutouch.png" width="30">[Ubuntu Touch*](https://ubuntu-touch.io)

🔵<img src="./icons/postmarketos.png" width="30">[PostmarketOS*](https://postmarketos.org)

🔵<img src="./icons/mobian.png" width="30">[Mobian*](https://mobian-project.org)

🔵<img src="./icons/pureos.png" width="30">[PureOS*](https://pureos.net)

🔵<img src="./icons/manjaro.png" width="30">[Manjaro*](https://manjaro.org)

**Hardware preinstalado :**

[Fairphone 3 y 3+](https://www.fairphone.com) : /e/ OS (versión solo disponible en el sitio del proyecto /e/)

[Gigaset GS290](https://e.foundation/es/e-announces-the-e-gs290-as-the-latest-device-available-with-privacy-friendly-e-os-pre-installed/) : /e/OS (versión solo disponible en el sitio del proyecto /e/)

[Volla Phone](https://volla.online) : Volla OS, Ubuntu Touch otros compatibles

[Pinephone](https://www.pine64.org/pinephone) : Manjaro y otros S.O. Linux compatibles)

Otros modelos con /e/ OS preinstalado están disponibles en el [sitio del proyecto /e/](https://esolutions.shop)

### 4-2 Aplicaciones

Las aplicaciones propuestas para Android y derivados deben ser buscadas primero en la tienda de aplicaciones libres F-Droid (garantía que no tengan rastreadores terceros) y solo si no están, en Aurora Store, un proxy de Google Play permitiendo tener acceso a sus aplicaciones gratuitas de manera anónima (nunca conectarse con una cuenta Google personal, siempre con la anónima).

Estas tiendas deben ser descargadas directamente desde sus páginas web oficiales. Recuerden luego retirar la autorización de instalar aplicaciones desconocidas a su navegador, por motivos de seguridad (ajustes > aplicaciones > navegador utilizado).

**Android y derivados :**

Tienda de aplicaciones :

🟢<img src="./icons/f-droid.png" width="30">[F-Droid](https://f-droid.org)

🔵<img src="./icons/aurorastore.png" width="30">[Aurora Store](https://auroraoss.com) (proxy Play Store)

🔵<img src="./icons/apkmirror.png" width="30">[APKMirror](https://www.apkmirror.com)

Navegador :

🟢<img src="./icons/bromite.png" width="30">[Bromite](https://www.bromite.org/fdroid)

🟢<img src="./icons/torbrowser.png" width="30">[Tor Browser](https://www.torproject.org/es/download/#android)

🔵<img src="./icons/mull.png" width="30">[mull](https://github.com/Divested-Mobile/mull)

🔵<img src="./icons/privacybrowser.png" width="30">[Privacy Browser](https://f-droid.org/es/packages/com.stoutner.privacybrowser.standard)

🔵<img src="./icons/fossbrowser.png" width="30">[FOSS Browser](https://f-droid.org/es/packages/de.baumann.browser)

🔵<img src="./icons/ungoogledchromium.png" width="30">[Ungoogled Chromium](https://uc.droidware.info/fdroid.html)

Mensajería instantánea :

🟢<img src="./icons/threema.png" width="30">[Threema](https://threema.ch/en)

🔵<img src="./icons/signal.png" width="30">[Signal](https://signal.org)

🟢<img src="./icons/session.png" width="30">[Session*](https://getsession.org)

🔴<img src="./icons/telegram.png" width="30">[Telegram FOSS](https://f-droid.org/packages/org.telegram.messenger/)

🔵<img src="./icons/element.png" width="30">[Element](https://app.element.io)

🔵<img src="./icons/jami.png" width="30">[Jami](https://jami.net)

🟢<img src="./icons/briar.png" width="30">[Briar](https://briarproject.org)

🔵<img src="./icons/conversations.png" width="30">[Conversations](https://conversations.im)

Videoconferencia :

🟢<img src="./icons/jitsimeet.png" width="30">[Jitsi Meet](https://meet.jit.si)

🔵<img src="./icons/signal.png" width="30">[Signal](https://signal.org)

🟢<img src="./icons/jami.png" width="30">[Jami](https://jami.net)

🔵<img src="./icons/element.png" width="30">[Element](https://app.element.io)

🔵<img src="./icons/whereby.png" width="30">[Whereby](https://whereby.com)

🔴<img src="./icons/telegram.png" width="30">[Telegram FOSS](https://f-droid.org/packages/org.telegram.messenger)

Plataforma vídeo :

🔴<img src="./icons/lbry.png" width="30">[LBRY](https://lbry.com)

🔴<img src="./icons/newpipe.png" width="30">[Newpipe](https://newpipe.schabi.org) (cliente Youtube)

🟢<img src="./icons/tubelab.png" width="30">[Tubelab](https://f-droid.org/en/packages/app.fedilab.tubelab/) (cliente Peertube)

Bloqueador de publicidad/rastreadores :

🟢<img src="./icons/rethinkdns.png" width="30">[RethinkDNS*](https://play.google.com/store/apps/details?id=com.celzero.bravedns&hl=es&gl=US)

🟢<img src="./icons/blokada.png" width="30">[Blokada](https://f-droid.org/es/packages/org.blokada.alarm)

🟢<img src="./icons/nebulo.png" width="30">[Nebulo](https://play.google.com/store/apps/details?id=com.frostnerd.smokescreen&hl=es&gl=US)

🟢TrackerControl

Mapas/navegación GPS :

🔵<img src="./icons/magicearth.png" width="30">[Magic Earth](https://www.magicearth.com)

🟢<img src="./icons/osmand.png" width="30">[OsmAnd+](https://f-droid.org/es/packages/net.osmand.plus/)

🟢Organic Maps

Cliente correo :

🔵<img src="./icons/tutanota.png" width="30">[Tutanota](https://f-droid.org/es/packages/de.tutao.tutanota)

🔵<img src="./icons/protonmail.png" width="30">[ProtonMail](https://protonmail.com)

⚫[FairEmail](https://email.faircode.eu)

⚫<img src="./icons/k-9mail.png" width="30">[K-9 Mail](https://f-droid.org/es/packages/com.fsck.k9)

Gestor de alias para correo :

🟢<img src="./icons/simplelogin.png" width="30">[Simple Login](https://simplelogin.io)

🟢<img src="./icons/anonaddy.png" width="30">[AnonAddy](https://anonaddy.com/)

Cliente administrador de contraseñas :

🟢<img src="./icons/keepassdx.png" width="30">[KeePassDX](https://f-droid.org/es/packages/com.kunzisoft.keepass.libre)

🔵<img src="./icons/bitwarden.png" width="30">[Bitwarden](https://bitwarden.com)

🟢AuthPass

Autentificación a dos factores :

🟢<img src="./icons/aegis.png" width="30">[Aegis](https://f-droid.org/es/packages/com.beemdevelopment.aegis)

🟢<img src="./icons/andotp.png" width="30">[andOTP](https://f-droid.org/en/packages/org.shadowice.flocke.andotp)

VPN :

🟢<img src="./icons/protonvpn.png" width="30">[ProtonVPN](https://protonvpn.com)

🟢<img src="./icons/ivpn.svg" width="30">[IVPN](https://www.ivpn.net)

🔵<img src="./icons/mullvad.png" width="30">[Mullvad](https://mullvad.net)

🔵<img src="./icons/riseupvpn.svg" width="30">[Riseup VPN](https://riseup.net/es/vpn)

🔵<img src="./icons/calyxos.png" width="30">[Calyx VPN](https://calyx.net/)

Herramienta de sincronización :

🟢<img src="./icons/syncthing.png" width="30">[Syncthing](https://f-droid.org/en/packages/com.nutomic.syncthingandroid)

⚫DAVx5

Cloud :

🔵<img src="./icons/kdrive.png" width="30">[Kdrive](https://www.infomaniak.com/es/kdrive)

🔴<img src="./icons/mega.png" width="30">[Kdrive](https://www.https://mega.nz)

🟢<img src="./icons/nextcloud.png" width="30">[Nextcloud](https://nextcloud.com)

🔴<img src="./icons/cozycloud.png" width="30">[Cozy Drive](https://cozy.io)

🔴<img src="./icons/icedrive.png" width="30">[Kdrive](https://icedrive.net)

Herramienta de cifrado para cloud :

🟢<img src="./icons/cryptomator.png" width="30">[Cryptomator](https://cryptomator.org)

Interfaz de conexión entre computadora y celular :

🟢KDE Connect

🟢Zorin Connect

Red social respetuosa :

🔵<img src="./icons/tusky.png" width="30">[Tusky](https://f-droid.org/en/packages/com.keylesspalace.tusky) (Mastodon)

🔵<img src="./icons/telegram.png" width="30">[Telegram FOSS](https://f-droid.org/packages/org.telegram.messenger)

🔵<img src="./icons/element.png" width="30">[Element](https://f-droid.org/es/packages/im.vector.app) (Matrix)

🔵<img src="./icons/fedilab.png" width="30">[Fedilab](https://f-droid.org/en/packages/fr.gouv.etalab.mastodon) Mastodon, Pleroma...),

🔵PixelDroid (PixelFed)

🔵<img src="./icons/lemmy.png" width="30">[Lemmur (Lemmy)](https://lemmy.ml)

Cliente respetuoso Facebook :

🔴<img src="./icons/frost.png" width="30">[Frost for Facebook](https://f-droid.org/es/packages/com.pitchedapps.frost)

🔴<img src="./icons/webapps.png" width="30">WebApps

Cliente respetuoso Instagram :

🔴<img src="./icons/webapps.png" width="30">WebApps

🔴Barinsta

Cliente respetuoso Twitter :

🔴Fritter

🔴<img src="./icons/twidere.png" width="30">[Twidere](https://f-droid.org/es/packages/org.mariotaku.twidere)

🔴<img src="./icons/webapps.png" width="30">WebApps

Creador de WebApps :

🟢<img src="./icons/webapps.png" width="30">WebApps

Películas y series en linea :

🔴<img src="./icons/stremio.png" width="30">[Stremio](https://www.stremio.com)

🟢<img src="./icons/kodi.png" width="30">[Kodi](https://f-droid.org/es/packages/org.xbmc.kodi)

Supresión de metadatos :

🟢<img src="./icons/scrambledexif.png" width="30">[Scrambled Exif](https://f-droid.org/es/packages/com.jarsilio.android.scrambledeggsif)

🟢<img src="./icons/imagepipe.png" width="30">[ImagePipe](https://f-droid.org/es/packages/de.kaffeemitkoffein.imagepipe)

Ofimática :

🟢<img src="./icons/collaboraoffice.png" width="30">[Collabora Office - LibreOffice prof.](https://www.collaboraoffice.com)

🟢LibreOffice

Lector de libros electrónicos :

🟢Librera Reader

🟢KOReader

Finanzas :

🟢MoneyWallet

🟢Unstoppable Wallet

🟢MoneyBuster

🟢WeeklyBudget

Ejercicio físico :

🟢Feeel – home workouts

🟢FitoTracker

🟢Workout Time!

Radio internet :

🟢<img src="./icons/radiodroid.png" width="30">[RadioDroid](https://f-droid.org/es/packages/net.programmierecke.radiodroid2)

🟢Transistor – Simple Radio App

Redirector de contenido Youtube, Twitter, Instagram y Google Map :

🟢<img src="./icons/untrackme.png" width="30">[UntrackMe](https://f-droid.org/en/packages/app.fedilab.nitterizeme)

Escáner de códigos QR :

⚫QR & Barcode Scanner

Lector RSS :

🟢Feeder

🟢Flym

🟢Handy News Reader

Reemplazo de aplicaciones sistema para Android de origen :

Keyboard :

🟢<img src="./icons/anysoftkeyboard.png" width="30">[AnySoftKeyboard](https://anysoftkeyboard.github.io)

🟢<img src="./icons/openboard.png" width="30">[OpenBoard](https://f-droid.org/es/packages/org.dslul.openboard.inputmethod.latin)

🟢<img src="./icons/florisboard.png" width="30">[FlorisBoard*](https://github.com/florisboard/florisboard)

Agenda :

🟢<img src="./icons/simplecalendar.png" width="30">[Simple Calendar](https://f-droid.org/es/packages/com.simplemobiletools.calendar.pro)

🟢<img src="./icons/tutanota.png" width="30">[Tutanota](https://f-droid.org/es/packages/de.tutao.tutanota)

🟢Proton Calendar*

🟢<img src="./icons/etar.png" width="30">[Etar](https://f-droid.org/es/packages/ws.xsoh.etar)

Notas :

🟢<img src="./icons/standardnotes.png" width="30">[Standard Notes](https://play.google.com/store/apps/details?id=com.standardnotes)

🟢Quillnote

🟢<img src="./icons/joplin.png" width="30">[Joplin](https://play.google.com/store/apps/details?id=net.cozic.joplin&utm_source=GitHub&utm_campaign=README&pcampaignid=MKT-Other-global-all-co-prtnr-py-PartBadge-Mar2515-1)

🟢<img src="./icons/nextcloudnotes.png" width="30">[Nextcloud Notes](https://f-droid.org/es/packages/it.niedermann.owncloud.notes)

Clima :

🟢Geometric Weather

🟢Weather

SMS :

🔴<img src="./icons/signal.png" width="30">[Signal](https://signal.org)

🔴<img src="./icons/simplesmsmessenger.png" width="30">[Simple SMS Messenger](https://f-droid.org/en/packages/com.simplemobiletools.smsmessenger/)

🔴<img src="./icons/qksms.png" width="30">[QKSMS](https://f-droid.org/en/packages/com.moez.QKSMS/)

Gestor de archivos :

🟢<img src="./icons/simplefilemanager.png" width="30">[Simple File Manager](https://f-droid.org/es/packages/com.simplemobiletools.filemanager.pro)

🟢Ghost Commander

🟢Material Files

Galería :

🟢<img src="./icons/simplegallery.png" width="30">[Simple Gallery](https://f-droid.org/es/packages/com.simplemobiletools.gallery.pro)

Reproductor de audio :

🟢<img src="./icons/vinylmusicplayer.png" width="30">[Vinyl Music Player](https://f-droid.org/es/packages/com.poupa.vinylmusicplayer)

🟢<img src="./icons/vanillamusic.png" width="30">[Vanilla Music](https://f-droid.org/en/packages/ch.blinkenlights.android.vanilla)

🟢<img src="./icons/musicplayergo.png" width="30">[Music Player GO](https://f-droid.org/es/packages/com.iven.musicplayergo)

PDF :

🟢<img src="./icons/pdfviewerplus.png" width="30">[PDF Viewer Plus](https://f-droid.org/es/packages/com.gsnathan.pdfviewer)

🟢Librera Reader

🟢KOReader

🟢<img src="./icons/mupdfviewer.png" width="30">[MuPDF Viewer](https://f-droid.org/es/packages/com.artifex.mupdf.viewer.app)

Contactos :

🟢<img src="./icons/opencontacts.png" width="30">[Open Contacts](https://f-droid.org/es/packages/opencontacts.open.com.opencontacts)

🟢<img src="./icons/simplecontacts.png" width="30">[Simple Contacts](https://f-droid.org/es/packages/com.simplemobiletools.contacts.pro)

Cámara :

🟢<img src="./icons/opencamera.png" width="30">[Open Camera](https://f-droid.org/es/packages/net.sourceforge.opencamera)

🟢<img src="./icons/simplecamera.png" width="30">[Simple Camera](https://f-droid.org/es/packages/com.simplemobiletools.camera)

Grabador audio :

🟢<img src="./icons/audiorecorder.png" width="30">[Audio Recorder](https://f-droid.org/es/packages/com.github.axet.audiorecorder)

🟢<img src="./icons/simplevoicerecorder.png" width="30">[Simple Voice Recorder](https://f-droid.org/es/packages/com.simplemobiletools.voicerecorder)

Gestor de llamadas : 

🔴<img src="./icons/simpledialer.png" width="30">[Simple Dialer](https://f-droid.org/es/packages/com.simplemobiletools.dialer)

🔴Emerald Dialer

Calculadora :

🟢<img src="./icons/simplecalculator.png" width="30">[Simple Calculator](https://f-droid.org/en/packages/com.simplemobiletools.calculator)

Reloj :

🟢<img src="./icons/simpleclock.png" width="30">[Simple Clock](https://f-droid.org/en/packages/com.simplemobiletools.clock)

Reproductor multimedia :

🟢<img src="./icons/vlc.png" width="30">[VLC](https://f-droid.org/es/packages/org.videolan.vlc/)

Para ir más lejos :

Controlador de trafico red (cortafuegos) :

🟢<img src="./icons/rethinkdns.png" width="30">[RethinkDNS*](https://play.google.com/store/apps/details?id=com.celzero.bravedns&hl=es&gl=US)

🟢<img src="./icons/inviziblepro.png" width="30">[InviZible Pro](https://f-droid.org/en/packages/pan.alexander.tordnscrypt.stable)

🟢<img src="./icons/netguard.png" width="30">[NetGuard](https://f-droid.org/es/packages/eu.faircode.netguard)

Revelador de rastreadores terceros :

🟢<img src="./icons/classyshark3xodus.png" width="30">[ClassyShark3xodus](https://f-droid.org/es/packages/com.oF2pks.classyshark3xodus)

🟢<img src="./icons/exodus.png" width="30">[Exodus](https://f-droid.org/en/packages/org.eu.exodus_privacy.exodusprivacy)

Gestor de privacidad para aplicaciones : 

🟢<img src="./icons/appmanager.png" width="30">[App Manager](https://f-droid.org/es/packages/io.github.muntashirakon.AppManager)

🟢<img src="./icons/appwarden.png" width="30">[App Warden](https://forum.xda-developers.com/t/app-5-0-warden-app-manager.4122227) (root)

Parador de aplicaciones (fondo) :

🟢<img src="./icons/rethinkdns.png" width="30">[RethinkDNS*](https://play.google.com/store/apps/details?id=com.celzero.bravedns&hl=es&gl=US)

🟢<img src="./icons/superfreezz.png" width="30">[SuperFreezZ](https://f-droid.org/es/packages/superfreeze.tool.android)

Anonimización red por Tor :

🟢<img src="./icons/orbotproxy.png" width="30">[Orbot Proxy](https://play.google.com/store/apps/details?id=org.torproject.android&hl=es&gl=US)

🟢<img src="./icons/inviziblepro.png" width="30">[InviZible Pro](https://f-droid.org/en/packages/pan.alexander.tordnscrypt.stable)

Aislador de aplicaciones :

🟢<img src="./icons/shelter.png" width="30">[Shelter](https://f-droid.org/en/packages/net.typeblog.shelter)

🟢<img src="./icons/insular.png" width="30">[Insular](https://f-droid.org/en/packages/com.oasisfeng.island.fdroid)

Detector de malware :

🟢Hypatia (ClamAV)

Alternativa a Chromecast para Raspberry Pi :

🟢Raspicast

Falsificador de localización :

🟢<img src="./icons/faketraveler.png" width="30">[Fake Traveler](https://f-droid.org/en/packages/cl.coders.faketraveler)

Reemplazo de Google Services :

🔵<img src="./icons/microg.png" width="30">[MicroG GmsCore](https://microg.org)

Bloqueador de uso del micrófono :

🟢<img src="./icons/pilfershushjammer.png" width="30">[PilferShush Jammer](https://f-droid.org/en/packages/cityfreqs.com.pilfershushjammer)

### IOS :

Navegador :

🔵<img src="./icons/firefox.png" width="30">[Firefox](https://apps.apple.com/us/app/navegador-firefox/id989804926)

🔵<img src="./icons/onionbrowser.png" width="30">[Onion Browser](https://apps.apple.com/us/app/onion-browser/id519296448)

🔵<img src="./icons/duckduckgobrowser.png" width="30">[DuckDuckGo Browser](https://apps.apple.com/us/app/duckduckgo-privacy-browser/id663592361)

🔴<img src="./icons/brave.png" width="30">[Brave](https://apps.apple.com/us/app/brave-private-web-browser-vpn/id1052879175)

Mensajería instantánea :

🟢<img src="./icons/threema.png" width="30">[Threema](https://apps.apple.com/us/app/threema-the-secure-messenger/id578665578)

🔵<img src="./icons/signal.png" width="30">[Signal](https://apps.apple.com/us/app/signal-mensajer%C3%ADa-privada/id874139669)

🟢<img src="./icons/session.png" width="30">[Session*](https://apps.apple.com/us/app/session-private-messenger/id1470168868)

🔴<img src="./icons/telegram.png" width="30">[Telegram](https://apps.apple.com/us/app/telegram-messenger/id686449807)

🔵<img src="./icons/element.png" width="30">[Element](https://app.element.io)

🔵<img src="./icons/jami.png" width="30">[Jami](https://apps.apple.com/us/app/jami/id1306951055)

🔵<img src="./icons/monal.png" width="30">[Monal](https://apps.apple.com/us/app/monal-xmpp-chat/id317711500)

Videoconferencia :

🟢<img src="./icons/jitsimeet.png" width="30">[Jitsi Meet](https://apps.apple.com/us/app/jitsi-meet/id1165103905)

🔵<img src="./icons/signal.png" width="30">[Signal](https://apps.apple.com/us/app/signal-mensajer%C3%ADa-privada/id874139669)

🟢<img src="./icons/jami.png" width="30">[Jami](https://apps.apple.com/us/app/jami/id1306951055)

🔵<img src="./icons/element.png" width="30">[Element](https://app.element.io)

🔵<img src="./icons/whereby.png" width="30">[Whereby](https://apps.apple.com/us/app/whereby-video-meetings/id878583078)

🔴<img src="./icons/telegram.png" width="30">[Telegram](https://apps.apple.com/us/app/telegram-messenger/id686449807)

Plataforma vídeo :

🔴<img src="./icons/odysee.png" width="30">[Odysee - LBRY web](https://odysee.com)

Bloqueador publicidad/rastreadores :

🟢<img src="./icons/blokada.png" width="30">[Blokada](https://apps.apple.com/us/app/blokada/id1508341781)

🟢<img src="./icons/dnscloak.png" width="30">[DNSCloak](https://apps.apple.com/us/app/dnscloak-secure-dns-client/id1452162351)

🟢<img src="./icons/lockdown.png" width="30">[Lockdown](https://apps.apple.com/us/app/lockdown-apps/id1469783711)

Mapas/navegación GPS :

🔵Magic Earth

🟢Organic Maps

🔵OsmAnd

Cliente correo : 

🔵<img src="./icons/tutanota.png" width="30">[Tutanota](https://apps.apple.com/us/app/tutanota/id922429609)

🔵<img src="./icons/protonmail.png" width="30">[ProtonMail](https://apps.apple.com/us/app/protonmail-correo-cifrado/id979659905)

Gestor de alias para correro :

🟢<img src="./icons/simplelogin.png" width="30">[Simple Login](https://apps.apple.com/us/app/simplelogin-anti-spam/id1494359858)

Cliente administrador de contraseñas :

🟢<img src="./icons/strongbox.png" width="30">[Strongbox](https://apps.apple.com/es/app/strongbox-keepass-pwsafe/id897283731) - KeePass & PwSafe

🔵<img src="./icons/bitwarden.png" width="30">[Bitwarden](https://apps.apple.com/us/app/bitwarden-gestor-de-contrase/id1137397744)

Autentificación a dos factores :

🟢<img src="./icons/tofuauthenticator.png" width="30">[Tofu Authenticator](https://apps.apple.com/us/app/tofu-authenticator/id1082229305)

🟢Raivo OTP

VPN:

🔵ProtonVPN

🟢IVPN

🔵Mullvad VPN

🔵Windscribe VPN

Cloud :

🔵<img src="./icons/kdrive.png" width="30">[Kdrive](https://www.infomaniak.com/es/kdrive)

🔴<img src="./icons/mega.png" width="30">[MEGA](https://apps.apple.com/es/app/mega/id706857885)

🟢<img src="./icons/nextcloud.png" width="30">[Nextcloud](https://nextcloud.com)

🔴<img src="./icons/cozycloud.png" width="30">[Cozy Drive](https://cozy.io)

🔴<img src="./icons/icedrive.png" width="30">[Kdrive](https://apps.apple.com/es/app/icedrive-cloud-storage/id1476402680)

Herramienta de cifrado para la nube :

🟢<img src="./icons/cryptomator.png" width="30">[Cryptomator](https://apps.apple.com/us/app/cryptomator/id953086535)

Red social respetuosa :

🔵Mastodon for iPhone

🔴<img src="./icons/telegram.png" width="30">[Telegram](https://apps.apple.com/us/app/telegram-messenger/id686449807)

🔵Element (Matrix)

Ofimática :

🟢Collabora Office

🟢LibreOffice

## 5 Navegadores

La compartimentalización (usar diferentes navegadores con diferentes configuraciones, según las tareas) es un método recomendado para preservar la privacidad sin sacrificar demasiado la comodidad de navegación.
Por ejemplo, se trataría de usar Firefox con una configuración restrictiva para la navegación general. Luego, usar otro perfil del mismo Firefox o Firefox ESR, configurado de manera menos restrictiva para los sitios que no cargan correctamente o que requieren una conexión a una cuenta personal, y otro navegador para la consulta des los sitios más recalcitrantes a una configuración para la protección de la privacidad (Brave o Ungoogled Chromium sin configuración son ideales para esa tarea). También es concebible usar otro navegador unicamente dedicado al e-banking o también Tor Browser para la navegación anónima.

### 5-1 Firefox

Para que Firefox proteja la privacidad, es necesario configurarlo de manera adecuada (ajustes, extensiones y about:config). Todas las configuraciones necesarias están desarrolladas en el punto 8.3 del documento. Estos ajustes también valen para LibreWolf y, en una cierta medida, para la versión móvil de Firefox (Fennec).

**Extensiones :**

Lista ligera :

<img src="./icons/ublockorigin.png" width="30">uBlock Origin - [Chrome](https://chrome.google.com/webstore/detail/ublock-origin/cjpalhdlnbpafiamejdnhcphjbkeiagm) - [Firefox](https://addons.mozilla.org/es/firefox/addon/ublock-origin)

<img src="./icons/decentraleyes.png" width="30">Decentraleyes - [Chrome](https://chrome.google.com/webstore/detail/decentraleyes/ldpochfccmkkmhdbclfhpagapcfdljkj) - [Firefox](https://addons.mozilla.org/es/firefox/addon/decentraleyes)

<img src="./icons/cookieautodelete.png" width="30">Cookie AutoDelete - [Chrome](https://chrome.google.com/webstore/detail/cookie-autodelete/fhcgjolkccmbidfldomjliifgaodjagh) - [Firefox](https://addons.mozilla.org/en-US/firefox/addon/cookie-autodelete)

<img src="./icons/https-everywhere.png" width="30">HTTPS Everywhere - [Chrome](https://chrome.google.com/webstore/detail/https-everywhere/gcbommkclmclpchllfjekcdonpmejbdp) - [Firefox](https://addons.mozilla.org/es/firefox/addon/https-everywhere)

Aleatorización de huella (restrictiva) :

<img src="./icons/ublockorigin.png" width="30">uBlock Origin - [Chrome](https://chrome.google.com/webstore/detail/ublock-origin/cjpalhdlnbpafiamejdnhcphjbkeiagm) - [Firefox](https://addons.mozilla.org/es/firefox/addon/ublock-origin)

<img src="./icons/decentraleyes.png" width="30">Decentraleyes - [Chrome](https://chrome.google.com/webstore/detail/decentraleyes/ldpochfccmkkmhdbclfhpagapcfdljkj) - [Firefox](https://addons.mozilla.org/es/firefox/addon/decentraleyes) - Finished development? - Alternative?

<img src="./icons/privacyredirect.png" width="30">Privacy Redirect - [Chrome](https://chrome.google.com/webstore/detail/privacy-redirect/pmcmeagblkinmogikoikkdjiligflglb) - [Firefox](https://addons.mozilla.org/en-US/firefox/addon/privacy-redirect)

<img src="./icons/canvasblocker.png" width="30">CanvasBlocker - [Chrome](https://chrome.google.com/webstore/detail/canvas-blocker-fingerprin/nomnklagbgmgghhjidfhnoelnjfndfpd) - [Firefox](https://addons.mozilla.org/es/firefox/addon/canvasblocker)

<img src="./icons/chameleon.png" width="30">[Chameleon](https://github.com/ghostwords/chameleon) Finished development? - Alternative?

### 5-2 Tor Browser

El concepto de Tor es hacer pasar el trafico internet por una red anonimizandolo. En el afán de que la huella (fingerprint) de su navegador (dada entre otros por su configuración) no traicione su identidad, los navegadores Tor son concebidos para
tener la misma huella independientemente de los usuarios. Para evitar volver única la huella de su navegador Tor, no se debe instalar ninguna extensión y tampoco realizar modificaciones en los ajustes "about:config". Para preservar el anonimato dado, también es necesario no conectarse a cuentas que podrían de facto anularlo.
El método de anonimización de la red Tor ralentiza los cargamentos. Pues no es recomendado usarlo para el streaming o las descargas voluminosas.

## 6 Instancias de servicios

### 6-1 Searx

Searx es un metabuscador que no transmite datos personales a los buscadores usados. Permite, si uno lo desea, una configuración muy avanzada. Las diferentes instancias (disponibles ahí : https://searx.space/) no ofrecen todas las mismas garantías de protección de la privacidad (log de dirección IP o no, etc.)

🔵https://searx.nobigtech.es : Google results included, IP address, log good UI

🟢https://search.disroot.org : Google results (Startpage), no IP address log, good UI

🟢https://search.disroot.org : Google results included, no IP address log

### 6-2 Invidious

Invidious da acceso al contenido Youtube (proxy) sin transmitir los datos personales de sus usuarios a Google. Lamentablemente, sus diferentes instancias (disponibles ahí : https://instances.invidio.us/) padecen frecuentemente de problemas causados por las medidas de Google tomadas para impedir su funcionamiento. La extensión Privacy Redirect redirige automáticamente los enlaces Youtube hacia Invidous.

Las instancias Invidious que parecen actualmente ser las más funcionales son

⚫https://yewtu.be

### 6-3 Videoconferencia

**Jitsi Meet :**

🟢[FDN](https://talk.fdn.fr)

🟢[Snopyta](https://talk.snopyta.org)

🟢[Framasoft](https://framatalk.org/accueil)

🟢[Calyx](https://meet.calyx.net)

🔵[Jitsi](https://jitsi.org/jitsi-meet)

🔵[Infomaniak](https://meet.infomaniak.com)

**BigBlueButton :**

🟢[FAImaison](https://bbb.faimaison.net/b)

🟢[Grifon](https://bbb.grifon.fr/b)

🟢[Nixnet](https://meet.nixnet.services/b)

### 6-4 Servidores DNS

Si usan un VPN, es recomendable no cambiar su servidor DNS por defecto, en el afán de no destacar de sus otros usuarios. En el caso contrario, reemplacen el servidor DNS proporcionado por su proveedor de internet por uno respetuoso entre las recomendaciones a continuación. Usen una implementación cifrada (DoH, DoT, DoQ, DNSCrypt, etc.) siempre que es posible.

Con filtros contra la publicidad, rastreadores y dominios maliciosos :

🟢[BlahDNS](https://blahdns.com) (DoH, DoT, DNSCrypt) (Europa y Asia Oriental)

🟢[NixNet](https://docs.nixnet.services/NixNet_DNS) (DoH, DoT) (Europa y Norteamérica)

🔵[Adguard](https://adguard.com/en/adguard-dns/overview.html) (DoH, DoT, DNSCrypt) (Europa, Norteamérica y Asia Oriental)

🔵[NextDNS](https://nextdns.io)(DoH, DoT, DNSCrypt) (intercontinental)

🔵[LibreDNS](https://libredns.gr)(DoH, DoT) (Europa)

BlahDNS DoH (Alemania) : https://doh-de.blahdns.com/dns-query

BlahDNS DoH (Singapur) : https://doh-sg.blahdns.com/dns-query

BlahDNS DoQ (Finlandia) : quic://dot-fi.blahdns.com:784

NixNet DoH (intercontinental) : https://adblock.any.dns.nixnet.xyz/dns-query

Con filtros contra los dominios maliciosos :

🟢[Quad9](https://www.quad9.net) (DoH, DoT, DNSCrypt) (solo bloquea los dominios maliciosos)

DoH : https://dns.quad9.net/dns-query

DoT : tls://dns.quad9.net

IPv4 : 9.9.9.9, 149.112.112.112

IPv6 : 2620:fe::fe, 2620:fe::9

Sin filtros :

🟢[Snopyta](https://snopyta.org) (DoH, DoT) (Europa)

🟢[Digitale Gesellschaft](https://digitalegesellschaft.de) (DoH, DoT) (Europa)

🔵[UncensoredDNS](https://blog.uncensoreddns.org/dns-servers) (DoH) (Europa y Norteamérica)

🔵[DNS.Watch](https://dns.watch) (DoH, DNSCrypt)

Snopyta DoH (Finlandia) : https://fi.doh.dns.snopyta.org/dns-query

## 7 Recursos adicionales, fuentes destacadas

**General**

Excelentes recursos para comprender el capitalismo de vigilancia y sus amenazas :

* https://www.nobigtech.es
* El dilema de las redes sociales, Jeff Orlowski (película)
* Nothing to Hide, Marc Meillassoux (documental)
* La era del capitalismo de la vigilancia, Shoshana Zuboff (libro)

Excelentes tutoriales para la privacidad y la protección de datos :

básico :

* https://spreadprivacy.com/tag/device-privacy-tips
* https://www.vice.com/en_us/article/d3devm/motherboard-guide-to-notgetting-hacked-online-safety-guide

completo :

* https://dt.gl/privacy-cookbook-the-story-so-far/

Excelentes canales acerca de la privacidad (con tutoriales) :

* The Hated One : https://www.youtube.com/channel/UCjr2bPAyPV7t35MvcgT3W8Q
* Techlore : https://www.youtube.com/channel/UCs6KfncB4OV6Vug4o_bzijg

Asociaciones para la defensa de la privacidad (informaciones) :

* https://ssd.eff.org/
* https://www.laquadrature.net/es/
* https://www.eff.org/deeplinks

Asociaciones proponiendo excelentes servicios respetuosos de la privacidad :

* https://disroot.org/es/
* https://komun.org/
* https://framasoft.org/en/
* https://snopyta.org/
* https://www.drycat.fr/en

Excelente sitio listando servicios y programas respetuosos :

* https://www.privacytools.io/

Comparativos de recomendables :

* https://www.eff.org/pages/quien-defiende-tus-datos

**Grupos y canales Telegram (y Matrix)**

Privacidad, protección de datos y más :

* [t.me/privacidadlibre](t.me/privacidadlibre) y #privacidadlibre:matrix.org
* [t.me/techloregroup](t.me/techloregroup) y #techlore:matrix.org
* [t.me/techloreofficial](t.me/techloreofficial) (cuidado, sesgo pro Apple)

Linux y libre :

* [Proyecto tic tac](t.me/grupo_telegram_proyectotictac)
* [LinuxMintEs](t.me/LinuxMintEs)
* [mxantixes](t.me/mxantixes)

**Sistemas operativos**

Linux :

* [MX Linux](https://mxlinux.org)
* [Linux Mint](https://linuxmint.com)

Android respetuoso de la privacidad :

* [CalyxOS](https://calyxos.org)
* [GrapheneOS](https://grapheneos.org)
* [/e/ OS](https://e.foundation)
* Compatibilidad de las aplicaciones con y sin microG : (https://plexus.techlore.tech)

**Firefox**

* [Configuración Firefox](https://www.youtube.com/watch?v=tQhWdsFMc24)
* [Configuración Firefox básica](https://12bytes.org/articles/tech/firefox/the-firefox-privacy-guide-for-dummies)
* [Configuración Firefox avanzada](https://12bytes.org/articles/tech/firefox/firefoxgecko-configuration-guide-for-privacy-and-performance-buffs)

## 8 Configuraciones

### 8-1 Sistemas operativos

**Android**

Las siguientes recomendaciones son imperfectas y no garantizan totalmente la protección de datos, pues es recomendado usar una versión de Android modificada para la privacidad en vez de Android de origen. Siendo dicho esto, en el afán de no estar perfilado de manera completa y continua con Android de origen, seguir las siguientes recomendaciones :

* Evitar todas las marcas chinas o Samsung y preferir una marca, como Nokia, proponiendo “Android One” (es decir sin capa adicional del fabricante)
* Nunca conectarse con una cuenta Google
* Usar aplicaciones para poder instalar aplicaciones sin Google Play Store
* Instalar y usar una aplicación, como RethinkDNS o Blokada, que permite bloquear los rastreadores así como la publicidad y usar un servidor DNS respetuoso cifrado
* Reemplazar el teclado por defecto por uno respetuoso
* Eliminar (o cuando no es posible desactivar) todas las aplicaciones nefastas (Google, antivirus tercero, etc.) o no usadas
* Bloquear el acceso internet de todas las aplicaciones desactivadas o que no requieren un acceso internet para funcionar gracias a una aplicación firewall como RethinkDNS
* Revisar todas las autorizaciones de aplicaciones y del sistema para retirarlas si son nefastas para la privacidad o innecesarias

**GrapheneOS**

Aprovechen la función oferta unicamente por GrapheneOS para quitarles la autorización del acceso a los sensores (usado insidiosamente para la recolección de informaciones y el rastreo) a todas las aplicaciones comerciales o de código cerrado y también de las que no lo necesitan, por precaución :

“Configuraciones” > “Apps y notificaciones“ > escoger una app > “Permisos” > “Sensors” > “Ver todas las apps que tienen este permiso”

**Windows**

Las siguientes recomendaciones son imperfectas y no garantizan la protección de datos, pues es recomendado usar una distribución de Linux en vez de
Windows. Siendo dicho esto, en el afán de no estar perfilado de manera completa y continua con Windows, seguir las siguientes recomendaciones :

* No usar ninguna versión anterior a Windows 10 pues son vulnerables/inseguras
* Nunca conectarse con una cuenta Microsoft
* Desactivar totalmente Cortana
* Desactivar el historial de actividad
* Ir en los ajustes, bajo “privacidad” y desactivar todo en cada una de las categorías a excepción de la autorizaciones necesarias para las aplicaciones usadas
* Desinstalar (o cuando no es posible desactivar) Edge, Microsoft OneDrive, los antivirus (a excepción de Microsoft Defender) y todas las aplicaciones no usadas
* Activar la dirección MAC aleatoria en los ajustes de la Wi-Fi
* Preferiblemente usar otra sesión que la administradora para el uso a diario
* Instalar el programa ShutUp10 para tener un mayor control sobre la privacidad

**MX Linux**

Plugin Flash :
Entrar el comando siguiente en la terminal para eliminar el plugin Flash propietario :
sudo apt purge --remove adobe-flashplugin flashplugin-installer pepperflashplugin-nonfree

Advert Blocker (Bloquear-publicidad) :
Seleccionar todas las opciones a excepción de “UNBLOCK” y luego confirmar.

Configuración Wi-Fi :
Clic derecho en el icono Wi-Fi, modificar las conexiones, seleccionar el Wi-Fi activo, bajo Wi-Fi seleccionar Dirección MAC clonada : Aleatoria.
Bajo ajustes IPv6, seleccionar Extensiones de confidencialidad IPv6 : Activado (dirección temporal preferida).

### 8-2 F-Droid

Para poder encontrar y descargar algunas aplicaciones desde F-Droid, es necesario agregar sus repositorios. Para esto, ir a los ajustes de F-Droid,luego bajo "repositorios", activar el repositorio "Guardian Project" y por fin presionar el "+" y entrar las direcciones mencionadas deseadas :

* Bromite :
https://fdroid.bromite.org/fdroid/repo

* Mull :
https://divestos.org/fdroid/official

* Ungoogled Chromium :
https://www.droidware.info/fdroid/repo

* Newpipe :
https://archive.newpipe.net/fdroid/repo

Puede suceder que Newpipe deje de funcionar por causa de modificaciones de parte de Google en Youtube. En el afán de beneficiar rápidamente de las últimas actualizaciones corrigiendo esos problemas, es recomendado añadir el propio repositorio de Newpipe.

* Langis (Signal) :
https://gitlab.com/TheCapsLock/fdroid-patched-apps/raw/master/fdroid/repo

Langis es una versión modificada de Signal a utilizar como último recurso si las notificaciones no llegan con la versión clásica de Signal de Aurora Store.

* Session :
https://fdroid.getsession.org/fdroid/repo

* Bitwarden :
https://mobileapp.bitwarden.com/fdroid/repo

Versión sin los rastreadores terceros presentes en la versión de Google Play.

* Nebulo :
https://fdroid.frostnerd.com/fdroid/repo

* Collabora Office :
https://www.collaboraoffice.com/downloads/fdroid/repo


### 8-3 Aplicaciones y programas

**Telegram**

Empezar chats secretos para que las conversaciones sean cifradas de extremo a
extremo y no pasen por los servidores de Telegram :
perfiles de los contactos > los tres puntos arriba > empezar chat secreto

Desactivar la vista previa de enlaces en chats secretos para evitar solicitar los
servidores de Telegram :

Ajustes> Privacidad y seguridad > Chats secretos > Vista previa de enlaces

**Blokada**

Blocklists > activar las listas negras siguientes :

- OISD
- Phishing Army
- DuckDuckGo Tracker Radar
- Exodus Privacy
- Combined Privacy
- URLhaus
- (Goodbye Ads : Samsung o Xiaomi (solo sirven para los modelos de esas marcas))

Encryption > seleccionar un servidor DNS dentro de los siguientes :
DoH : Blah DNS, Digitale Gesellschaft(Europa), (OpenNIC).
((No cifrado : DNS.Watch, Uncensored DNS, French Data Network(Europa))).

**FreeTube**

Utiliser Invidious comme proxy pour éviter de transmettre ses données à Google :

Settings :
- Player Settings : activer "Proxy Videos Through Invidious"
- Advanced Settings : entrer une instance Invidious fonctionnelle

En cas de problème, changer d’instance ou tout simplement désactiver "Proxy Videos
Through Invidious".

### 8-4 Firefox

**Configuración general**

La configuración propuesta ahí abajo siendo relativamente restrictiva en el afán de proteger la privacidad del usuario, es recomendado seguir la compartimentalización propuesta en el punto 5 del documento y así usar por lo menos un otro navegador para poder acceder a los sitios menos respetuosos de la privacidad.

Perfiles :

Firefox ofrece la posibilidad de usar varios perfiles (configuraciones) diferentes al  mismo tiempo. Se trata de una solución ideal para una transición rápida y simple desde una configuración restrictiva impidiendo una página web de cargar correctamente hacia una configuración más ligera, sin tener que cambiar de navegador. Los diferentes ajustes aportados, extensiones instaladas o marcadores añadidos serán guardados en el perfil en uso.

Para acceder a los diferentes perfiles de Firefox, entrar "about:profiles" en la barra de búsqueda. Esta página les permite crear nuevos perfiles y luego lanzarlos en una nueva ventana independiente en cualquier momento.

DNS over HTTPS :

Si usan un VPN o si su red o computadora son configurados para usar globalmente un servidor DNS respetuoso y cifrado, se debe desactivar la función "DNS over HTTPS" activada por defecto en Firefox. Si no es el caso (si no lo saben, probablemente no es el caso), es recomendado dejar esta función activada. Ahora bien, es necesario cambiar el servidor DNS por defecto ya que Cloudflare es un actor centralizador y nefasto para la privacidad. En lugar de este último, es recomendado escoger una opción respetuosa propuesta en el punto 6.4 del documento, en función de sus
preferencias y ubicación.

Para esto : ajustes de Firefox > "General" > abajo "Ajustes red" > abajo "Activar DNS
over HTTPS".

A continuación, el resto de la configuración general recomendada en imágenes :

<img src="https://raw.githubusercontent.com/adgellida/data-protection-list/master/images/1.png" width="750">
<img src="https://raw.githubusercontent.com/adgellida/data-protection-list/master/images/2.png" width="750">
<img src="https://raw.githubusercontent.com/adgellida/data-protection-list/master/images/3.png" width="750">
<img src="https://raw.githubusercontent.com/adgellida/data-protection-list/master/images/4.png" width="750">
<img src="https://raw.githubusercontent.com/adgellida/data-protection-list/master/images/5.png" width="750">
<img src="https://raw.githubusercontent.com/adgellida/data-protection-list/master/images/6.png" width="750">

**Configuración de las extensiones**

Es importante autorizar esas extensiones a funcionar en navegación privada y activar
sus actualizaciones automáticas.

uBlock :
- Settings : activar todo bajo “Privacy”
- Filter Lists : activar TODAS las listas, excepto bajo “Regions” (solo activar para los idiomas usados)
- (Agregar las listas de filterlists.com : Energized : Ultimate Protection, Xtreme + IP + Social extension)
- Seguir el tutorial de la página web siguiente para establecer las reglas de filtración
dinámica (opcional pero recomendado) :

https://www.maketecheasier.com/ultimate-ublock-origin-superusers-guide/

Chameleon :

<img src="https://raw.githubusercontent.com/adgellida/data-protection-list/master/images/11.png" width="450"><img src="https://raw.githubusercontent.com/adgellida/data-protection-list/master/images/22.png" width="450">
<img src="https://raw.githubusercontent.com/adgellida/data-protection-list/master/images/33.png" width="450"><img src="https://raw.githubusercontent.com/adgellida/data-protection-list/master/images/44.png" width="450">
<img src="https://raw.githubusercontent.com/adgellida/data-protection-list/master/images/55.png" width="450">

Decentraleyes :
Ninguna configuración necesaria

CanvasBlocker :
General : - marcar "Expert mode"
          - Presets > open > Stealth mode
          - Random number generator : non persistent
APIs : marcar "Protect Window api" + aceptar excepción captcha
Misc : desmarcar "Block data URL pages"

ClearURLs :
request types:
beacon,csp_report,font,image,imageset,main_frame,media,object,object_subrequest,other,ping,script,speculative,stylesheet,sub_frame,web_manifest,websocket,xbl,xml_dtd,xmlhttprequest,xslt

Cookie AutoDelete :
- Automatic Cleaning Options : activar todo
- Extension Options : desactivar “Show notification after cookie cleanup”

Privacy Redirect :
General : - seleccionar las instancias deseadas
Advanced : - activar “Always proxy videos through Invidious”
- Seleccionar “DASH” bajo “Invidious video quality”

(HTTPS Everywhere) :
- Solo necesario para las versiones de Firefox en las cuales el “HTTPS-Only Mode” todavía no esta implementado : Firefox ESR y móvil (Fennec)
- Ninguna configuración necesaria

**Configuraciones about:config**

Acceder a estos ajustes entrando about:config en la barra de direcciones de Firefox.
Esas diversas configuraciones mejoran la privacidad, la seguridad y el rendimiento.
Los elementos entre paréntesis no suelen ser deseables en todos los casos.

accessibility.blockautorefresh = true

((accessibility.force_disabled = 1))

beacon.enabled = false

browser.cache.offline.capacity = 0

browser.cache.offline.enable = false

browser.display.use_document_fonts = 0

browser.send_pings.max_per_link = 0

browser.sessionhistory.max_entries = 15

Numero máximo de paginas disponibles con "precedente", aligera Firefox

browser.sessionhistory.max_total_viewers = 4

Numero máximo de paginas cargadas con "precedente", aligera Firefox

browser.sessionstore.interval = 50000

browser.sessionstore.privacy_level = 2

(browser.startup.homepage_override.buildID = borrar)

browser.urlbar.autofill.enabled = false

(browser.urlbar.maxRichResults = 0)

browser.urlbar.speculativeConnect.enabled = false

browser.urlbar.trimURLs = false

browser.xul.error_pages.expert_bad_cert = true

captivedetect.canonicalURL = borrar

device.sensors = false para todos los elementos

dom.allow_cut_copy = false

dom.battery.enabled = false

dom.enable_performance = false

dom.enable_resource_timing = false

dom.event.clipboardevents.enabled = false

dom.event.contextmenu.enabled = false

dom.push = false para todos los elementos + borrar las direcciones e identificadores

dom.serviceWorkers.enabled= false

dom.vr.oculus.enabled = false

dom.webaudio.enabled = false

gamepad = false para todos los elementos

geo = borrar todas las direcciones

geo.enabled = false

(gfx.font_rendering.graphite.enabled = false)

google = false para todos los elementos + borrar las direcciones

javascript.options.baselinejit = false

javascript.options.ion = false

javascript.options.native_regexp = false

layers.acceleration.force-enabled = true

layout.css.visited_links_enabled = false

mathml.disabled = true

((media.gmp-widevinecdm.enabled = false))

((Desactiva DRM, sí videos DRM no necesarias))

media.navigator.enabled = false

media.video_stats.enabled = false

network.captive-portal-service.enabled = false

network.dnsCacheEntries = 4000

network.dnsCacheExpiration = 43200

network.dnsCacheExpirationGracePeriod = 43200

network.IDN_show_punycode = true

network.http.referer.XOriginPolicy = 0

network.http.referer.XOriginTrimmingPolicy = 2

network.http.referer.spoofSource = true

network.http.referer.trimmingPolicy = 2

network.http.speculative-parallel-limit = 0

network.manage-offline-status = false

normandy = false para todos los elementos + borrar las direcciones e identificadores

pocket = false para todos los elementos + borrar las direcciones e identificadores

privacy.clearOnShutdown.offlineApps = true

privacy.spoof_english = 2

privacy.trackingprotection.socialtracking.enabled = true

report (reporter/reporting) = false para todos los elementos + borrar las direcciones

safebrowsing = false para todos los elementos + borrar direcciones e identificadores

security.cert_pinning.enforcement_level = 2

security.mixed_content.upgrade_display_content = true

security.OCSP.enabled = 0

security.ssl.enable_false_start = false

security.ssl.enable_ocsp_must_staple = false

security.ssl.enable_ocsp_stapling = false

security.ssl.require_safe_negotiation = true

security.ssl3.rsa_des_ede3_sha = false

security.tls.enable_0rtt_data = false

security.tls.version.min = 3

telemetry = false para todos los elementos + borrar las direcciones e identificadores

ui.use_standins_for_native_colors = true

webgl.disabled = true

webgl.enable-debug-renderer-info = false

webgl.enable-webgl2 = false

**Solo si no se usa la extensión Chameleon :**

(privacy.resistFingerprinting = true)

(Mejor poner "false" y falsificar el fingerprint con Chameleon)

Estos deberían ser configurados directamente con Chameleon sí esta instalado :

media.peerconnection.ice.default_address_only = true

media.peerconnection.ice.no_host = true

((media.peerconnection.enabled = false))

privacy.firstparty.isolate = true