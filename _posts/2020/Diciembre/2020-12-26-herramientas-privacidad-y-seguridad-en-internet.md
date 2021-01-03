---
title: "Aplicaciones para la seguridad y privacidad online."
layout: post
date: 2020-12-26 23:06
image: /assets/images/media/headerpost.png
headerImage: true
tag:
- seguridad
- bitwarden
- keepass
- 2FA
- authenticator
- telegram
- signal
- brave
- firefox
- windscribe
- VPN
- GitJournal
- cryptomator
- 7zip
- protonmail
- veracrypt
- GPG
- PGP
star: false
category: blog
author: Euri
description: Herramientas recomendadas para proteger nuestra pivacidad y una pequeña explicación de cómo funcionan.
permalink: pretty
---

Ya se viene un año nuevo, y para año nuevo, prácticas de seguridad y privacidad nuevas… Hace tan sólo unos pocos años solía ser de aquellas personas que utilizan una sola contraseña para TODO, correo, redes sociales, móvil, ordenador, etc… y debo admitir que es muy cómodo… e inseguro, y es que a medida que reflexionaba y escuchaba consejos me pude dar cuenta que esto puede llegar a ser más que peligroso, así que decidí solucionarlo y en tan sólo un par de semanas pude encontrar soluciones bastante interesantes.

Cabe resaltar que todas las aplicaciones mencionadas son Libres o de Código Abierto, algo importante, casi obligatorio en cualquier software centrado en la seguridad.


## Gestor de contraseñas Bitwarden.

Uno de los requisitos más importantes al momento de registrarnos en alguna página son las contraseñas, las cuales deben ser únicas, seguras y estar bien protegidas; para eso se crearon los gestores de contraseñas como [Bitwarden](https://bitwarden.com/) que además de almacenar nuestras contraseñas cifradas y gestionarlas, también nos ofrece almacenamiento de notas encriptadas y tarjetas de débito/crédito, identificación e integración con todos los navegadores, sistemas operativos móviles y de escritorio e incluso la posibilidad de montar el backend por nuestra cuenta.

![](https://play-lh.googleusercontent.com/dlpLD3NuvaxUAUx5j3xNVBfjxAHeS59AaHFEq9NX04v1dQgJZsaZznyrll8hIWPVE9c=w720-h310-rw) ![](https://play-lh.googleusercontent.com/v7Yggb0UPZadBckLSRGxp6dHVwXQ6NJksU_dFVLxC3ZZ8zIGm4n0O-s5v6SKB6uNOw=w720-h310-rw) ![](https://play-lh.googleusercontent.com/Dyq6M5ij-K4_G1GtOYxuBj5MpFxIi7H2-ITo-hNh99GT8RozPDd1SimuNwx8AJbo9Go=w720-h310-rw) ![](https://play-lh.googleusercontent.com/SiPHPtVFSKSFDoip-DQFRiwYZN36ef5QVB50NITuyxONkko_3dAZHKgE4xj4XuANfw=w720-h310-rw)


## Autenticación de dos factores (pasos).

Un método de protección de nuestras cuentas es la verificación en dos pasos o factores, ésto lo que hace es requerir además de la contraseña, algun otro tipo de identificador que sólo nosotros podamos proporcionar, ésto puede ser un código enviado por SMS a nuestro número telefónico, un email de confirmación, una llave física o un código expirable y autogenerado por algún dispositivo nuestro.

Es muy importante tener en cuenta que tanto las _carrier calls_ (llamadas por medio del operador telefónico) y los SMS **NO ESTÁN CIFRADAS Y PUEDEN SER INTERVENIDAS**, eso significa que cualquier persona capaz puede interceptar nuestros mensajes y llamadas sin que nos demos cuenta de ello y al no estar cifrados, puede ver el contenido; además, el intruso puede pedir un reemplazo de nuestra tarjeta SIM y hacerse con nuestro número para verificar la identidad o hasta reestablecer contraseñas; por este motivo no es recomendable establecer nuestro número de teléfono como método de verificación en dos factores.

Para autenticarnos tenemos las aplicaciones Autenticator, disponibles para Android y iOS:

### Authenticator Pro (Android).

Cuenta con licencia libre [GPLv3](https://www.gnu.org/licenses/gpl-3.0.en.html), protección de acceso con contraseña y huella digital, copias de seguridad cifradas, organización de categorías, e incluso puede instalarse en relojes inteligentes y otros wereables.

Es desarrollada por [jmh](https://github.com/jamie-mh/AuthenticatorPro), y puedes [descargarla desde aquí](https://play.google.com/store/apps/details?id=me.jmh.authenticatorpro&hl=en_US&gl=US).

![](https://play-lh.googleusercontent.com/Kgp5NL_cBossTAbpIV2hW1rbHPJCuBDP6sM2M2kTAull-duTvW0Yg8cEu39ggyPHE-5i=w720-h310-rw) ![](https://play-lh.googleusercontent.com/z7cfn1yQqOENIru47mxHL740VmTv0MFRlboi3Yq4sbSrxj8FPVNmYllnQ4J7uQKZHw=w720-h310-rw) ![](https://play-lh.googleusercontent.com/Unb2WhY_7HdOqi4E2QrP-SlZaZ-TMBUT6SCewad0FIm1BqTVHn5Jzqw4HDqkayhXWA=w720-h310-rw) ![](https://play-lh.googleusercontent.com/5wAszpPU3Lb0Nf7UTeb3G5mfq_dU9RfaZWOA-nKt-ABB0w6I0yqzsPhIpyyQTxZNMdU=w720-h310-rw)

Como alternativa también tenemos la aplicación [Aegis](https://play.google.com/store/apps/details?id=com.beemdevelopment.aegis).

### Authenticator (iOS).

Liberada bajo licencia [MIT](https://mit-license.org/), incluye prácticamente todas las carácteristicas de la aplicación de Android, además está diseñada para estar aislada de internet.
(Como aclaración, yo no tengo ningún dispositivo iOS y jamás la he utilizado.)

Es desarrollada por[ Matt Rubin](https://mattrubin.me/authenticator/) y puedes [descargarla desde aquí](https://apps.apple.com/us/app/authenticator/id766157276).

![](https://mattrubin.me/authenticator/img/ScreenshotMain.png) ![](https://mattrubin.me/authenticator/img/ScreenshotScanToken.png) ![](https://mattrubin.me/authenticator/img/ScreenshotAddToken.png)

Como alternativa también tenemos la aplicación [Tofu Authenticator](https://apps.apple.com/us/app/tofu-authenticator/id1082229305).


## Mensajería instantánea.

Muchos, por no decir todos, usamos a diario la mensajería instantánea, ya sea WhatsApp, Messenger, Line, Viber, Snapchat, WeChat, entre otros… Lo muchos de nosotros posiblemente no sepamos, es que las principales aplicaciones de mensajería que usamos día a día no son realmente seguras, no tienen cifrado alguno o éste cifrado se rompe.

Messenger, (Usado en Facebook e Instagram), por ejemplo, no tienen ninguna especie de cifrado, y el contenido de las conversaciones es analizado con fines de espionaje y publicidad, algo sumamente delicado, especialmente si somos de las personas que suelen compartir fotografías íntimas, ya que esas fotografías [NUNCA SE ELIMINAN](https://www.genbeta.com/redes-sociales-y-comunidades/instagram-mantuvo-sus-servidores-fotos-mensajes-eliminados-durante-ano) de los servidores de Facebook.

Por su parte WhatsApp a pesar que supuestamente está cifrado de extremo a extremo, se han demostrado [puertas traseras](https://telegra.ph/Why-Using-WhatsApp-Is-Dangerous-01-30-4) colocadas intencionalmente para colaborar con agencias de espionaje y gobiernos (como la SIA, NSA, FBI, etc...), además de ser SUMAMENTE SENCILLO [acceder a los mensajes de alguien](https://telegra.ph/why-whatsapp-will-never-be-secure-05-15), debido a las copias de seguridad **no cifradas en Google Drive y Apple iCloud**, inclusive, hasta hace poco iCloud cifraba todos los archivos subidos a la plataforma, pero el [cifrado fue retirado después de problemas con el FBI](https://www.reuters.com/article/us-apple-fbi-icloud-exclusive/exclusive-apple-dropped-plan-for-encrypting-backups-after-fbi-complained-sources-idUSKBN1ZK1CT) (les molesta nuestra privacidad).

Y es que este articulo no trata de ello, por favor, **elimina tu cuenta de facebook** (Facebook, Instagram y WhatsApp).

<script async src="https://telegram.org/js/telegram-widget.js?14" data-telegram-post="EuriNaiz/22" data-width="100%"></script>

### Telegram Messenger.

Quizás es la aplicación de mensajería más popular después de WhatsApp, y merecido lo tiene, siendo sumamente segura, fácil de usar, la completa en cuanto a funcionalidades (sí, más que WhatsApp o Messenger).

En Telegram podemos crear grupos de más de 100.000 usuarios, enviar archivos de hasta 2GB, imágenes que se autodestruyen después de verlas, canales con suscriptores ilimitados, multiples sesiones activas sin necesidad de tener nuestro móvil conectado a internet, aplicaciones para Android, GNU/Linux, MacOS, iOS, Windows, y muchas otras plataformas más[^1], chats de voz (sí, así como en Discord), [plataforma de blogs](https://telegra.ph/), etc....

Además tenemos disponibles los **chats secretos** que están cifrados de extremo a extremo (a diferencia de los grupos, canales y conversaciones privadas que usan el cifrado [MTProto](https://core.telegram.org/mtproto), propio de telegram), en los cuales nuestros mensajes no se guardan en los servidores de Telegram, podemos establecer la autodestrucción automática de los mensajes tras el paso de cierto tiempo, no es posible tomar capturas de pantalla ni reenviar los mensajes.

Telegram ha sido usado para [organizar protestas](https://www.theguardian.com/world/2020/nov/01/telegram-belarus-protesters-pressure-lukashenko) en paises con poca o nula libertad de expresión; y ha tenido [problemas con gobiernos](https://www.theverge.com/2020/6/29/21306691/telegram-russia-ban-evaded-washington-post-go-read-this) por negarse a entregar datos, además de estar desarrollada por una organización sin fines de lucro bajo licencias libres[^2]; lo cual da fé de la seguridad y compromiso por la privacidad.

Otro dato curioso es que Mark Zuckerberg, cofundador de Facebook, usa Telegram (Su perfil es [@zuckerberg](https://t.me/zuckerberg), por si queréis ir a decirle algo)… Lo cual es preocupante (en cuanto a WhatsApp) y deja mucho que pensar que el propio dueño no [confíe en su propia aplicación](https://www.dailymail.co.uk/news/article-4135958/Mark-Zuckerberg-DOESN-T-use-Facebook-himself.html).

![](https://play-lh.googleusercontent.com/shqQKbsBIGC3kzpav3kekZCBQ0dNUsrZja93Fte01p-dVw_9mo-fNOXaeKNCUclNYPk=w720-h310-rw) ![](https://play-lh.googleusercontent.com/31ZNmmQ2fcTRju8F9K9RaYRKRzGR-tlH4FfjvkPKkzcwATp0C25P-fUgZpDf2Xw914R9=w720-h310-rw) ![](https://play-lh.googleusercontent.com/lE-yVAcjm1rfr2TGIquOJ6vdkIR96VqW9AHPenKfUjjJr5L6kePiy-atQjC8e4kQ_RQ=w720-h310-rw)

Podemos descargar telegram desde su [página](https://telegram.org/), o desde las tiendas [Google Play](https://play.google.com/store/apps/details?id=org.telegram.messenger) y [Apple Store](https://apps.apple.com/app/telegram-messenger/id686449807).

[^1]:  Mediante aplicaciones no oficiales.
[^2]: Solamente las aplicaciones, el código fuente del servidor no está disponible para todos.

### Signal Messenger.

También es desarrollado por una organización sin fines de lucro, y de hecho está desarrollada principalmente por el Moxie Marlinkspike, fundador de Open Whisper Systems y Brian Acton, cofundador de WhatsApp, quien ya ha dicho que [dejemos de usar facebook](https://money.cnn.com/2018/03/20/technology/business/whatsapp-delete-facebook/index.html) (y por tanto WhatsApp e Instagram) con el hashtag #deletefacebook…

Así que podemos considerar a signal como el sucesor de WhatsApp, limpio de las asquerosas manos de Mark Zuckerberg y Facebook; ya que es prácticamente identico, pero con la diferencia de ser realmente seguro, y no tener estados o stories.

Signal es usado por [periodistas](https://freedom.press/training/locking-down-signal/), [políticos](https://www.theverge.com/2020/2/24/21150918/european-commission-signal-encrypted-messaging), [fuerzas armadas](https://www.militarytimes.com/flashpoints/2020/01/23/deployed-82nd-airborne-unit-told-to-use-these-encrypted-messaging-apps-on-government-cellphones/), [activistas y protestantes](https://www.nytimes.com/2020/06/11/style/signal-messaging-app-encryption-protests.html), y hasta por el mismísimo [Edward Snowden](https://www.newsweek.com/bad-news-fbi-edward-snowdens-favorite-chat-app-signal-just-got-50m-funding-816035); Está liberado bajo licencia GPLv3 (el cliente) y AGPLv3 (el servidor), así que siempre podremos examinar su código fuente, modificarlo y estar seguros que no hay puertas traseras o reportar cualquier fallo de seguridad de día cero.

![](https://play-lh.googleusercontent.com/WqG17neVpMfulukHQwTYSXPJqlJIEwL75g4uWmS0MgUYRS_ra0qnD-RmzFSdePG72WIf=w720-h310-rw) ![](https://play-lh.googleusercontent.com/D_tx9EYKOwZp68AVwBYio9J2nmmhtynzd_PyeHFCCKkJA7whIjnb7jY15R_mqUWGv4g=w720-h310-rw) ![ ](https://play-lh.googleusercontent.com/M8oHCF_J39irY3nkFETeWWOFaA6Ux7plAyBLlK4PViO7svYp8TW2y-dedGl4A4UHRQ=w720-h310-rw) ![ ](https://play-lh.googleusercontent.com/F8_xy1J1skAKaeAM3c930-e8LBVERcIVz8i4fAh7zaSfE473eZreK_1TROh5_XfsUwsl=w720-h310-rw)


## Navegador web.

Actualmente el navegador web es posiblemente la aplicación[^3] más utilizada, y por tanto es muy importante la seguridad del mismo, actualmente el navegador más utilizado es Google Chrome, pero no es el más seguro, por qué además de monopolizar la web y construír un internet exclusivamente por y para Google; también tiene integración y _tracking_ por parte de Google, un claro ejemplo de ello es la sincronización del historial de navegación, ubicación, extensiones, y hasta de contraseñas…

Para evitar eso, han surgido navegadores centrados en la privacidad, extensiones del navegador y hasta móviles _"De-Googled_ a los que se les remueven los servivios y apps de google con el motivo de hacerlos más seguros, pero eso es tema para otro post.

[^3]: De escritorio

### Mozilla Firefox.
