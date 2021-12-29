<a href="https://github.com/adgellida/data-protection-list/blob/main/READMEfrFR.md" target="_blank"><img src="https://raw.githubusercontent.com/adgellida/data-protection-list/main/images/languages/france.png" width="80" img align="right"></a>
<a href="https://github.com/adgellida/data-protection-list/blob/main/READMEesES.md" target="_blank"><img src="https://raw.githubusercontent.com/adgellida/data-protection-list/main/images/languages/spain.png" width="80" img align="right"></a>
<a href="https://github.com/adgellida/data-protection-list" target="_blank"><img src="https://raw.githubusercontent.com/adgellida/data-protection-list/main/images/languages/united-kingdom.png" width="80" style="vertical-align:middle;margin:0px 50px" img align="right"></a>

<img src="https://raw.githubusercontent.com/adgellida/data-protection-list/main/images/privacy-first.png" width="80"> data-protection-list
=============================================

Manual of resistance to surveillance capitalism

# Index

* [0 Comments about fork](#0-comments-about-fork)
* [1 Introduction](#1-introduction)
* [2 Golden rules](#2-golden-rules)
* [3 Computer](#3-computer)
* [3-1 Operating Systems](#3-1-operating-systems)
* [3-2 Services and programs](#3-2-services-and-programs)
* [4 Smartphone](#4-smartphone)
* [4-1 Operating Systems](#4-1-operating-systems)
* [4-2 Applications](#4-2-applications)
* [5 Browsers](#5-browsers)
* [5-1 Firefox](#5-1-firefox)
* [5-2 Tor Browser](#5-2-tor-browser)
* [6 Service instances](#6-service-instances)
* [6-1 Searx](#6-1-searx)
* [6-2 Invidious](#6-2-invidious)
* [6-3 Videoconference](#6-3-videoconference)
* [6-4 DNS Servers](#6-4-dns-servers)
* [7 Additional resources (featured sources)](#7-additional-resources-featured-sources)
* [8 Configurations](#8-configurations)
* [8-1 Operating systems](#8-1-operating-systems)
* [8-2 F-Droid](#8-2-f-droid)
* [8-3 Apps and software](#8-3-apps-and-software)
* [8-4 Firefox](#8-4-firefox)

## 0 Comments about fork

I have seen the need to fork this document of **Valentin Delacour** hosted [here](https://codeberg.org/PrivacyFirst/PrivacyFirst/issues) under his approval and license to give it more visibility, readability, comfort, improvement in some aspects and participation. If someone else forks both his and this one, they should do the same

I think that we should share how much more the better and the knowledge about good practices to follow regarding security, privacy and open source that are detailed are no exception.

We are open to changing the format of this document, for now I have thought that this is a good way, but it could be improved.

I don't consider myself an expert on the subject. In fact I do not follow all the recommendations to the letter. But I would like over time to leave aside services that I think I should not use for various reasons, change ways of accessing certain content, use other strategies, etc.

To actively participate you can:

* [Create pull requests](https://github.com/adgellida/data-protection-list/pulls)
* [Generate your questions or incidents](https://github.com/adgellida/data-protection-list/issues)

I recommend you participate in:

* [Official Telegram Group](https://t.me/privacid)
* [Official Discord Group](https://discord.gg/b9ey65Q) - Although due to various privacy and security reasons we do not recommend it.
* Official Element group - #privacidadlibre:matrix.org - Request invitation

The objective of the group is to collectively promote good customs in terms of privacy, security and also open source/free programs/apps, services and operating systems to resist the collection and exploitation of personal data by private companies.

I think that they take advantage of the ignorance of the majority to do things that they should not and benefit from it behind our backs. The good thing is that there are people who realize it because they understand the subject and share it with the community.

This document has been copied 1: 1 with very slight modifications in version 7/12/2020 and from now on it will undergo modifications following the following strategies:

* Following updates of the original file
* Pull requests from the community
* Own discoveries

The most notable improvements are:

* It encourages a more orderly, effective, public participation
* Images of the apps to better identify them
* Links to them to find them quickly

Now, the document begins. Put on your belt curves are coming!

## 1 Introduction

The main objective of this document is to propose tools and alternatives to protect data and privacy from predation by private companies under the current system of surveillance capitalism. Now, follow the following
recommendations also allows to improve, in certain measures, the protection against other entities such as state services or pirates, for example.

This list is intended for all persons aware or aware of the importance of data protection in our society, regardless of your knowledge of the subject. It is not intended for people needing anonymity total part of their function to risks such as political opponents or some journalists, even if some proposed options might suit them. Effectively, privacy does not necessarily equal anonymity.

The list format was chosen in order to make your query as efficient as possible possible. This approach precludes detailing true explanations. So I invite you to look for the ones they need on their own or in additional resources mentioned in point 6 of the document. With the purpose of proposing the more reputable and practical options without being too stuffy, the list does not have to vocation to be exhaustive and remains subjective despite seeking to have the greatest possible objectivity.

This list proposes a first prioritization (order of appearance and presence or not of parentheses) subjective based on the privacy/usability report in order to help them choose between the different options mentioned. A second prioritization (colors) is based solely on estimated privacy:

🟢green (true respect for privacy)

🔵blue (respect for privacy under conditions or presence of a problematic item)

🔴red (does not guarantee privacy but still being preferable to the GAFAM options)

⚫colorless (lack of elements to form an estimate, or a prioritization is not relevant for entry into question). The presence of an asterisk indicates that the mentioned option is still in development phase.

I hope this document will help you improve the protection of your data personal and those of her close ones. Although being the fruit of several years of searches and experiments, this work obviously remains perfectible.
Any suggestion or comment is then more than welcome to the email: "Privacyfirst@ik.me". Several months after the present version of the document, you must assume that certain information given will be obsolete. The document being
frequently updated, you are invited to get the latest version on the following website: “https://codeberg.org/PrivacyFirst/PrivacyFirst/issues”.

## 2 Golden rules

* Avoid using GAFAM services and programs (Google, Amazon, Facebook, Apple and Microsoft) WHENEVER possible. It is best to remove your eventual accounts.
* Always review all the settings and authorizations of what is used and optimize them to limit the collection of personal data as much as possible.
* Only install the necessary programs/applications as they are potential accesses to your personal data.
* Use free/open source programs (their codes are public and also verifiable) instead of proprietary/closed source whenever possible.
* Favor the popular free options over the unknown ones (they will be more reviewed/reliable).
* If a company offers its services for free, in general, the product it sells is you (your personal data). Due to the model imposed by the surveillance capitalism, pay now or protect them from also being the product.
* Update your programs/operating systems frequently to benefit from the latest fixes for exploitable security flaws and think about replacing the ones that no longer seem to be up to date.
* Don't use third-party antivirus, they are true vacuum cleaners of personal data. Their contribution is negligible as long as good numerical habits are maintained.
Prudence and a good configuration are the best antivirus.
* Privilege Web Apps or shortcuts from the browser to access services instead of applications to install to limit access and the possibilities of collecting
personal information.
* Use temporary emails to create accounts for unimportant sites/services.
* Always disable Wi-Fi, Bluetooth, and geolocation on your smartphone when not in use and don't connect to public Wi-Fi without using a VPN.
* Do not use connected objects (their purpose is to collect as much personal data as possible) or not connect them to the internet when they are essential.

## 3 Computer

### 3-1 Operating Systems

Windows is currently the worst operating system in terms of privacy and security. The only OS that is easy to use and truly protecting data are the free (therefore free) Linux distributions. There is a multitude of them whose characteristics vary considerably. Here is a small selection of those offering the best user experience (always respecting privacy) or guaranteeing the best data protection. It should be remembered that each of them proposes one or more interfaces (desktop) different in terms of experience, resource consumption and appearance. There is abundant documentation online to choose which one layout and desktop environment will best suit the capabilities of your computer and your preferences as well as how to easily install it on his computer.

**Desktop :**

🟢<img src="./icons/linuxmint.png" width="30">[Linux Mint](https://linuxmint.com) : great for beginners

🟢<img src="./icons/mxlinux.png" width="30">[MX Linux](https://mxlinux.org) : suits beginners

🟢<img src="./icons/parrotos.png" width="30">[Parrot Home OS](https://www.parrotsec.org) : improved security and privacy (confirmed users)

🟢<img src="./icons/zorinos.png" width="30">[Zorin OS](https://zorin.com/os) : great for beginners coming from Windows or macOS (commercial support)

🟢<img src="./icons/qubeos.png" width="30">[Qubes OS](https://www.qubes-os.org) : extreme security (advanced users)

🟢<img src="./icons/whonix.png" width="30">[Whonix](https://www.whonix.org) : anonymity by Tor and extreme security (advanced users)

**USB live (RAM) :**

🟢<img src="./icons/mxlinux.png" width="30">[MX Linux](https://mxlinux.org) : suits beginners

🟢<img src="./icons/tails.png" width="30">[Tails](https://tails.boum.org) : anonymity by Tor (confirmed users)

🟢<img src="./icons/parrotos.png" width="30">[Parrot Home OS](https://www.parrotsec.org) : improved security and privacy (confirmed users)

**Raspberry Pi :**

🟢<img src="./icons/libreelec.png" width="30">[LibreELEC](https://libreelec.tv) : multimedia center for TV

🟢<img src="./icons/batocera.png" width="30">[Batocera](https://batocera.org) : console emulator, retrogaming

🟢<img src="./icons/raspberrypios.png" width="30">[Raspberry Pi OS](https://www.raspberrypi.org/software) : classic operating system

🟢<img src="./icons/plasmabigscreen.png" width="30">[Plasma BigScreen*](https://plasma-bigscreen.org) : multimedia center for TV (voice command with Mycroft AI)

🟢<img src="./icons/nymphcast.png" width="30">[Nymphcast](http://nyanko.ws/product_nymphcast.php) : free and environmentally friendly alternative to Chromecast

**Hardware :**

The following brands sell computers with Linux preinstalled :

TUXEDO Computers

Slimbook

Librem

System76

Linux Mint

PINE64

ThinkPenguin

Dell (few models)

There are also other lesser-known vendors of computers with Linux preinstalled. Regarding Windows computer vendors
Pre-installed, Dell, Asus, and HP models are reputed to have good Linux compatibility. It is advisable to avoid buying computers that come with an Nvidia graphics card as they are known to suffer from compatibility issues.

### 3-2 Services and programs

Browser :

🔵<img src="./icons/firefox.png" width="30">[Firefox](https://www.mozilla.org)

🟢<img src="./icons/torbrowser.png" width="30">[Tor Browser](https://www.torproject.org/download)

🟢<img src="./icons/librewolf.png" width="30">[LibreWolf*](https://librewolf-community.gitlab.io)

🔴<img src="./icons/brave.png" width="30">[Brave](https://brave.com)

🔵<img src="./icons/ungoogledchromium.png" width="30">[Ungoogled Chromium*](https://ungoogled-software.github.io/ungoogled-chromium-binaries/)

🔵<img src="./icons/iridiumbrowser.png" width="30">[Iridium Browser](https://iridiumbrowser.de)

Search engine :

🔵<img src="./icons/duckduckgo.png" width="30">[DuckDuckGo](https://duckduckgo.com)

🔵<img src="./icons/searxme.png" width="30">[searx.me](https://searx.me)

🔵<img src="./icons/qwant.png" width="30">[Qwant](https://www.qwant.com)

🔵<img src="./icons/swisscows.png" width="30">[Swisscows](https://swisscows.com)

🔴<img src="./icons/startpage.png" width="30">[Startpage](https://www.startpage.com) (proxy Google)

⚫<img src="./icons/brave.png" width="30">[Brave Search](https://search.brave.com/)

Office automation :

🟢<img src="./icons/libreoffice.png" width="30">[LibreOffice](https://www.libreoffice.org)

🟢<img src="./icons/onlyoffice.png" width="30">[Onlyoffice](https://www.onlyoffice.com)

🟢<img src="./icons/collaboraoffice.png" width="30">[Collabora Office - LibreOffice prof.](https://www.collaboraoffice.com)

🟢<img src="./icons/calligra.png" width="30">[Calligra](https://calligra.org)

🟢<img src="./icons/cryptpad.png" width="30">[CryptPad](https://cryptpad.fr)

Mail :

<img src="./icons/tutanota.png" width="30">[Tutanota](https://tutanota.com) 🔵free 🔴paid

<img src="./icons/protonmail.png" width="30">[ProtonMail](https://protonmail.com) 🔵free 🔵paid

<img src="./icons/disroot.png" width="30">[Disroot](https://disroot.org/en/services/email) 🔵free

<img src="./icons/posteo.png" width="30">[Posteo](https://posteo.de) 🔵paid

Video platform :

🔵<img src="./icons/lbry.png" width="30">[LBRY - desktop](https://lbry.com)

🔴<img src="./icons/odysee.png" width="30">[Odysee - LBRY web](https://odysee.com)

🟢<img src="./icons/peertube.png" width="30">[PeerTube](https://joinpeertube.org)

Youtube Proxy :

🔵<img src="./icons/invidious.png" width="30">[Invidious](https://invidio.us)

🔵<img src="./icons/cloudtube.png" width="30">[CloudTube](https://cadence.moe/cloudtube/subscriptions)

🔵<img src="./icons/freetube.png" width="30">[FreeTube](https://freetubeapp.io) (Youtube client)

Instant messaging :

🟢<img src="./icons/threema.png" width="30">[Threema](https://threema.ch/en)

🔵<img src="./icons/signal.png" width="30">[Signal](https://signal.org)

🟢<img src="./icons/session.png" width="30">[Session*](https://getsession.org)

🔴<img src="./icons/telegram.png" width="30">[Telegram](https://telegram.org)

🔵<img src="./icons/element.png" width="30">[Element](https://app.element.io)

🔵<img src="./icons/jami.png" width="30">[Jami](https://jami.net)

🔵<img src="./icons/gajim.png" width="30">[Gajim](https://gajim.org/)

Video conferencing :

🟢<img src="./icons/jitsimeet.png" width="30">[Jitsi Meet](https://meet.jit.si)

🔵<img src="./icons/signal.png" width="30">[Signal](https://signal.org)

🔵<img src="./icons/bigbluebutton.png" width="30">[BigBlueButton](https://bigbluebutton.org)

🟢<img src="./icons/jami.png" width="30">[Jami](https://jami.net)

🔵<img src="./icons/element.png" width="30">[Element](https://app.element.io)

🔵<img src="./icons/whereby.png" width="30">[Whereby](https://whereby.com)

🔴<img src="./icons/telegram.png" width="30">[Telegram](https://telegram.org)

Respectfull social network :

🔵<img src="./icons/mastodon.png" width="30">[Mastodon](https://mastodon.social)

🔵<img src="./icons/element.png" width="30">[Element](https://app.element.io)

🔴<img src="./icons/telegram.png" width="30">[Telegram*](https://telegram.org)

🔵<img src="./icons/pixelfed.png" width="30">[PixelFed](https://pixelfed.org)

🔵<img src="./icons/lemmy.png" width="30">[Lemmy](https://join.lemmy.ml/)

🔵<img src="./icons/pleroma.png" width="30">[Pleroma](https://pleroma.social/)

🔵<img src="./icons/movim.png" width="30">[movim](https://movim.eu/)

🔵<img src="./icons/friendica.png" width="30">[Friendica](https://friendi.ca)

Abusive social network proxy :

🔵<img src="./icons/nitter.png" width="30">[Nitter](https://nitter.net) (Twitter)

🔵<img src="./icons/libreddit.png" width="30">[Libreddit](https://libredd.it/) (Reddit)

🔵<img src="./icons/bibliogram.png" width="30">[Bibliogram](https://bibliogram.art) (Instagram)

Translator :

🟢<img src="./icons/libretranslate.png" width="30">[LibreTranslate](https://libretranslate.com/)

<img src="./icons/deepl.png" width="30">[DeepL](https://www.deepl.com/translator) 🔴free 🔵paid

🟢<img src="./icons/apertium.png" width="30">[Apertium](https://www.apertium.org)

🔴<img src="./icons/lingva.png" width="30">[Lingva Translate](https://lingva.ml) (Google
Translate proxy)

Ad blocker/trackers and network traffic controller :

⚫<img src="./icons/portmaster.png" width="30">[Portmaster*](https://safing.io/portmaster)

Password manager :

🟢<img src="./icons/keepassxc.png" width="30">[KeePassXC](https://keepassxc.org)

🔵<img src="./icons/bitwarden.png" width="30">[Bitwarden](https://bitwarden.com)

Maps :

🟢<img src="./icons/openstreetmap.png" width="30">[OpenStreetMap](https://www.openstreetmap.org)

🔵<img src="./icons/qwant.png" width="30">[Qwant Maps*](https://www.qwant.com/map)

🔵<img src="./icons/duckduckgo.png" width="30">[DuckDuckGo](https://duckduckgo.com)

🔴<img src="./icons/mapsme.png" width="30">[Maps.me](https://maps.me)

VPN :

🟢<img src="./icons/protonvpn.png" width="30">[ProtonVPN](https://protonvpn.com)

🟢<img src="./icons/ivpn.svg" width="30">[IVPN](https://www.ivpn.net)

🔵<img src="./icons/mullvad.png" width="30">[Mullvad](https://mullvad.net)

🔵<img src="./icons/windscribe.png" width="30">[Windscribe](https://windscribe.com/)

Movies and series online :

🔵<img src="./icons/stremio.png" width="30">[Swiss Transfer](https://www.stremio.com) 🔵without account 🔴with account

🟢<img src="./icons/kodi.png" width="30">[IVPN](https://kodi.tv)

File sharing :

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

<img src="./icons/icedrive.png" width="30">[Kdrive](https://icedrive.net) 🔴free 🔵paid

🔴<img src="./icons/disroot.png" width="30">[Disroot](https://cloud.disroot.org)

Peer-to-peer synchronization tool :

🟢<img src="./icons/syncthing.png" width="30">[Syncthing](https://syncthing.net)

Schedule :

🟢<img src="./icons/tutanota.png" width="30">[Tutanota](https://f-droid.org/es/packages/de.tutao.tutanota)

🟢<img src="./icons/protonmail.png" width="30">[ProtonCalendar*](https://protonmail.com)

Temporary mail:

⚫<img src="./icons/tempmail.png" width="30">[Temp Mail](https://temp-mail.org)

⚫<img src="./icons/guerrillamail.png" width="30">[Guerrillamail](https://guerrillamail.com)

⚫<img src="./icons/emailondeck.png" width="30">[EmailOnDeck](https://www.emailondeck.com)

Alias manager for mail :

🟢<img src="./icons/forwardemail.png" width="30">[forwardemail](https://forwardemail.net)

Collaboration and organization:

🟢<img src="./icons/cryptpad.png" width="30">[CryptPad](https://cryptpad.fr)

🟢<img src="./icons/mobilizon.png" width="30">[Mobilizon](https://mobilizon.org/en/)

Wikipedia :

🟢<img src="./icons/wikiless.png" width="30">[Elisa](https://wikiless.org) (proxy Wikipedia)

Audio player :

🟢<img src="./icons/elisa.png" width="30">[Elisa](https://elisa.kde.org)

🟢<img src="./icons/audacious.png" width="30">[Audacious](https://audacious-media-player.org)

🟢<img src="./icons/strawberry.png" width="30">[Strawberry Music Player](https://www.strawberrymusicplayer.org)

Media player :

🟢<img src="./icons/mpv.png" width="30">[mpv](https://mpv.io)

🟢<img src="./icons/vlc.png" width="30">[VLC](https://www.videolan.org)

Notes :

🟢<img src="./icons/standardnotes.png" width="30">[Standard Notes](https://standardnotes.org)

🟢<img src="./icons/joplin.png" width="30">[Joplin](https://joplinapp.org)

🟢<img src="./icons/knotes.png" width="30">[Knotes](http://knotesapp.com)

🟢<img src="./icons/gnome.png" width="30">[Gnote](https://wiki.gnome.org/Apps/Gnote)

Antivirus (ClamAV) :

🟢ClamTK (Linux)

🟢ClamWin (Windows)

System cleaning and optimization :

🟢<img src="./icons/stacer.png" width="30">[Stacer](https://oguzhaninan.github.io/Stacer-Web)

🟢<img src="./icons/ubunsys.png" width="30">[ubunsys](https://github.com/adgellida/ubunsys)

🟢<img src="./icons/bleachbit.png" width="30">[BleachBit](https://www.bleachbit.org)

Encryption tool :

🟢<img src="./icons/veracrypt.png" width="30">[VeraCrypt](https://www.veracrypt.fr)

🟢<img src="./icons/cryptomator.png" width="30">[Cryptomator](https://cryptomator.org)

Metadata suppression :

🟢<img src="./icons/exifcleaner.png" width="30">[ExifCleaner](https://exifcleaner.com)

Image editing and drawing :

🟢<img src="./icons/gimp.png" width="30">[Gimp](http://www.gimp.org)

🟢<img src="./icons/krita.png" width="30">[Krita](https://krita.org)

🟢<img src="./icons/drawing.png" width="30">[Drawing](https://maoschanz.github.io/drawing)

Photo processing :

🟢<img src="./icons/darktable.png" width="30">[Darktable](https://www.darktable.org)

🟢<img src="./icons/rawtherapee.png" width="30">[RawTherapee](https://rawtherapee.com)

Vector graphics editing :

🟢<img src="./icons/inkscape.png" width="30">[Inkscape](https://inkscape.org)

Page layout :

🟢<img src="./icons/scribus.png" width="30">[Scribus](https://www.scribus.net)

Audio editing :

🟢<img src="./icons/lmms.png" width="30">[LMMS](https://www.lmms.io)

🟢<img src="./icons/ardour.png" width="30">[Ardour](https://www.ardour.org)

🔵<img src="./icons/audacity.png" width="30">[Audacity](https://www.audacityteam.org)

Video editing :

🟢<img src="./icons/openshot.png" width="30">[OpenShot](https://www.openshot.org)

🟢<img src="./icons/kdenlive.png" width="30">[Kdenlive](https://kdenlive.org)

🟢<img src="./icons/avidemux.png" width="30">[Avidemux](https://www.avidemux.org)

🟢<img src="./icons/pitivi.png" width="30">[Pitivi](http://www.pitivi.org)

🟢<img src="./icons/cinelerra.png" width="30">[Cinelerra](http://cinelerra.org)

CD/DVD burning :

🟢<img src="./icons/k3b.png" width="30">[k3b](https://apps.kde.org/k3b)

🟢<img src="./icons/brasero.png" width="30">[Brasero](https://wiki.gnome.org/Apps/Brasero)

Transcoding :

🟢<img src="./icons/handbrake.png" width="30">[Handbrake](https://handbrake.fr)

🟢<img src="./icons/mkv.png" width="30">[MKV](https://www.matroska.org/index.html)

Connection interface between computer and cell phone :

🟢KDE Connect

🟢Zorin Connect

Windows programs/games under Linux :

⚫<img src="./icons/playonlinux.png" width="30">[PlayOnLinux](https://www.playonlinux.com)

⚫<img src="./icons/wine.png" width="30">[Wine](https://www.winehq.org)

⚫<img src="./icons/winapps.svg" width="30">[WinApps*](https://github.com/Fmstrat/winapps)

Network traffic analysis:

🟢<img src="./icons/wireshark.png" width="30">[Wireshark](https://www.wireshark.org)

All-in-one ecosystem :

🔵Infomaniak

🔵Proton*

🔵Cozy Cloud

## 4 Smartphone

### 4-1 Operating Systems

Android, in its default configuration, is currently the worst operating system in terms of privacy. Its purpose is to continuously send personal data to Google's servers to exploit and sell them. The most recommended solution today is to use a modified version of Android (custom ROM) to respect privacy.

If you do not want to install or buy a smartphone with a respectful operating system (serious error) and you still want to use Android from origin, follow the advice detailed in point 8.1 of this document in order to limit the collection of personal information.

Apple's operating system (iOS), despite its marketing based on respect for privacy, also collects and exploits the personal data of its users in addition to considerably limiting their freedom.

Linux-based options are privacy-friendly and promising in terms of independence, but they don't offer the same security guarantees as Android. Furthermore, in their current state of development, they are not recommended for average users (except for Sailfish OS).

**Android modified for privacy :**

🟢<img src="./icons/calyxos.png" width="30">[CalyxOS](https://calyxos.org) : Android degooglized and secure with microG for better compatibility

🟢<img src="./icons/grapheneos.png" width="30">[GrapheneOS](https://grapheneos.org) : the most private and secure degooglized Android available

🔵<img src="./icons/e.png" width="30">[/e/ OS](https://e.foundation) : Degooglized LineageOS but with microG and integrated services (/e/ account)

🔵<img src="./icons/divestos.png" width="30">[DivestOS](https://divestos.org/) : LineageOS partially enhanced for security and privacy

🔵<img src="./icons/lineageosmicrog.png" width="30">[LineageOS for microG](https://lineage.microg.org) : LineageOS with microG for better compatibility

🔵<img src="./icons/vollaos.png" width="30">[Volla OS](https://volla.online): Safe Android, without Google apps but not totally degooglized

🔵<img src="./icons/lineageos.png" width="30">[LineageOS](https://lineageos.org) : Android without Google apps but not totally degooglized

**Linux :**

🔵<img src="./icons/sailfishos.png" width="30">[Sailfish OS](https://sailfishos.org) (partially proprietary)

🔵<img src="./icons/ubuntutouch.png" width="30">[Ubuntu Touch*](https://ubuntu-touch.io)

🔵<img src="./icons/postmarketos.png" width="30">[PostmarketOS*](https://postmarketos.org)

🔵<img src="./icons/mobian.png" width="30">[Mobian*](https://mobian-project.org)

🔵<img src="./icons/pureos.png" width="30">[PureOS*](https://pureos.net)

🔵<img src="./icons/manjaro.png" width="30">[Manjaro*](https://manjaro.org)

**Preinstalled hardware :**

[Fairphone 3 y 3+](https://www.fairphone.com) : /e/ OS (version only available on project site /e/)

[Gigaset GS290](https://e.foundation/es/e-announces-the-e-gs290-as-the-latest-device-available-with-privacy-friendly-e-os-pre-installed/) : /e/ OS (version only available on project site /e/)

[Volla Phone](https://volla.online) : Volla OS, Ubuntu Touch and others

[Pinephone](https://www.pine64.org/pinephone) : Manjaro and others Linux O.S. compatibles)

Other models with /e/ OS pre-installed are available at the /e/ project site:

https://esolutions.shop/

### 4-2 Applications

The applications proposed for Android and derivatives must be searched first in the free F-Droid application store (guarantee that they do not have third-party trackers) and only if they are not, in Aurora Store, a Google Play proxy allowing access to their free applications anonymously (never connect with a personal Google account, always anonymously).

These stores must be downloaded directly from their official web pages. Remember then to withdraw the authorization to install unknown applications to your browser, for security reasons (settings> applications> browser used).

**Android and derivatives :**

App store :

🟢<img src="./icons/f-droid.png" width="30">[F-Droid](https://f-droid.org)

🔵<img src="./icons/aurorastore.png" width="30">[Aurora Store](https://auroraoss.com) (proxy Play Store)

🔵<img src="./icons/apkmirror.png" width="30">[APKMirror](https://www.apkmirror.com)

Browser :

🟢<img src="./icons/bromite.png" width="30">[Bromite](https://www.bromite.org/fdroid)

🟢<img src="./icons/torbrowser.png" width="30">[Tor Browser](https://www.torproject.org/es/download/#android)

🔵<img src="./icons/mull.png" width="30">[mull](https://github.com/Divested-Mobile/mull)

🔵<img src="./icons/privacybrowser.png" width="30">[Privacy Browser](https://f-droid.org/es/packages/com.stoutner.privacybrowser.standard)

🔵<img src="./icons/fossbrowser.png" width="30">[FOSS Browser](https://f-droid.org/es/packages/de.baumann.browser)

🔵<img src="./icons/ungoogledchromium.png" width="30">[Ungoogled Chromium](https://uc.droidware.info/fdroid.html)

Instant messaging :

🟢<img src="./icons/threema.png" width="30">[Threema](https://threema.ch/en)

🔵<img src="./icons/signal.png" width="30">[Signal](https://signal.org)

🟢<img src="./icons/session.png" width="30">[Session*](https://getsession.org)

🔴<img src="./icons/telegram.png" width="30">[Telegram FOSS](https://f-droid.org/packages/org.telegram.messenger/)

🔵<img src="./icons/element.png" width="30">[Element](https://app.element.io)

🔵<img src="./icons/jami.png" width="30">[Jami](https://jami.net)

🟢<img src="./icons/briar.png" width="30">[Briar](https://briarproject.org)

🔵<img src="./icons/conversations.png" width="30">[Conversations](https://conversations.im)

Video conferencing :

🟢<img src="./icons/jitsimeet.png" width="30">[Jitsi Meet](https://meet.jit.si)

🔵<img src="./icons/signal.png" width="30">[Signal](https://signal.org)

🟢<img src="./icons/jami.png" width="30">[Jami](https://jami.net)

🔵<img src="./icons/element.png" width="30">[Element](https://app.element.io)

🔵<img src="./icons/whereby.png" width="30">[Whereby](https://whereby.com)

🔴<img src="./icons/telegram.png" width="30">[Telegram FOSS](https://f-droid.org/packages/org.telegram.messenger)

Video platform :

🔴<img src="./icons/lbry.png" width="30">[LBRY](https://lbry.com)

🔴<img src="./icons/newpipe.png" width="30">[Newpipe](https://newpipe.schabi.org) (Youtube client)

🟢<img src="./icons/tubelab.png" width="30">[Tubelab](https://f-droid.org/en/packages/app.fedilab.tubelab/) (Peertube client)

Ad/Tracker Blocker:

🟢<img src="./icons/rethinkdns.png" width="30">[RethinkDNS*](https://play.google.com/store/apps/details?id=com.celzero.bravedns&hl=es&gl=US)

🟢<img src="./icons/blokada.png" width="30">[Blokada](https://f-droid.org/es/packages/org.blokada.alarm)

🟢<img src="./icons/nebulo.png" width="30">[Nebulo](https://play.google.com/store/apps/details?id=com.frostnerd.smokescreen&hl=es&gl=US)

🟢TrackerControl

Maps/GPS navigation:

🔵<img src="./icons/magicearth.png" width="30">[Magic Earth](https://www.magicearth.com)

🟢<img src="./icons/osmand.png" width="30">[OsmAnd+](https://f-droid.org/es/packages/net.osmand.plus/)

🟢Organic Maps

Mail client :

🔵<img src="./icons/tutanota.png" width="30">[Tutanota](https://f-droid.org/es/packages/de.tutao.tutanota)

🔵<img src="./icons/protonmail.png" width="30">[ProtonMail](https://protonmail.com)

⚫FairEmail

⚫<img src="./icons/k-9mail.png" width="30">[K-9 Mail](https://f-droid.org/es/packages/com.fsck.k9)

Alias manager for mail :

🟢<img src="./icons/simplelogin.png" width="30">[Simple Login](https://simplelogin.io)

🟢<img src="./icons/anonaddy.png" width="30">[AnonAddy](https://anonaddy.com/)

Password manager client :

🟢<img src="./icons/keepassdx.png" width="30">[KeePassDX](https://f-droid.org/es/packages/com.kunzisoft.keepass.libre)

🔵<img src="./icons/bitwarden.png" width="30">[Bitwarden](https://bitwarden.com)

🟢AuthPass

Two-factor authentication :

🟢<img src="./icons/aegis.png" width="30">[Aegis](https://f-droid.org/es/packages/com.beemdevelopment.aegis)

🟢<img src="./icons/andotp.png" width="30">[andOTP](https://f-droid.org/en/packages/org.shadowice.flocke.andotp)

VPN :

🟢<img src="./icons/protonvpn.png" width="30">[ProtonVPN](https://protonvpn.com)

🟢<img src="./icons/ivpn.svg" width="30">[IVPN](https://www.ivpn.net)

🔵<img src="./icons/mullvad.png" width="30">[Mullvad](https://mullvad.net)

🔵<img src="./icons/riseupvpn.svg" width="30">[Riseup VPN](https://riseup.net/es/vpn)

🔵<img src="./icons/calyxos.png" width="30">[Calyx VPN](https://calyx.net/)

Sync tool :

🟢<img src="./icons/syncthing.png" width="30">[Syncthing](https://f-droid.org/en/packages/com.nutomic.syncthingandroid)

⚫DAVx5

Cloud :

🔵<img src="./icons/kdrive.png" width="30">[Kdrive](https://www.infomaniak.com/es/kdrive)

🔴<img src="./icons/mega.png" width="30">[Kdrive](https://www.https://mega.nz)

🟢<img src="./icons/nextcloud.png" width="30">[Nextcloud](https://nextcloud.com)

🔴<img src="./icons/cozycloud.png" width="30">[Cozy Drive](https://cozy.io)

🔴<img src="./icons/icedrive.png" width="30">[Kdrive](https://icedrive.net)

Encryption tool for cloud :

🟢<img src="./icons/cryptomator.png" width="30">[Cryptomator](https://cryptomator.org)

Connection interface between computer and cell phone :

🟢KDE Connect

🟢Zorin Connect

Respectful social network :

🔵<img src="./icons/tusky.png" width="30">[Tusky](https://f-droid.org/en/packages/com.keylesspalace.tusky) (Mastodon)

🔵<img src="./icons/element.png" width="30">[Element](https://f-droid.org/es/packages/im.vector.app) (Matrix)

🔴<img src="./icons/telegram.png" width="30">[Telegram FOSS](https://f-droid.org/packages/org.telegram.messenger)

🔵<img src="./icons/fedilab.png" width="30">[Fedilab](https://f-droid.org/en/packages/fr.gouv.etalab.mastodon) Mastodon, Pleroma...),

🔵PixelDroid (PixelFed)

🔵<img src="./icons/lemmy.png" width="30">[Lemmur (Lemmy)](https://lemmy.ml)

Respectful client Facebook :

🔴<img src="./icons/frost.png" width="30">[Frost for Facebook](https://f-droid.org/es/packages/com.pitchedapps.frost)

🔴<img src="./icons/webapps.png" width="30">WebApps

Respectful client Instagram :

🔴<img src="./icons/webapps.png" width="30">WebApps

🔴Barinsta

Respectful client Twitter :

🔴Fritter

🔴<img src="./icons/twidere.png" width="30">[Twidere](https://f-droid.org/es/packages/org.mariotaku.twidere)

🔴<img src="./icons/webapps.png" width="30">WebApps

WebApps creator:

🟢<img src="./icons/webapps.png" width="30">WebApps

Metadata suppression :

🟢<img src="./icons/scrambledexif.png" width="30">[Scrambled Exif](https://f-droid.org/es/packages/com.jarsilio.android.scrambledeggsif)

🟢<img src="./icons/imagepipe.png" width="30">[ImagePipe](https://f-droid.org/es/packages/de.kaffeemitkoffein.imagepipe)

Office :

🟢<img src="./icons/collaboraoffice.png" width="30">[Collabora Office - LibreOffice prof.](https://www.collaboraoffice.com)

🟢LibreOffice

E-book reader :

🟢Librera Reader

🟢KOReader

Finance :

🟢MoneyWallet

🟢Unstoppable Wallet

🟢MoneyBuster

🟢WeeklyBudget

Physical exercise :

🟢Feeel – home workouts

🟢FitoTracker

🟢Workout Time!

Internet radio :

🟢<img src="./icons/radiodroid.png" width="30">[RadioDroid](https://f-droid.org/es/packages/net.programmierecke.radiodroid2)

🟢Transistor – Simple Radio App

Redirector of content YouTube, Twitter, Instagram and Google Map :

🟢<img src="./icons/untrackme.png" width="30">[UntrackMe](https://f-droid.org/en/packages/app.fedilab.nitterizeme)

QR code scanner :

⚫QR & Barcode Scanner

RSS Reader:

🟢Feeder

🟢Flym

🟢Handy News Reader

Replacement application system for Android of origin :

Keyboard :

🟢<img src="./icons/anysoftkeyboard.png" width="30">[AnySoftKeyboard](https://anysoftkeyboard.github.io)

🟢<img src="./icons/openboard.png" width="30">[OpenBoard](https://f-droid.org/es/packages/org.dslul.openboard.inputmethod.latin)

🟢<img src="./icons/florisboard.png" width="30">[FlorisBoard*](https://github.com/florisboard/florisboard)

Schedule :

🟢<img src="./icons/simplecalendar.png" width="30">[Simple Calendar](https://f-droid.org/es/packages/com.simplemobiletools.calendar.pro)

🟢<img src="./icons/tutanota.png" width="30">[Tutanota](https://f-droid.org/es/packages/de.tutao.tutanota)

🟢Proton Calendar*

🟢<img src="./icons/etar.png" width="30">[Etar](https://f-droid.org/es/packages/ws.xsoh.etar)

Notes :

🟢<img src="./icons/standardnotes.png" width="30">[Standard Notes](https://play.google.com/store/apps/details?id=com.standardnotes)

🟢Quillnote

🟢<img src="./icons/joplin.png" width="30">[Joplin](https://play.google.com/store/apps/details?id=net.cozic.joplin&utm_source=GitHub&utm_campaign=README&pcampaignid=MKT-Other-global-all-co-prtnr-py-PartBadge-Mar2515-1)

🟢<img src="./icons/nextcloudnotes.png" width="30">[Nextcloud Notes](https://f-droid.org/es/packages/it.niedermann.owncloud.notes)

Meteorology :

🟢Geometric Weather

🟢Weather

SMS :

🔴<img src="./icons/signal.png" width="30">[Signal](https://signal.org)

🔴<img src="./icons/simplesmsmessenger.png" width="30">[Simple SMS Messenger](https://f-droid.org/en/packages/com.simplemobiletools.smsmessenger/)

🔴<img src="./icons/qksms.png" width="30">[QKSMS](https://f-droid.org/en/packages/com.moez.QKSMS/)

File manager :

🟢<img src="./icons/simplefilemanager.png" width="30">[Simple File Manager](https://f-droid.org/es/packages/com.simplemobiletools.filemanager.pro)

🟢Ghost Commander

🟢Material Files

Gallery :

🟢<img src="./icons/simplegallery.png" width="30">[Simple Gallery](https://f-droid.org/es/packages/com.simplemobiletools.gallery.pro)

Audioplayer :

🟢<img src="./icons/vinylmusicplayer.png" width="30">[Vinyl Music Player](https://f-droid.org/es/packages/com.poupa.vinylmusicplayer)

🟢<img src="./icons/vanillamusic.png" width="30">[Vanilla Music](https://f-droid.org/en/packages/ch.blinkenlights.android.vanilla)

🟢<img src="./icons/musicplayergo.png" width="30">[Music Player GO](https://f-droid.org/es/packages/com.iven.musicplayergo)

PDF :

🟢<img src="./icons/pdfviewerplus.png" width="30">[PDF Viewer Plus](https://f-droid.org/es/packages/com.gsnathan.pdfviewer)

🟢Librera Reader

🟢KOReader

🟢<img src="./icons/mupdfviewer.png" width="30">[MuPDF Viewer](https://f-droid.org/es/packages/com.artifex.mupdf.viewer.app)

Contacts :

🟢<img src="./icons/opencontacts.png" width="30">[Open Contacts](https://f-droid.org/es/packages/opencontacts.open.com.opencontacts)

🟢<img src="./icons/simplecontacts.png" width="30">[Simple Contacts](https://f-droid.org/es/packages/com.simplemobiletools.contacts.pro)

Camera :

🟢<img src="./icons/opencamera.png" width="30">[Open Camera](https://f-droid.org/es/packages/net.sourceforge.opencamera)

🟢<img src="./icons/simplecamera.png" width="30">[Simple Camera](https://f-droid.org/es/packages/com.simplemobiletools.camera)

Voice recorder :

🟢<img src="./icons/audiorecorder.png" width="30">[Audio Recorder](https://f-droid.org/es/packages/com.github.axet.audiorecorder)

🟢<img src="./icons/simplevoicerecorder.png" width="30">[Simple Voice Recorder](https://f-droid.org/es/packages/com.simplemobiletools.voicerecorder)

Call manager : 

🔴<img src="./icons/simpledialer.png" width="30">[Simple Dialer](https://f-droid.org/es/packages/com.simplemobiletools.dialer)

🔴Emerald Dialer

Calculator :

🟢<img src="./icons/simplecalculator.png" width="30">[Simple Calculator](https://f-droid.org/en/packages/com.simplemobiletools.calculator)

Clock :

🟢<img src="./icons/simpleclock.png" width="30">[Simple Clock](https://f-droid.org/en/packages/com.simplemobiletools.clock)

Media Player:

🟢<img src="./icons/vlc.png" width="30">[VLC](https://f-droid.org/es/packages/org.videolan.vlc/)

To go further :

Network traffic controller (firewall) :

🟢<img src="./icons/rethinkdns.png" width="30">[RethinkDNS*](https://play.google.com/store/apps/details?id=com.celzero.bravedns&hl=es&gl=US)

🟢<img src="./icons/inviziblepro.png" width="30">[InviZible Pro](https://f-droid.org/en/packages/pan.alexander.tordnscrypt.stable)

🟢<img src="./icons/netguard.png" width="30">[NetGuard](https://f-droid.org/es/packages/eu.faircode.netguard)

Third Party Tracker Developer :

🟢<img src="./icons/classyshark3xodus.png" width="30">[ClassyShark3xodus](https://f-droid.org/es/packages/com.oF2pks.classyshark3xodus)

🟢<img src="./icons/exodus.png" width="30">[Exodus](https://f-droid.org/en/packages/org.eu.exodus_privacy.exodusprivacy)

Privacy manager for applications :

🟢<img src="./icons/appmanager.png" width="30">[App Manager](https://f-droid.org/es/packages/io.github.muntashirakon.AppManager)

🟢<img src="./icons/appwarden.png" width="30">[App Warden](https://forum.xda-developers.com/t/app-5-0-warden-app-manager.4122227) (root)

Application stop (background):

🟢<img src="./icons/rethinkdns.png" width="30">[RethinkDNS*](https://play.google.com/store/apps/details?id=com.celzero.bravedns&hl=es&gl=US)

🟢<img src="./icons/superfreezz.png" width="30">[SuperFreezZ](https://f-droid.org/es/packages/superfreeze.tool.android)

Network anonymization by Tor :

🟢<img src="./icons/orbotproxy.png" width="30">[Orbot Proxy](https://play.google.com/store/apps/details?id=org.torproject.android&hl=es&gl=US)

🟢<img src="./icons/inviziblepro.png" width="30">[InviZible Pro](https://f-droid.org/en/packages/pan.alexander.tordnscrypt.stable)

Applications Isolator :

🟢<img src="./icons/shelter.png" width="30">[Shelter](https://f-droid.org/en/packages/net.typeblog.shelter)

🟢<img src="./icons/insular.png" width="30">[Insular](https://f-droid.org/en/packages/com.oasisfeng.island.fdroid)

Malware detector:

🟢Hypatia (ClamAV)

Alternative to Chromecast for Raspberry Pi :

🟢Raspicast

Fake Localization :

🟢<img src="./icons/faketraveler.png" width="30">[Fake Traveler](https://f-droid.org/en/packages/cl.coders.faketraveler)

Replacement of Google Services:

🔵<img src="./icons/microg.png" width="30">[MicroG GmsCore](https://microg.org)

Microphone usage blocker :

🟢<img src="./icons/pilfershushjammer.png" width="30">[PilferShush Jammer](https://f-droid.org/en/packages/cityfreqs.com.pilfershushjammer)

### IOS :

Browser :

🔵<img src="./icons/firefox.png" width="30">[Firefox](https://apps.apple.com/us/app/navegador-firefox/id989804926)

🔵<img src="./icons/onionbrowser.png" width="30">[Onion Browser](https://apps.apple.com/us/app/onion-browser/id519296448)

🔵<img src="./icons/duckduckgobrowser.png" width="30">[DuckDuckGo Browser](https://apps.apple.com/us/app/duckduckgo-privacy-browser/id663592361)

🔴<img src="./icons/brave.png" width="30">[Brave](https://apps.apple.com/us/app/brave-private-web-browser-vpn/id1052879175)

Instant messaging :

🟢<img src="./icons/threema.png" width="30">[Threema](https://apps.apple.com/us/app/threema-the-secure-messenger/id578665578)

🔵<img src="./icons/signal.png" width="30">[Signal](https://apps.apple.com/us/app/signal-mensajer%C3%ADa-privada/id874139669)

🟢<img src="./icons/session.png" width="30">[Session*](https://apps.apple.com/us/app/session-private-messenger/id1470168868)

🔴<img src="./icons/telegram.png" width="30">[Telegram](https://apps.apple.com/us/app/telegram-messenger/id686449807)

🔵<img src="./icons/element.png" width="30">[Element](https://app.element.io)

🔵<img src="./icons/jami.png" width="30">[Jami](https://apps.apple.com/us/app/jami/id1306951055)

🔵<img src="./icons/monal.png" width="30">[Monal](https://apps.apple.com/us/app/monal-xmpp-chat/id317711500)

Video conferencing :

🟢<img src="./icons/jitsimeet.png" width="30">[Jitsi Meet](https://apps.apple.com/us/app/jitsi-meet/id1165103905)

🔵<img src="./icons/signal.png" width="30">[Signal](https://apps.apple.com/us/app/signal-mensajer%C3%ADa-privada/id874139669)

🟢<img src="./icons/jami.png" width="30">[Jami](https://apps.apple.com/us/app/jami/id1306951055)

🔵<img src="./icons/element.png" width="30">[Element](https://app.element.io)

🔵<img src="./icons/whereby.png" width="30">[Whereby](https://apps.apple.com/us/app/whereby-video-meetings/id878583078)

🔴<img src="./icons/telegram.png" width="30">[Telegram](https://apps.apple.com/us/app/telegram-messenger/id686449807)

Video platform :

🔴<img src="./icons/odysee.png" width="30">[Odysee - LBRY web](https://odysee.com)

Ad/Tracker Blocker :

🟢<img src="./icons/blokada.png" width="30">[Blokada](https://apps.apple.com/us/app/blokada/id1508341781)

🟢<img src="./icons/dnscloak.png" width="30">[DNSCloak](https://apps.apple.com/us/app/dnscloak-secure-dns-client/id1452162351)

🟢<img src="./icons/lockdown.png" width="30">[Lockdown](https://apps.apple.com/us/app/lockdown-apps/id1469783711)

Maps / GPS navigation :

🔵Magic Earth

🟢Organic Maps

🔵OsmAnd

Mail client : 

🔵<img src="./icons/tutanota.png" width="30">[Tutanota](https://apps.apple.com/us/app/tutanota/id922429609)

🔵<img src="./icons/protonmail.png" width="30">[ProtonMail](https://apps.apple.com/us/app/protonmail-correo-cifrado/id979659905)

Alias manager for mail :

🟢<img src="./icons/simplelogin.png" width="30">[Simple Login](https://apps.apple.com/us/app/simplelogin-anti-spam/id1494359858)

Password manager client :

🟢<img src="./icons/strongbox.png" width="30">[Strongbox](https://apps.apple.com/es/app/strongbox-keepass-pwsafe/id897283731) - KeePass & PwSafe

🔵<img src="./icons/bitwarden.png" width="30">[Bitwarden](https://apps.apple.com/us/app/bitwarden-gestor-de-contrase/id1137397744)

Two-factor authentication :

🟢<img src="./icons/tofuauthenticator.png" width="30">[Tofu Authenticator](https://apps.apple.com/us/app/tofu-authenticator/id1082229305)

🟢Raivo OTP

VPN:

🔵ProtonVPN

🟢IVPN

🔵Mullvad VPN

🔵Windscribe VPN

Cloud :

🔵<img src="./icons/kdrive.png" width="30">[Kdrive](https://www.infomaniak.com/es/kdrive)

🔴<img src="./icons/mega.png" width="30">[Kdrive](https://apps.apple.com/es/app/mega/id706857885

🟢<img src="./icons/nextcloud.png" width="30">[Nextcloud](https://nextcloud.com)

🔴<img src="./icons/cozycloud.png" width="30">[Cozy Drive](https://cozy.io)

🔴<img src="./icons/icedrive.png" width="30">[Kdrive](https://apps.apple.com/es/app/icedrive-cloud-storage/id1476402680)

Encryption tool for cloud :

🟢<img src="./icons/cryptomator.png" width="30">[Cryptomator](https://apps.apple.com/us/app/cryptomator/id953086535)

Respectful social network :

🔵Mastodon for iPhone

🔴<img src="./icons/telegram.png" width="30">[Telegram](https://apps.apple.com/us/app/telegram-messenger/id686449807)

🔵Element (Matrix)

Office :

🟢Collabora Office

🟢LibreOffice

## 5 Browsers

Compartmentalization (using different browsers with different settings, depending on the tasks) is a recommended method to preserve privacy without sacrificing too much browsing comfort.
For example, it would be to use Firefox with a restrictive configuration for general navigation. Then, use another profile of the same Firefox or Firefox ESR, configured in a less restrictive way for sites that do not load correctly or that require a connection to a personal account, and another browser for the consultation of the most recalcitrant sites to a configuration for the privacy protection (Brave or Ungoogled Chromium without settings are ideal for that task). It is also conceivable to use another browser solely dedicated to e-banking or also Tor Browser for anonymous browsing.

### 5-1 Firefox

For Firefox to protect privacy, it needs to be configured appropriately (settings, extensions and about: config). All necessary settings are developed in point 8.3 of the document. These settings also apply to LibreWolf and, to a certain extent, for the mobile version of Firefox (Fennec).

**Extensions :**

Light list :

<img src="./icons/ublockorigin.png" width="30">uBlock Origin - [Chrome](https://chrome.google.com/webstore/detail/ublock-origin/cjpalhdlnbpafiamejdnhcphjbkeiagm) - [Firefox](https://addons.mozilla.org/es/firefox/addon/ublock-origin)

<img src="./icons/decentraleyes.png" width="30">Decentraleyes - [Chrome](https://chrome.google.com/webstore/detail/decentraleyes/ldpochfccmkkmhdbclfhpagapcfdljkj) - [Firefox](https://addons.mozilla.org/es/firefox/addon/decentraleyes)

<img src="./icons/cookieautodelete.png" width="30">Cookie AutoDelete - [Chrome](https://chrome.google.com/webstore/detail/cookie-autodelete/fhcgjolkccmbidfldomjliifgaodjagh) - [Firefox](https://addons.mozilla.org/en-US/firefox/addon/cookie-autodelete)

<img src="./icons/https-everywhere.png" width="30">HTTPS Everywhere - [Chrome](https://chrome.google.com/webstore/detail/https-everywhere/gcbommkclmclpchllfjekcdonpmejbdp) - [Firefox](https://addons.mozilla.org/es/firefox/addon/https-everywhere)

Footprint randomization (restrictive) :

<img src="./icons/ublockorigin.png" width="30">uBlock Origin - [Chrome](https://chrome.google.com/webstore/detail/ublock-origin/cjpalhdlnbpafiamejdnhcphjbkeiagm) - [Firefox](https://addons.mozilla.org/es/firefox/addon/ublock-origin)

<img src="./icons/decentraleyes.png" width="30">Decentraleyes - [Chrome](https://chrome.google.com/webstore/detail/decentraleyes/ldpochfccmkkmhdbclfhpagapcfdljkj) - [Firefox](https://addons.mozilla.org/es/firefox/addon/decentraleyes) - Finished development? - Alternative?

<img src="./icons/privacyredirect.png" width="30">Privacy Redirect - [Chrome](https://chrome.google.com/webstore/detail/privacy-redirect/pmcmeagblkinmogikoikkdjiligflglb) - [Firefox](https://addons.mozilla.org/en-US/firefox/addon/privacy-redirect)

<img src="./icons/canvasblocker.png" width="30">CanvasBlocker - [Chrome](https://chrome.google.com/webstore/detail/canvas-blocker-fingerprin/nomnklagbgmgghhjidfhnoelnjfndfpd) - [Firefox](https://addons.mozilla.org/es/firefox/addon/canvasblocker)

<img src="./icons/chameleon.png" width="30">[Chameleon](https://github.com/ghostwords/chameleon) Finished development? - Alternative?

### 5-2 Tor Browser

The concept of Tor is to make Internet traffic pass through a network by anonymizing it. In the effort that the fingerprint of your browser (given among others by its configuration) does not betray your identity, Tor browsers are designed to
have the same footprint regardless of users. To avoid making the footprint of your Tor browser unique, no extensions should be installed and no modifications should be made to the "about: config" settings. To preserve the given anonymity, it is also necessary not to connect to accounts that could de facto override it.
The Tor network's anonymization method slows down uploads. Well, it is not recommended to use it for streaming or voluminous downloads.

## 6 Service instances

### 6-1 Searx

Searx is a meta search engine that does not transmit personal data to used search engines. It allows, if one wishes, a very advanced configuration. The different instances (available there: https://searx.space/) do not offer all the same guarantees of privacy protection (IP address log or not, etc.)

🔵https://searx.nobigtech.es : Google results included, IP address, log good UI

🟢https://search.disroot.org : Google results (Startpage), no IP address log, good UI

🟢https://search.disroot.org : Google results included, no IP address log

### 6-2 Invidious

Invidious gives access to YouTube content (proxy) without transmitting the personal data of its users to Google. Unfortunately, its different instances (available there: https://instances.invidio.us/) frequently suffer from problems caused by Google's measures taken to prevent their operation. The Privacy Redirect extension automatically redirects YouTube links to Invidous.
The Invidious instances that currently appear to be the most functional are

⚫https://yewtu.be

### 6-3 Videoconference

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

### 6-4 DNS Servers

If you use a VPN, it is advisable not to change your default DNS server, in order not to stand out from your other users. If not, replace the DNS server provided by your internet provider with a respectful one among the recommendations below. Use an encrypted implementation (DoH, DoT, DoQ, DNSCrypt, etc.) whenever possible.

With filters against ads, trackers and malicious domains :

🟢[BlahDNS](https://blahdns.com) (DoH, DoT, DNSCrypt) (Europe and East Asia)

🟢[NixNet](https://docs.nixnet.services/NixNet_DNS) (DoH, DoT) (Europe and North America)

🔵[Adguard](https://adguard.com/en/adguard-dns/overview.html) (DoH, DoT, DNSCrypt) (Europe, North America and East Asia)

🔵[NextDNS](https://nextdns.io)(DoH, DoT, DNSCrypt) (intercontinental)

🔵[LibreDNS](https://libredns.gr)(DoH, DoT) (Europa)

BlahDNS DoH (Alemania) : https://doh-de.blahdns.com/dns-query

BlahDNS DoH (Singapur) : https://doh-sg.blahdns.com/dns-query

BlahDNS DoQ (Finlandia) : quic://dot-fi.blahdns.com:784

NixNet DoH (intercontinental) : https://adblock.any.dns.nixnet.xyz/dns-query

Filters against malicious domains: :

🟢[Quad9](https://www.quad9.net) (DoH, DoT, DNSCrypt) (only block malicious domains)

DoH : https://dns.quad9.net/dns-query

DoT : tls://dns.quad9.net

IPv4 : 9.9.9.9, 149.112.112.112

IPv6 : 2620:fe::fe, 2620:fe::9

Without filters :

🟢[Snopyta](https://snopyta.org) (DoH, DoT) (Europe)

🟢[Digitale Gesellschaft](https://digitalegesellschaft.de) (DoH, DoT) (Europe)

🔵[UncensoredDNS](https://blog.uncensoreddns.org/dns-servers) (DoH) (Europe and North America)

🔵[DNS.Watch](https://dns.watch) (DoH, DNSCrypt)

Snopyta DoH (Finlandia) : https://fi.doh.dns.snopyta.org/dns-query


## 7 Additional resources (featured sources)

**General**

Excellent resources for understanding surveillance capitalism and its threats :

* https://www.nobigtech.es
* The Social Media Dilemma, Jeff Orlowski (film)
* Nothing to Hide, Marc Meillassoux (documentary film)
* The Age of Surveillance Capitalism, Shoshana Zuboff (book)

Excellent tutorials for privacy and data protection :

basic :

* https://spreadprivacy.com/tag/device-privacy-tips
* https://www.vice.com/en_us/article/d3devm/motherboard-guide-to-notgetting-hacked-online-safety-guide

complete :

* https://dt.gl/privacy-cookbook-the-story-so-far/

Great channels about privacy (with tutorials) :

* The Hated One : https://www.youtube.com/channel/UCjr2bPAyPV7t35MvcgT3W8Q
* Techlore : https://www.youtube.com/channel/UCs6KfncB4OV6Vug4o_bzijg

Associations for the defense of privacy (information) :

* https://ssd.eff.org/
* https://www.laquadrature.net/es/
* https://www.eff.org/deeplinks

Associations proposing excellent services respectful of privacy:

* https://disroot.org/es/
* https://komun.org/
* https://framasoft.org/en/
* https://snopyta.org/
* https://www.drycat.fr/en

Excellent site listing respectful services and programs :

* https://www.privacytools.io/

Recommended operators:

* https://www.eff.org/pages/quien-defiende-tus-datos

**Telegram groups and channels (and Matrix)**

Privacidad, protección de datos y más :

* [t.me/privacidadlibre](t.me/privacidadlibre) and #privacidadlibre:matrix.org
* [t.me/techloregroup](t.me/techloregroup) and #techlore:matrix.org
* [t.me/techloreofficial](t.me/techloreofficial) (watch out, pro Apple bias)

Linux y libre :

* [Proyecto tic tac](t.me/grupo_telegram_proyectotictac)
* [LinuxMintEs](t.me/LinuxMintEs)
* [mxantixes](t.me/mxantixes)

**Operating Systems**

Linux :

* [MX Linux](https://mxlinux.org)
* [Linux Mint](https://linuxmint.com)

Privacy-friendly Android :

* [CalyxOS](https://calyxos.org)
* [GrapheneOS](https://grapheneos.org)
* [/e/ OS](https://e.foundation)

*Application compatibility with and without microG : (https://plexus.techlore.tech)

**Firefox**

* [Firefox configuration](https://www.youtube.com/watch?v=tQhWdsFMc24)
* [Firefox basic configuration](https://12bytes.org/articles/tech/firefox/the-firefox-privacy-guide-for-dummies)
* [Firefox advanced configuration](https://12bytes.org/articles/tech/firefox/firefoxgecko-configuration-guide-for-privacy-and-performance-buffs)

## 8 Configurations

### 8-1 Operating systems

**Android**

The following recommendations are imperfect and do not fully guarantee data protection, as it is recommended to use a version of Android modified for privacy instead of Android of origin. That being said, in an effort not to be fully and continuously outlined with Android of origin, follow the following recommendations :

* Avoid all Chinese or Samsung brands and prefer one brand, such as Nokia, proposing "Android One" (ie without additional manufacturer layer)
* Never connect with a Google account
* Use applications to be able to install applications without Google Play Store
* Install and use an application, such as RethinkDNS or Blokada, that allows you to block trackers as well as advertisements and use an encrypted respectful DNS server
* Replace the default keyboard with a respectful one
* Delete (or when it is not possible to deactivate) all harmful applications (Google, third-party antivirus, etc.) or not used
* Block internet access to all applications that are disabled or do not require internet access to function thanks to a firewall application such as RethinkDNS
* Review all application and system authorizations to remove them if they are harmful to privacy or unnecessary

**GrapheneOS**

Take advantage of the function offered only by GrapheneOS to remove the authorization of the access to the sensors (used insidiously for the collection of information and the tracking) to all the commercial or closed source applications and also those that do not need it, as a precaution:

"Settings"> "Apps and notifications"> choose an app> "Permissions"> "Sensors" > "See all apps that have this permission"

**Windows**

The following recommendations are imperfect and do not guarantee data protection, as it is recommended to use a Linux distribution instead of
Windows. That being said, in an effort not to be fully and continuously outlined with Windows, follow the following recommendations :

* Do not use any version prior to Windows 10 as they are vulnerable/insecure
* Never connect with a Microsoft account
* Completely disable Cortana
* Disable activity history
* Go in the settings, under "privacy" and deactivate everything in each of the categories except for the necessary authorizations for the applications used
* Uninstall (or when it is not possible to deactivate) Edge, Microsoft OneDrive, antivirus (except Microsoft Defender) and all unused applications
* Enable random MAC address in Wi-Fi settings
* Preferably use another session than the administrator for daily use
* Install the ShutUp10 program to have more control over privacy

**MX Linux**

Flash plugin :
Enter the following command in the terminal to remove the proprietary Flash plugin :
sudo apt purge --remove adobe-flashplugin flashplugin-installer pepperflashplugin-nonfree

Advert Blocker :
Select all the options except "UNBLOCK" and then confirm.

Wi-Fi configuration :
Right click on the Wi-Fi icon, modify the connections, select the active Wi-Fi,
under Wi-Fi select Cloned MAC Address: Random.
Under IPv6 settings, select IPv6 Confidentiality Extensions : On (preferred temporary address).

### 8-2 F-Droid

In order to find and download some applications from F-Droid, it is necessary to add their repositories. To do this, go to the F-Droid settings, then under "repositories", activate the "Guardian Project" repository and finally press the "+" and enter the desired mentioned addresses :

* Bromite :
https://fdroid.bromite.org/fdroid/repo

* Mull :
https://divestos.org/fdroid/official

* Ungoogled Chromium :
https://www.droidware.info/fdroid/repo

* Newpipe :
https://archive.newpipe.net/fdroid/repo

It may happen that Newpipe stops working due to modifications made by Google on YouTube. In order to quickly benefit from the latest updates by correcting these problems, it is recommended to add Newpipe's own repository.

* Langis (Signal) :
https://gitlab.com/TheCapsLock/fdroid-patched-apps/raw/master/fdroid/repo

Langis is a modified version of Signal to use as a last resort if notifications do not arrive with the classic version of Signal from Aurora Store.

* Session :
https://fdroid.getsession.org/fdroid/repo

* Bitwarden :
https://mobileapp.bitwarden.com/fdroid/repo

Version without the third-party trackers present in the Google Play version.

* Nebulo :
https://fdroid.frostnerd.com/fdroid/repo

* Collabora Office :
https://www.collaboraoffice.com/downloads/fdroid/repo

### 8-3 Apps and software

**Telegram**

Start secret chats so that conversations are end-to-end encrypted
extreme and do not go through the Telegram servers:
contact profiles> the three dots above> start secret chat

Disable link preview in secret chats to avoid requesting links
Telegram servers:

Settings> Privacy and security> Secret chats> Link preview

**Blokada**

Blocklists > enable the following blacklists:

- OISD
- Phishing Army
- DuckDuckGo Tracker Radar
- Exodus Privacy
- Combined Privacy
- URLhaus
- (Goodbye Ads : Samsung or Xiaomi (they only work for the models of those brands))

Encryption > select a DNS server from the following:
DoH: Blah DNS, Digitale Gesellschaft (Europe), (OpenNIC).
((Not encrypted: DNS.Watch, Uncensored DNS, French Data Network (Europe))).

**FreeTube**

Use Invidious as a proxy to avoid transmitting your data to Google:

Settings :
- Player Settings: enable "Proxy Videos Through Invidious"
- Advanced Settings: enter a functional Invidious instance

In case of problem, change the instance or simply deactivate "Proxy Videos
Through Invidious ".

### 8-4 Firefox

**General configuration**

The configuration proposed down there being relatively restrictive in order to protect the privacy of the user, it is recommended to follow the compartmentalization proposed in point 5 of the document and thus use at least one other browser to be able to access the sites less respectful of privacy.

Profiles:

Firefox offers the ability to use several different profiles (settings) at the same time. It is an ideal solution for a quick and simple transition from a restrictive configuration preventing a web page from loading correctly towards a lighter configuration, without having to change the browser. The different settings provided, extensions installed or bookmarks added will be saved in the profile in use.

To access the different Firefox profiles, enter "about:profiles" in the search bar. This page allows you to create new profiles and then launch them in a separate new window at any time.

DNS over HTTPS :

If you use a VPN or if your network or computer is configured to use a respectful and encrypted DNS server globally, you must disable the "DNS over HTTPS" feature enabled by default in Firefox. If this is not the case (if you do not know, it is probably not the case), it is recommended to leave this function activated. Now, it is necessary to change the default DNS server since Cloudflare is a centralizing actor and nefarious for privacy. Instead of the latter, it is recommended to choose a respectful option proposed in point 6.4 of the document, depending on your
preferences and location.

For this: Firefox settings> "General"> down "Network settings"> down "Activate DNS
over HTTPS ".

Here are the rest of the general settings recommended in images:


<img src="https://raw.githubusercontent.com/adgellida/data-protection-list/master/images/1.png" width="750">
<img src="https://raw.githubusercontent.com/adgellida/data-protection-list/master/images/2.png" width="750">
<img src="https://raw.githubusercontent.com/adgellida/data-protection-list/master/images/3.png" width="750">
<img src="https://raw.githubusercontent.com/adgellida/data-protection-list/master/images/4.png" width="750">
<img src="https://raw.githubusercontent.com/adgellida/data-protection-list/master/images/5.png" width="750">
<img src="https://raw.githubusercontent.com/adgellida/data-protection-list/master/images/6.png" width="750">

**Extension settings**

It is important to authorize these extensions to work in private browsing and activate
its automatic updates.

uBlock :
- Settings : activate everything under "Privacy"
- Filter Lists : activate ALL lists, except under “Regions” (only activate for
languages used)
- (Add the lists from filterlists.com: Energized: Ultimate Protection, Xtreme + IP +
Social extension)
- Follow the tutorial on the following web page to set the filtering rules
dynamic (optional but recommended):

https://www.maketecheasier.com/ultimate-ublock-origin-superusers-guide/

Chameleon :

<img src="https://raw.githubusercontent.com/adgellida/data-protection-list/master/images/11.png" width="450"><img src="https://raw.githubusercontent.com/adgellida/data-protection-list/master/images/22.png" width="450">
<img src="https://raw.githubusercontent.com/adgellida/data-protection-list/master/images/33.png" width="450"><img src="https://raw.githubusercontent.com/adgellida/data-protection-list/master/images/44.png" width="450">
<img src="https://raw.githubusercontent.com/adgellida/data-protection-list/master/images/55.png" width="450">

Decentraleyes :
No configuration necessary

CanvasBlocker :
General: - check "Expert mode"
         - Presets > open > Stealth mode
         - Random number generator: non persistent
APIs : check "Protect Window api" + accept captcha exception
Misc : uncheck "Block data URL pages"

ClearURLs :
request types:
beacon,csp_report,font,image,imageset,main_frame,media,object,object_subrequest,
other,ping,script,speculative,stylesheet,sub_frame,web_manifest,websocket,xbl,xml_dtd,xmlhttprequest,xslt

Cookie AutoDelete :
- Automatic Cleaning Options: activate all
- Extension Options: disable "Show notification after cookie cleanup"

Privacy Redirect :
General : - select the desired instances
Advanced : - enable "Always proxy videos through Invidious"
- Select "DASH" under "Invidious video quality"

(HTTPS Everywhere) :
- Only necessary for Firefox versions in which the "HTTPS-Only Mode" not yet implemented: Firefox ESR and mobile (Fennec)
- No configuration necessary

**about:config settings**

Access these settings by entering about: config in the Firefox address bar.
Those various settings improve privacy, security, and performance.
Items in parentheses are generally not desirable in all cases.

accessibility.blockautorefresh = true

((accessibility.force_disabled = 1))

beacon.enabled = false

browser.cache.offline.capacity = 0

browser.cache.offline.enable = false

browser.display.use_document_fonts = 0

browser.send_pings.max_per_link = 0

browser.sessionhistory.max_entries = 15

Maximum number of pages available with "precedent", Firefox lightens

browser.sessionhistory.max_total_viewers = 4

Maximum number of pages loaded with "precedent", Firefox lightens

browser.sessionstore.interval = 50000

browser.sessionstore.privacy_level = 2

(browser.startup.homepage_override.buildID = delete)

browser.urlbar.autofill.enabled = false

(browser.urlbar.maxRichResults = 0)

browser.urlbar.speculativeConnect.enabled = false

browser.urlbar.trimURLs = false

browser.xul.error_pages.expert_bad_cert = true

captivedetect.canonicalURL = delete

device.sensors = false for all elements

dom.allow_cut_copy = false

dom.battery.enabled = false

dom.enable_performance = false

dom.enable_resource_timing = false

dom.event.clipboardevents.enabled = false

dom.event.contextmenu.enabled = false

dom.push = false for all elements + delete addresses and identifiers

dom.serviceWorkers.enabled = false

dom.vr.oculus.enabled = false

dom.webaudio.enabled = false

gamepad = false for all elements

geo = delete all addresses

geo.enabled = false

(gfx.font_rendering.graphite.enabled = false)

google = false for all items + clear addresses

javascript.options.baselinejit = false

javascript.options.ion = false

javascript.options.native_regexp = false

layers.acceleration.force-enabled = true

layout.css.visited_links_enabled = false

mathml.disabled = true

((media.gmp-widevinecdm.enabled = false))

((Disable DRM, yes DRM videos not necessary))

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

normandy = false for all elements + clear addresses and identifiers

pocket = false for all items + clear addresses and identifiers

privacy.clearOnShutdown.offlineApps = true

privacy.spoof_english = 2

privacy.trackingprotection.socialtracking.enabled = true

report (reporter/reporting) = false for all items + delete addresses

safebrowsing = false for all items + clear addresses and identifiers

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

telemetry = false for all items + clear addresses and identifiers

ui.use_standins_for_native_colors = true

webgl.disabled = true

webgl.enable-debug-renderer-info = false

webgl.enable-webgl2 = false

**Only if Chameleon extension is not used :**

(privacy.resistFingerprinting = true)

(Better to put "false" and fake the fingerprint with Chameleon)

These should be configured directly with Chameleon if it is installed:

media.peerconnection.ice.default_address_only = true

media.peerconnection.ice.no_host = true

((media.peerconnection.enabled = false))

privacy.firstparty.isolate = true