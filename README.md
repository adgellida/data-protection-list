<img src="https://raw.githubusercontent.com/adgellida/data-protection-list/main/images/privacy-first.png" width="80"> data-protection-list
=============================================

Manual of resistance to capitalism of vigilance

# Languages

<p align="center">
  <a href="https://github.com/adgellida/data-protection-list/README.md" target="_blank"><img src="https://raw.githubusercontent.com/adgellida/data-protection-list/main/images/languages/united-kingdom.png" width="80"></a>
  <a href="https://github.com/adgellida/data-protection-list/READMEesES.md" target="_blank"><img src="https://raw.githubusercontent.com/adgellida/data-protection-list/main/images/languages/spain.png" width="80"></a>
  <a href="https://github.com/adgellida/data-protection-list/READMEfrFR.md" target="_blank"><img src="https://raw.githubusercontent.com/adgellida/data-protection-list/main/images/languages/france.png" width="80"></a>
</p>

# Index

* [0 Comments about fork](#0-comments-about-fork)
* [1 Introduction](#1-introduction)
* [2 Gold rules](#2-gold-rules)
* [3 Computer](#3-computer)
* [3-1 Operating Systems](#3-1-operating-systems)
* [3-2 Services and programs](#3-2-services-and-programs)
* [4 Smartphone](#4-smartphone)
* [4-1 Operating Systems](#4-1-operating-systems)
* [4-2 Preinstalled hardware](#4-2-preinstalled-hardware)
* [4-3 Aplications](#4-3-aplications)
* [5-Browsers](#5-browsers)
* [5-1 Firefox](#5-1-firefox)
* [5-2 Tor Browser](#5-2-tor-browser)
* [6 Service instances](#6-service-instances)
* [6-1 Searx](#6-1-searx)
* [6-2 Invidious](#6-2-invidious)
* [6-3 Video calls/video conferencing](#6-3-video-calls/video-conferencing)
* [6-4 DNS](#6-4-dns)
* [7 Recursos adicionales y fuentes](#7-additional-resources-and-sources)
* [8 Configurations](#8-configurations)
* [8-1 Computer](#8-1-computer)
* [8-2 Smartphone](#8-2-smartphone)
* [8-3 Firefox](#8-3-firefox)

## 0 Comments about fork

I have seen the need to fork this document of Valentin Delacour hosted [here](https://codeberg.org/PrivacyFirst/PrivacyFirst/issues) under his approval and license to give it more visibility, readability, comfort, improvement in some aspects and participation. If someone forks any of the 2 they should do the same.

I think that we should share how much more the better and the knowledge about good practices to follow regarding security, privacy and open source that are detailed are no exception.

We are open to changing the format of this document, for now I have thought that this is a good way, but it could be improved.

I don't consider myself an expert on the subject. In fact I do not follow all the recommendations to the letter. But I would like over time to leave aside services that I think I should not use for various reasons, change ways of accessing certain content, use other strategies, etc.

To actively participate you can:

* [Create pull requests](https://github.com/adgellida/data-protection-list/pulls)
* [Generate your questions or incidents](https://github.com/adgellida/data-protection-list/issues)

I recommend you participate in:

* [Official Telegram Group](https://t.me/privacid)
* [Official Discord Group](https://discord.gg/b9ey65Q) - Although due to various privacy and security reasons we do not recommend it.
* Official Element group - Request invitation

The objective of the group is to collectively promote good customs in terms of privacy, security and also open source/free programs/apps, services and operating systems to resist the collection and exploitation of personal data by private companies.

I think that they take advantage of the ignorance of the majority to do things that they should not and benefit from it behind our backs. The good thing is that there are people who realize it because they understand the subject and share it with the community.

This document has been copied 1: 1 with very slight modifications in version 7/12/2020 and from now on it will undergo modifications following the following strategies:

- Following updates of the original file
- Pull requests from the community
- Own discoveries

Now, the document begins. Put on your belt curves are coming!

## 1 Introduction

The main objective of this document is to propose tools and alternatives to protect data and privacy from predation by private companies under the current system of surveillance capitalism. Now, follow the following
recommendations also allows to improve, in certain measures, the protection against other entities such as state services or pirates, for example.

This list is intended for all persons aware or aware of the importance of data protection in our society, regardless of your knowledge of the subject. It is not intended for people needing anonymity total part of their function to risks such as political opponents or some journalists, even if some proposed options might suit them. Effectively, privacy does not necessarily equal anonymity.

The list format was chosen in order to make your query as efficient as possible possible. This approach precludes detailing true explanations. So I invite you to look for the ones they need on their own or in additional resources mentioned in point 6 of the document. With the purpose of proposing the more reputable and practical options without being too stuffy, the list does not have to vocation to be exhaustive and remains subjective despite seeking to have the greatest possible objectivity.

This list proposes a first prioritization (order of appearance and presence or not of parentheses) subjective based on the privacy / usability report in order to help them choose between the different options mentioned. A second prioritization (colors) is based solely on estimated privacy: green (true respect for privacy), blue (respect for privacy under conditions or presence of a problematic item), red (does not guarantee privacy but still being preferable to the GAFAM options) and colorless (lack of elements to
form an estimate, or a prioritization is not relevant for entry into question). The presence of an asterisk indicates that the mentioned option is still in development phase.

I hope this document will help you improve the protection of your data personal and those of her close ones. Although being the fruit of several years of searches and experiments, this work obviously remains perfectible.
Any suggestion or comment is then more than welcome to the email: "Privacyfirst@ik.me". Several months after the present version of the document, you must assume that certain information given will be obsolete. The document being
frequently updated, you are invited to get the latest version on the following website: “https://codeberg.org/PrivacyFirst/PrivacyFirst/issues”.


## 2 Gold rules

* Avoid using GAFAM services and programs (Google, Amazon, Facebook, Apple and Microsoft) WHENEVER possible. It is best to remove your eventual accounts.
* Always review all the settings and authorizations of what is used and optimize them to limit the collection of personal data as much as possible.
* Only install the necessary programs / applications as they are potential accesses to your personal data.
* Use free / open source programs (their codes are public and also verifiable) instead of proprietary / closed source whenever possible.
* Favor the popular free options over the unknown ones (they will be more reviewed / reliable).
* If a company offers its services for free, in general, the product it sells is you (your personal data). Due to the model imposed by the surveillance capitalism, pay now or protect them from also being the product.
* Update your programs / operating systems frequently to benefit from the latest fixes for exploitable security flaws and think about replacing the ones that no longer seem to be up to date.
* Do not use third-party antivirus, they are true vacuum cleaners of personal data. Their contribution is negligible as long as good numerical habits are maintained.
Prudence and a good configuration are the best antivirus.
* Privilege Web Apps or shortcuts from the browser to access services instead of applications to install to limit access and the possibilities of collecting
personal information.
* Use temporary emails to create accounts for unimportant sites / services.
* Always disable Wi-Fi, Bluetooth, and geolocation on your smartphone when not in use and don't connect to public Wi-Fi without using a VPN.
* Do not use connected objects (their purpose is to collect as much personal data as possible) or not connect them to the internet when they are essential.

## 3 Computer

### 3-1 Operating Systems

Windows is currently the worst operating system in terms of privacy and security. The only OS that is easy to use and truly protecting data are the free (therefore free) Linux distributions. There is a multitude of them whose characteristics vary considerably. Here is a small selection of those offering the best user experience (always respecting privacy) or guaranteeing the best data protection. It should be remembered that each of them proposes one or more interfaces (desktop) different in terms of experience, resource consumption and appearance. There is abundant documentation online to choose which one layout and desktop environment will best suit the capabilities of your computer and your preferences as well as how to easily install it on his computer.

**Desktop :**

🟢[Linux Mint](https://linuxmint.com) : great for beginners

🟢[MX Linux](https://mxlinux.org) : suits beginners

🟢[Solus](https://getsol.us/home) : suits beginners

🟢[Parrot Home](https://www.parrotsec.org/download) : improved security and privacy (confirmed users)

🟢[Qubes OS](https://www.qubes-os.org) : extreme security (advanced users)

🟢[Whonix](https://www.whonix.org) : anonymity by Tor and extreme security (advanced users)

**USB live (RAM) :**

🟢[MX Linux](https://mxlinux.org) : suits beginners

🟢[Tails](https://tails.boum.org) : anonymity by Tor (confirmed users)

🟢[Parrot Home](https://www.parrotsec.org/download) : improved security and privacy (confirmed users)

**Raspberry Pi :**

🟢[Plasma BigScreen*](https://plasma-bigscreen.org) : multimedia center for TV (voice command with Mycroft AI)

🟢[Raspberry Pi OS](https://www.raspberrypi.org/software) : classic operating system

🟢[LibreELEC](https://libreelec.tv) : multimedia center for TV

🟢[Batocera](https://batocera.org) : console emulator, retrogaming

🟢[RetroPie](https://retropie.org.uk) : console emulator, retrogaming

### 3-2 Services and programs

Browser :

🔵[Firefox](https://www.mozilla.org)

🟢[Tor Browser](https://www.torproject.org/download)

🟢[LibreWolf*](https://librewolf-community.gitlab.io)

🔵[Iridium Browser](https://iridiumbrowser.de)

🔴[Brave](https://brave.com)

Seeker :

🔵[Qwant](https://www.qwant.com)

🔵[Swisscows](https://swisscows.com)

🔵[searx.me](https://searx.me)

🔴[Startpage](https://www.startpage.com) (proxy Google)

🔴[DuckDuckGo](https://duckduckgo.com)

Office automation :

🟢[LibreOffice](https://www.libreoffice.org)

🟢[CryptPad](https://cryptpad.fr)

⚫[Onlyoffice](https://www.onlyoffice.com)

Mail :

🔵[Tutanota](https://tutanota.com)

🔵[Protonmail](https://protonmail.com)

🔵[CTemplar](https://ctemplar.com)

🔵[Posteo](https://posteo.de)

Video platform :

🔵[Invidious](https://invidio.us) (proxy Youtube)

🔵[CloudTube](https://cadence.moe/cloudtube/subscriptions) (proxy Youtube)

🔵[FreeTube](https://freetubeapp.io) (cliente Youtube/Invidious)

🟢[PeerTube](https://joinpeertube.org)

🔵[LBRY](https://lbry.com)

Instant messaging :

🟢[Signal](https://signal.org)

🔵[Telegram](https://telegram.org)

🔵[Element](https://app.element.io)

⚫[Session*](https://getsession.org)

Video calls/video conferencing :

🟢[Jitsi Meet](https://meet.jit.si)

🟢[Signal](https://signal.org)

🔵[BigBlueButton](https://bigbluebutton.org)

🟢[Jami](https://jami.net)

🔵[Element](https://app.element.io)

🔵[Telegram*](https://telegram.org)

Social network :

🟢[Mastodon](https://mastodon.social)

🟢[Friendica](https://friendi.ca)

🟢[Diaspora](https://diasporafoundation.org)

🟢[PixelFed](https://pixelfed.org)

🔵[Nitter](https://nitter.net) (proxy Twitter)

🔵[Bibliogram](https://bibliogram.art) (proxy Instagram)

Translator :

🟢[Apertium](https://www.apertium.org)

🔴[DeepL](https://www.deepl.com/translator)

🟢[Bergamot Project*](https://browser.mt)

Maps :

🟢[OpenStreetMap](https://www.openstreetmap.org)

🔴[Maps.me](https://maps.me)

🟢[Qwant Maps*](https://www.qwant.com/map)

🔴[DuckDuckGo](https://duckduckgo.com)

File sharing :

🟢[Disroot](upload.disroot.org)

🔵[Swisst Transfer](swisstransfer.com)

🟢[OnionShare](https://onionshare.org)

Colaboration :

🟢[CryptPad](https://cryptpad.fr)

Password manager :

🟢[Bitwarden](https://bitwarden.com)

🟢[KeePassXC](https://keepassxc.org)

Media player :

🟢[VLC](https://www.videolan.org)

VPN :

🟢[IVPN](https://www.ivpn.net)

🔵[Mullvad](https://mullvad.net)

🔵[ProtonVPN](https://protonvpn.com)

⚫[Firefox VPN*](https://vpn.mozilla.org)

Cloud :

🟢[Disroot](https://cloud.disroot.org) (Nextcloud)

🟢[Cozy Cloud](https://cozy.io)

🟢[Nextcloud](https://nextcloud.com)

🔵[Kdrive](https://www.infomaniak.com/es/kdrive) (Infomaniak)

Temporary mail:

⚫[Temp Mail](temp-mail.org)

⚫[Guerrillamail](guerrillamail.com)

⚫[EmailOnDeck](https://www.emailondeck.com)

Notes :

🟢[Joplin](https://joplinapp.org)

🟢[Standard Notes](https://standardnotes.org)

System cleaning and optimization :

🟢[Stacer](https://oguzhaninan.github.io/Stacer-Web)

🟢[ubunsys](https://github.com/adgellida/ubunsys)

🟢[BleachBit](https://www.bleachbit.org)

Image editing and drawing :

🟢[Gimp](http://www.gimp.org)

🟢[Drawing](https://maoschanz.github.io/drawing)

🟢[Krita](https://krita.org)

🟢[Darktable](https://www.darktable.org)

🟢[RawTherapee](https://rawtherapee.com)

Vector graphics editing :

🟢[Inkscape](https://inkscape.org)

Page layout :

🟢[Scribus](https://www.scribus.net)

Audio editing :

🟢[Audacity](https://www.audacityteam.org)

Video editing :

🟢[OpenShot](https://www.openshot.org)

🟢[Kdenlive](https://kdenlive.org)

🟢[Avidemux](https://www.avidemux.org)

🟢[Pitivi](http://www.pitivi.org)

🟢[Cinelerra](http://cinelerra.org)

Metadata suppression :

🟢[ExifCleaner](https://exifcleaner.com)

Encryption tool :

🟢[VeraCrypt](https://www.veracrypt.fr)

🟢[Cryptomator](https://cryptomator.org)

Network traffic analysis:

🟢[Wireshark](https://www.wireshark.org)

Windows programs/games under Linux :

⚫[PlayOnLinux](https://www.playonlinux.com)

⚫[Wine](https://www.winehq.org)

⚫[WinApps*](https://github.com/Fmstrat/winapps)

## 4 Smartphone

### 4-1 Operating Systems

Android, in its default configuration, is currently the worst operating system in terms of privacy. Its purpose is to continuously send personal data to Google's servers to exploit and sell them. The most recommended solution today is to use a modified version of Android (custom ROM) to respect privacy. If you do not want to install or buy a smartphone with a respectful operating system (serious mistake), remember that you should absolutely avoid all Chinese brands and also Samsung. In an effort not to be fully and continuously profiled, it is essential to never connect with a Google account and use a tracker blocker. Apple's operating system (iOS), despite its marketing based on respect for privacy, also collects and exploits the personal data of its users, although without common measure to Android by default. Apple controls and limits its users more than Android, but it also offers more security and privacy protections against third parties.

**Android modified for privacy :**

🟢[CalyxOS](https://calyxos.org) : Android degooglized and secure with microG for better compatibility

🟢[/e/ OS](https://e.foundation) : Degooglized LineageOS but with microG and integrated services (/ e / account)

🟢[GrapheneOS](https://grapheneos.org) : the most private and secure degooglized Android available

🔵[LineageOS for microG](https://lineage.microg.org) : LineageOS with microG for better compatibility

🔵[Volla OS](https://volla.online): Safe Android, without Google apps but not totally degooglized

🔵[LineageOS](https://lineageos.org) : Android without Google apps but not totally degooglized

**Linux :**

🟢[UBports](https://ubports.com)

🟢[Postmarket OS*](https://ubports.com)

🟢[PureOS*](https://pureos.net)

🟢[Manjaro*](https://manjaro.org)

🟢[Mobian*](https://mobian-project.org)

🔵[Sailfish OS Jolla](https://jolla.com)

Linux-based options, in their current state of development, are not yet recommended for average users (except Sailfish OS).

### 4-2 Preinstalled hardware

[Fairphone 3 y 3+](https://www.fairphone.com) : /e/ OS (version only available on project site /e/)

[Volla Phone](https://volla.online) : Volla OS, UBports, Sailfish OS and others

[PinePhone](https://www.pine64.org/pinephone) : UBports and other Linux-based OS

[Librem 5](https://puri.sm/products/librem-5) : PureOS and other Linux-based OS

Other models with / e / OS pre-installed are available at the / e / project site:

https://esolutions.shop/

### 4-3 Aplications

The proposed applications for Android and derivatives must be searched first in the free F-Droid application store (guarantee that they do not have third-party trackers) and only if they are not, in the Aurora Store. These stores must be downloaded directly from their respective official web pages.

[F-Droid](https://f-droid.org/en)
[Aurora Store](https://auroraoss.com/downloads.php)

**Android and derivatives :**

App store :

🟢[F-Droid](https://f-droid.org)

🔵[Aurora Store](https://auroraoss.com) (proxy Play Store)

🔵[APKMirror](https://www.apkmirror.com)

Browser :

🟢[Tor Browser](https://www.torproject.org/es/download/#android)

🟢[Bromite](https://www.bromite.org/fdroid)

🔵[Fennec](https://f-droid.org/en/packages/org.mozilla.fennec_fdroid) (Firefox)

🟢[Privacy Browser](https://f-droid.org/es/packages/com.stoutner.privacybrowser.standard)

Instant messaging :

🟢[Signal](https://signal.org)

🔵[Telegram](https://telegram.org)

🔵[Element](https://app.element.io)

🟢[Briar](https://briarproject.org)

🟢[Conversations](https://conversations.im)

⚫[Session*](https://getsession.org)

Video calls/video conferencing :

🟢[Jitsi Meet](https://meet.jit.si)

🟢[Signal](https://signal.org)

🔵[Element](https://app.element.io)

🟢[Jami](https://jami.net)

🔵[Telegram](https://telegram.org)

Video platform :

🔴[Newpipe](https://newpipe.schabi.org) (cliente Youtube)

🔵[LBRY](https://lbry.com)

🔴[Skytube](https://skytube-app.com) (cliente Youtube)

Keyboard :

🟢[OpenBoard](https://f-droid.org/es/packages/org.dslul.openboard.inputmethod.latin)

🟢[AnySoftKeyboard](https://anysoftkeyboard.github.io)

Maps/GPS navigation:

🟢[Maps](https://f-droid.org/es/packages/com.github.axet.maps) (OpenStreetMap)

🟢[OsmAnd](https://f-droid.org/es/packages/net.osmand.plus/)

🔵[Magic Earth](https://www.magicearth.com)

Ad/Tracker Blocker:

🟢[Blokada](https://f-droid.org/es/packages/org.blokada.alarm)

🟢[Nebulo](https://play.google.com/store/apps/details?id=com.frostnerd.smokescreen&hl=es&gl=US)

🟢[personalDNSfilter](https://www.zenz-solutions.de/personaldnsfilter-wp)

Mail client :

🟢[Tutanota](https://f-droid.org/es/packages/de.tutao.tutanota)

🟢[Protonmail](https://protonmail.com)

🟢[CTemplar](https://f-droid.org/es/packages/com.ctemplar.app.fdroid)

🟢[K-9 Mail](https://f-droid.org/es/packages/com.fsck.k9)

Alias manager for mail :

🟢[Simple Login](https://simplelogin.io)

Password manager client :

🟢[Bitwarden](https://bitwarden.com)

🟢[KeePassDX](https://f-droid.org/es/packages/com.kunzisoft.keepass.libre)

Two-factor authentication :

🟢[Aegis](https://f-droid.org/es/packages/com.beemdevelopment.aegis)

🟢[andOTP](https://f-droid.org/en/packages/org.shadowice.flocke.andotp)

Web Apps :

🟢[WebApps](https://f-droid.org/en/packages/com.tobykurien.webapps)

Redirector of content YouTube, Twitter, Instagram and Google Map :

🟢[UntrackMe](https://f-droid.org/en/packages/app.fedilab.nitterizeme)

Client Mastodon, Friendica, Peertube y PixelFed :

🟢[Fedilab](https://f-droid.org/en/packages/fr.gouv.etalab.mastodon)

🟢[Tusky](https://f-droid.org/en/packages/com.keylesspalace.tusky) (Mastodon)

Respectful client respetuoso Facebook/Twitter/Instagram :

🔴[Frost for Facebook](https://f-droid.org/es/packages/com.pitchedapps.frost)

🔴[Twidere](https://f-droid.org/es/packages/org.mariotaku.twidere)

🔴[Barinsta](https://f-droid.org/en/packages/me.austinhuang.instagrabber) (Instagrabber)

Schedule :

🟢[Simple Calendar](https://f-droid.org/es/packages/com.simplemobiletools.calendar.pro)

🟢[Etar](https://f-droid.org/es/packages/ws.xsoh.etar)

Notes :

🟢[Joplin](https://play.google.com/store/apps/details?id=net.cozic.joplin&utm_source=GitHub&utm_campaign=README&pcampaignid=MKT-Other-global-all-co-prtnr-py-PartBadge-Mar2515-1)

🟢[Nextcloud Notes](https://f-droid.org/es/packages/it.niedermann.owncloud.notes)

🟢[Simple Notes](https://f-droid.org/es/packages/com.simplemobiletools.notes.pro)

🟢[Standard Notes](https://play.google.com/store/apps/details?id=com.standardnotes)

File manager :

🟢[Simple File Manager](https://f-droid.org/es/packages/com.simplemobiletools.filemanager.pro)

Gallery :

🟢[Simple Gallery](https://f-droid.org/es/packages/com.simplemobiletools.gallery.pro)

Audioplayer :

🟢[Music Player GO](https://f-droid.org/es/packages/com.iven.musicplayergo)

🟢[Vinyl Music Player](https://f-droid.org/es/packages/com.poupa.vinylmusicplayer)

PDF :

🟢[PDF Viewer Plus](https://f-droid.org/es/packages/com.gsnathan.pdfviewer)

🟢[MuPDF Viewer](https://f-droid.org/es/packages/com.artifex.mupdf.viewer.app)

Contacts :

🟢[Open Contacts](https://f-droid.org/es/packages/opencontacts.open.com.opencontacts)

🟢[Simple Contacts](https://f-droid.org/es/packages/com.simplemobiletools.contacts.pro)

Camera :

🟢[Open Camera](https://f-droid.org/es/packages/net.sourceforge.opencamera)

🟢[Simple Camera](https://f-droid.org/es/packages/com.simplemobiletools.camera)

Radio :

🟢[RadioDroid](https://f-droid.org/es/packages/net.programmierecke.radiodroid2)

Metadata suppression :

🟢[ImagePipe](https://f-droid.org/es/packages/de.kaffeemitkoffein.imagepipe)

🟢[Scrambled Exif](https://f-droid.org/es/packages/com.jarsilio.android.scrambledeggsif)

To go further :

Third Party Tracker Developer :

🟢[ClassyShark3xodus](https://f-droid.org/es/packages/com.oF2pks.classyshark3xodus)

🟢[Exodus](https://f-droid.org/en/packages/org.eu.exodus_privacy.exodusprivacy)

Application stop (background):

🟢[SuperFreezZ](https://f-droid.org/es/packages/superfreeze.tool.android)

Applications Isolator :

🟢[Shelter](https://f-droid.org/en/packages/net.typeblog.shelter)

Network anonymization by Tor :

🟢[Orbot Proxy](https://play.google.com/store/apps/details?id=org.torproject.android&hl=es&gl=US)

Location simulator :

🟢[Private Location](https://f-droid.org/es/packages/com.wesaphzt.privatelocation)

Replacement of Google Services:

🔴[MicroG GmsCore](https://microg.org)

Privacy manager :

🟢[XprivacyLua](https://f-droid.org/es/packages/eu.faircode.xlua)

🟢[App Manager](https://f-droid.org/es/packages/io.github.muntashirakon.AppManager)

🟢[App Warden](https://forum.xda-developers.com/t/app-5-0-warden-app-manager.4122227) (root)

Application network isolator :

🟢[NetGuard](https://f-droid.org/es/packages/eu.faircode.netguard)

Network traffic monitor :

🟢[Net Monitor](https://f-droid.org/es/packages/org.secuso.privacyfriendlynetmonitor)

Microphone usage blocker :

🟢[PilferShush Jammer](https://f-droid.org/en/packages/cityfreqs.com.pilfershushjammer)

### IOS :

Browser :

🟢[Onion Browser](https://apps.apple.com/us/app/onion-browser/id519296448)

🔵[Firefox](https://apps.apple.com/us/app/navegador-firefox/id989804926)

🔵[DuckDuckGo Browser](https://apps.apple.com/us/app/duckduckgo-privacy-browser/id663592361)

🔴[Brave](https://apps.apple.com/us/app/brave-private-web-browser-vpn/id1052879175)

Instant messaging :

🟢[Signal](https://apps.apple.com/us/app/signal-mensajer%C3%ADa-privada/id874139669)

🔵[Telegram](https://apps.apple.com/us/app/telegram-messenger/id686449807)

🔵[Element](https://app.element.io)

⚫[Session*](https://apps.apple.com/us/app/session-private-messenger/id1470168868)

Video calls/video conferencing :

🟢[Jitsi Meet](https://apps.apple.com/us/app/jitsi-meet/id1165103905)

🟢[Signal](https://apps.apple.com/us/app/signal-mensajer%C3%ADa-privada/id874139669)

🔵[Element](https://app.element.io)

🟢[Jami](https://apps.apple.com/us/app/jami/id1306951055)

🔵[Telegram](https://apps.apple.com/us/app/telegram-messenger/id686449807)

Ad/Tracker Blocker :

🟢[Blokada](https://apps.apple.com/us/app/blokada/id1508341781)

🟢[Lockdown](https://apps.apple.com/us/app/lockdown-apps/id1469783711)

🟢[DNSCloak](https://apps.apple.com/us/app/dnscloak-secure-dns-client/id1452162351)

Video platform :

🔵[LBRY](https://lbry.tv/)

Mail client : 

🟢[Tutanota](https://apps.apple.com/us/app/tutanota/id922429609)

🟢[Protonmail](https://apps.apple.com/us/app/protonmail-correo-cifrado/id979659905)

🟢[CTemplar](https://apps.apple.com/us/app/ctemplar/id1495837525)

Alias manager for mail :

🟢[Simple Login](https://apps.apple.com/us/app/simplelogin-anti-spam/id1494359858)

Password manager client :

🟢[Bitwarden](https://apps.apple.com/us/app/bitwarden-gestor-de-contrase/id1137397744)

🟢[Strongbox](https://apps.apple.com/es/app/strongbox-keepass-pwsafe/id897283731) - KeePass & PwSafe

Two-factor authentication :

🟢[Tofu Authenticator](https://apps.apple.com/us/app/tofu-authenticator/id1082229305)

## 5 Browsers

Compartmentalization (using different browsers with different settings, depending on the tasks) is a recommended method to preserve privacy without sacrificing too much browsing comfort.
For example, it would be to use Firefox with a restrictive configuration for general navigation. Then, use another profile of the same Firefox or Firefox ESR, configured in a less restrictive way for sites that do not load correctly or that require a connection to a personal account, and another browser for the consultation of the most recalcitrant sites to a configuration for the privacy protection (Brave or Ungoogled Chromium without settings are ideal for that task). It is also conceivable to use another browser solely dedicated to e-banking or also Tor Browser for anonymous browsing.

### 5-1 Firefox

For Firefox to protect privacy, it needs to be configured appropriately (settings, extensions and about: config). All necessary settings are developed in point 8.3 of the document. These settings also apply to LibreWolf and, to a certain extent, for the mobile version of Firefox (Fennec).

**Extensions :**

Complete list :

uBlock Origin - [Chrome](https://chrome.google.com/webstore/detail/ublock-origin/cjpalhdlnbpafiamejdnhcphjbkeiagm) - [Firefox](https://addons.mozilla.org/es/firefox/addon/ublock-origin)

uMatrix - [Chrome](https://chrome.google.com/webstore/detail/umatrix/ogfcmafjalglgifnmanfmnieipoejdcf) - [Firefox](https://addons.mozilla.org/es/firefox/addon/umatrix) - Development ended - Alternative?

Decentraleyes - [Chrome](https://chrome.google.com/webstore/detail/decentraleyes/ldpochfccmkkmhdbclfhpagapcfdljkj) - [Firefox](https://addons.mozilla.org/es/firefox/addon/decentraleyes) - Finished development? - Alternative?

[Chameleon](https://github.com/ghostwords/chameleon) Finished development? - Alternative?

CanvasBlocker - [Chrome](https://chrome.google.com/webstore/detail/canvas-blocker-fingerprin/nomnklagbgmgghhjidfhnoelnjfndfpd) - [Firefox](https://addons.mozilla.org/es/firefox/addon/canvasblocker)

Cookie AutoDelete - [Chrome](https://chrome.google.com/webstore/detail/cookie-autodelete/fhcgjolkccmbidfldomjliifgaodjagh) - [Firefox](https://addons.mozilla.org/en-US/firefox/addon/cookie-autodelete)

ClearURLs - [Chrome](https://chrome.google.com/webstore/detail/clearurls/lckanjgmijmafbedllaakclkaicjfmnk) - [Firefox](https://addons.mozilla.org/es/firefox/addon/clearurls)

Privacy Redirect - [Chrome](https://chrome.google.com/webstore/detail/privacy-redirect/pmcmeagblkinmogikoikkdjiligflglb) - [Firefox](https://addons.mozilla.org/en-US/firefox/addon/privacy-redirect)

Light list :

uBlock Origin - [Chrome](https://chrome.google.com/webstore/detail/ublock-origin/cjpalhdlnbpafiamejdnhcphjbkeiagm) - [Firefox](https://addons.mozilla.org/es/firefox/addon/ublock-origin)

Decentraleyes - [Chrome](https://chrome.google.com/webstore/detail/decentraleyes/ldpochfccmkkmhdbclfhpagapcfdljkj) - [Firefox](https://addons.mozilla.org/es/firefox/addon/decentraleyes)

Cookie AutoDelete - [Chrome](https://chrome.google.com/webstore/detail/cookie-autodelete/fhcgjolkccmbidfldomjliifgaodjagh) - [Firefox](https://addons.mozilla.org/en-US/firefox/addon/cookie-autodelete)

HTTPS Everywhere - [Chrome](https://chrome.google.com/webstore/detail/https-everywhere/gcbommkclmclpchllfjekcdonpmejbdp) - [Firefox](https://addons.mozilla.org/es/firefox/addon/https-everywhere)

### 5-2 Tor Browser

The concept of Tor is to make Internet traffic pass through a network by anonymizing it. In the effort that the fingerprint of your browser (given among others by its configuration) does not betray your identity, Tor browsers are designed to
have the same footprint regardless of users. To avoid making the footprint of your Tor browser unique, no extensions should be installed and no modifications should be made to the "about: config" settings. To preserve the given anonymity, it is also necessary not to connect to accounts that could de facto override it.
The Tor network's anonymization method slows down uploads. Well, it is not recommended to use it for streaming or voluminous downloads.

## 6 Service instances

### 6-1 Searx

Searx is a meta search engine that does not transmit personal data to used search engines. It allows, if one wishes, a very advanced configuration. The different instances (available there: https://searx.space/) do not offer all the same guarantees of privacy protection (IP address log or not, etc.)

🟢https://search.disroot.org : Google results by default, no IP address log

🔵https://spot.ecloud.global : nicer interface but with IP address log

⚫https://searx.xyz : Google results (Startpage) by default


### 6-2 Invidious

Invidious gives access to YouTube content (proxy) without transmitting the personal data of its users to Google. Unfortunately, its different instances (available there: https://instances.invidio.us/) frequently suffer from problems caused by Google's measures taken to prevent their operation.
The Invidious instances that currently appear to be the most functional are

⚫https://invidious.snopyta.org

⚫https://invidious.xyz


### 6-3 Videoconference

**Jitsi Meet :**

🟢[FDN](https://talk.fdn.fr)

🟢[Snopyta](https://talk.snopyta.org)

🟢[/e/](https://visio.ecloud.global)

🟢[Framasoft](https://framatalk.org/accueil)

🟢[Calyx](https://meet.calyx.net)

🔵[Infomaniak](https://meet.infomaniak.com)

🔵[Jitsi](https://jitsi.org/jitsi-meet)

**BigBlueButton :**

🟢[FAImaison](https://bbb.faimaison.net/b)

🟢[Grifon](https://bbb.grifon.fr/b)

🟢[Nixnet](https://meet.nixnet.services/b)

### 6-4 DNS

**Intercontinental :**

With filters against ads, trackers and malicious domains :

🟢[NixNet](https://docs.nixnet.services/NixNet_DNS) (DoH, DoT)

🟢[BlahDNS](https://blahdns.com) (DoH, DoT, DNSCrypt)

🔵[Adguard](https://adguard.com/en/adguard-dns/overview.html) (DoH, DoT, DNSCrypt)

🔵[NextDNS](https://nextdns.io) (DoH, DoT, DNSCrypt)

NixNet DoH : https://adblock.any.dns.nixnet.xyz/dns-query
BlahDNS DoH (Japón) : https://doh-jp.blahdns.com/dns-query

Without filters :

🟢DNSWatch (not encrypted)

🟢UncensoredDNS (DoT)

DNS.Watch IPv4 : 84.200.69.80, 84.200.70.40
DNS.Watch IPv6 : 2001:1608:10:25::1c04:b12f, 2001:1608:10:25::9249:d69b

**Europe :**

With filters against ads, trackers and malicious domains :

🟢[BlahDNS](https://blahdns.com) (DoH, DoT, DNSCrypt)

🟢[LibreDNS](https://libredns.gr) (DoH, DoT)

BlahDNS DoH (Alemania) : https://doh-de.blahdns.com/dns-query
LibreDNS DoH (Alemania) : https://doh.libredns.gr/ads

Without filters :

🟢[Snopyta](https://snopyta.org) (DoH, DoT)

🟢[Digitale Gesellschaft](https://digitalegesellschaft.de) (DoH, DoT)

🟢[PowerDNS](https://www.powerdns.com) (DoH)

🟢[FDN](https://www.fdn.fr/actions/dns) (not encrypted)

## 7 Additional resources and sources

**General**

Excellent resources for understanding surveillance capitalism and its threats :

https://www.nogafam.es/blog/presentacion

The Social Media Dilemma, Jeff Orlowski (film)
The Age of Surveillance Capitalism, Shoshana Zuboff (book)

Easy tutorials for privacy :

https://spreadprivacy.com/tag/device-privacy-tips

Great channels about privacy (with tutorials):

The Hated One : https://www.youtube.com/channel/UCjr2bPAyPV7t35MvcgT3W8Q

Techlore : https://www.youtube.com/channel/UCs6KfncB4OV6Vug4o_bzijg

Associations for the defense of privacy (information) :

https://www.laquadrature.net/es/
https://www.eff.org/deeplinks

Associations proposing excellent services respectful of privacy:

https://disroot.org/es/
https://framasoft.org/en/
https://snopyta.org/
https://www.drycat.fr/en

Good data protection practices:

https://www.vice.com/en_us/article/d3devm/motherboard-guide-to-not-getting-hacked-online-safety-guide

Excellent site listing respectful services and programs:

https://www.privacytools.io/

Recommended operators:

https://www.eff.org/pages/quien-defiende-tus-datos

**Telegram groups and channels**

Privacidad, protección de datos y más :
[t.me/privacid](t.me/privacid)
[t.me/techloregroup](t.me/techloregroup)
[t.me/techloreofficial](t.me/techloreofficial)
[t.me/NoGoolag](t.me/NoGoolag)

Linux y libre :
[Proyecto tic tac](t.me/grupo_telegram_proyectotictac)
[LinuxMintEs](t.me/LinuxMintEs)
[mxantixes](t.me/mxantixes)

**Operating Systems**

Linux :

[Linux Mint](https://linuxmint.com)

[MX Linux](https://mxlinux.org)

Privacy-friendly Android :

[CalyxOS](https://calyxos.org/what)

[/e/ OS](https://e.foundation)

**Firefox**

[Firefox configuration](https://www.youtube.com/watch?v=tQhWdsFMc24)

[Firefox basic configuration](https://12bytes.org/articles/tech/firefox/the-firefox-privacy-guide-for-dummies)

[Firefox advanced configuration](https://12bytes.org/articles/tech/firefox/firefoxgecko-configuration-guide-for-privacy-and-performance-buffs)

## 8 Configurations

### 8-1 Computer

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

**FreeTube**

Use Invidious as a proxy to avoid transmitting your data to Google:
Settings : - Player Settings: enable "Proxy Videos Through Invidious"
- Advanced Settings: enter a functional Invidious instance

In case of problem, change the instance or simply deactivate "Proxy Videos
Through Invidious ".

### 8-2 Smartphone

**F-Droid**

In order to find and download some applications from F-Droid, it is necessary
add your repositories. For this, go to the F-Droid settings, then under
"repositories", activate the "Guardian Project" repository and finally press the "+" and
enter the desired addresses mentioned.

Bromite : https://fdroid.bromite.org/fdroid/repo

Langis (modified version of Signal to be used only if notifications do not arrive with
the classic version of Signal (Aurora Store)):
https://gitlab.com/TheCapsLock/fdroid-patched-apps/raw/master/fdroid/repo

**Blokada**

Blocklists > enable the following blacklists:
- Energized : Basic (or Blu if RAM memory less than 4gb)
- DuckDuckGo Tracker Radar
- Exodus Privacy
- (Goodbye Ads : Samsung or Xiaomi (they only work for the models of those brands))
Encryption > select a DNS server from the following:
DoH: Blah DNS, Digitale Gesellschaft (Europe), (OpenNIC).
((Not encrypted: DNS.Watch, Uncensored DNS, French Data Network (Europe))).

**Newpipe**

It may happen that Newpipe stops working due to modifications of part
from Google on Youtube. In an effort to benefit as quickly as possible and
automatically updates correcting these problems, it is recommended
install Newpipe directly from its official site instead of F-Droid:
https://newpipe.schabi.org/

### 8-3 Firefox

**General configuration**

<img src="https://raw.githubusercontent.com/adgellida/data-protection-list/master/images/1.png" width="750">
<img src="https://raw.githubusercontent.com/adgellida/data-protection-list/master/images/2.png" width="750">
<img src="https://raw.githubusercontent.com/adgellida/data-protection-list/master/images/3.png" width="750">
<img src="https://raw.githubusercontent.com/adgellida/data-protection-list/master/images/4.png" width="750">
<img src="https://raw.githubusercontent.com/adgellida/data-protection-list/master/images/5.png" width="750">

**Extension settings**

It is important to authorize these extensions to work in private browsing and activate
its automatic updates.

uBlock :
- Settings : activate everything under "Privacy"
- Filter Lists : activate ALL lists, except under “Regions” (only activate for
languages used)
- (Add the lists from filterlists.com: Energized: Ultimate Protection, Xtreme + IP +
Social extension)

Decentraleyes :
No configuration necessary

Chameleon :

<img src="https://raw.githubusercontent.com/adgellida/data-protection-list/master/images/11.png" width="450"><img src="https://raw.githubusercontent.com/adgellida/data-protection-list/master/images/22.png" width="450">
<img src="https://raw.githubusercontent.com/adgellida/data-protection-list/master/images/33.png" width="450"><img src="https://raw.githubusercontent.com/adgellida/data-protection-list/master/images/44.png" width="450">
<img src="https://raw.githubusercontent.com/adgellida/data-protection-list/master/images/55.png" width="450">

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

uMatrix :
Video tutorial : https://www.youtube.com/watch?v=TVozpo3zUBk

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

report (reporter / reporting) = false for all items + delete addresses

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

**Only if Chameleon extension is not used:**

(privacy.resistFingerprinting = true)

(Better to put "false" and fake the fingerprint with Chameleon)

These should be configured directly with Chameleon if it is installed:

media.peerconnection.ice.default_address_only = true

media.peerconnection.ice.no_host = true

((media.peerconnection.enabled = false))

privacy.firstparty.isolate = true