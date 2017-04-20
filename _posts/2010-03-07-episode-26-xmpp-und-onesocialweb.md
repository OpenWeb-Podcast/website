---
ID: 308
post_title: 'Episode 26 &#8211; XMPP und OneSocialWeb'
author: Matthias Pfefferle
post_date: 2010-03-07 01:24:28
post_excerpt: ""
layout: post
permalink: /308/episode-26-xmpp-und-onesocialweb/
published: true
enclosure:
  - |
    http://openwebpodcast.de/mp3/openweb26.mp3
    52211840
    audio/mpeg
---

![xmpp](http://blog.openwebpodcast.de/uploads/2010/03/xmpp.png "xmpp")Vor ein paar Wochen wurde auf der [FOSDEM](http://fosdem.org/2010/) erstmals das Projekt _[OneSocialWeb](http://onesocialweb.org/)_ vorgestellt: ein _free, open, and decentralized social_ Network basierend auf XMPP. [Christian](http://mrtopf.de) und ich ([Matthias](http://notizblog.org/)) haben uns für dieses Thema mal wieder tatkräftige Unterstützung geholt: [Raphael Kallensee](http://identi.ca/rkallensee) arbeite als Web-Entwickler in Mannheimer und bloggt unter [raphael.kallensee.name](http://raphael.kallensee.name/).

Viel Spaß beim hören:

<audio controls>
  <source src="http://openwebpodcast.de/mp3/openweb26.mp3" type="audio/mpeg">
  Ihr Browser unterstützt diesen Audio-Player nicht.
</audio>
<small>Länge: 0:57h (49.8 MB), <a href="http://openwebpodcast.de/mp3/openweb26.mp3">Download MP3</a></small>

(weiter unten gibt es auch noch zwei Videos)

### News

*   CCC und Innenminister fordern Datenbrief: [http://www.ccc.de/datenbrief](http://www.ccc.de/datenbrief)
*   [http://openidentityexchange.org/](http://openidentityexchange.org/) (Drummond Reed darüber: [http://datawithoutborders.net/dwb12/)](http://datawithoutborders.net/dwb12/%29)
*   [Karlsruhe kippt Vorratsdatenspeicherung](http://www.tagesschau.de/inland/bundesverfassungsgericht144.html)
*   Action Streams:
    *   [http://www.readwriteweb.com/archives/action_streams_a_new_idea_for_social_networks.php](http://www.gravity7.com/blog/media/2010/02/action-streams-blue-sky-proposal.html)
    *   [http://www.gravity7.com/blog/media/2010/02/action-streams-blue-sky-proposal.html](http://www.gravity7.com/blog/media/2010/02/action-streams-blue-sky-proposal.html)
    *   [http://wiki.activitystrea.ms/Actions](http://wiki.activitystrea.ms/Actions)
*   Facebook-Chat via XMPP: [http://blog.facebook.com/blog.php?post=297991732130](http://blog.facebook.com/blog.php?post=297991732130)

## Thema: XMPP

> "XMPP is to Jabber as HTTP is to the Web." - Peter Saint-André

*   langlebige TCP-Verbindung
*   2 XML-Streams: Client-Server und Server-Client
*   Die einzelnen XML-Snippets nennen sich Stanzas
*   Verschiedene Typen: message, presence, iq
*   XMPP ist dezentral
*   Client/Server-Architektur, aber auch federated
*   ähnlich IRC bzw. E-Mail von der Dezentralität her
*   user@server.tld sind bare JIDs
*   user@server.tld/<resource> sind full JIDs
*   Dadurch kann man mehrfach eingeloggt sein
*   Da gibt es auch noch eine Priorität, denn Kontakte schreiben zuerst normalerweise an die Bare JID.
*   Man kann auch direkt an die full JIDs schicken (passiert nach Gesprächsbeginn normalerweise dann automatisch durch den Client)
*   "Transports" können als eine Art Gateway zu proprietären IM-Netzwerken verwendet werden
*   Installationen:
    *   Ursprungsserver: Jabber.org
    *   Google Talk
        *   Jede E-Mail-Adresse ist ein XMPP-Account
    *   LiveJournal
    *   GMX/Web.de/1&1
        *   Jede E-Mail-Adresse ist ein XMPP-Account
    *   talkr.im
*   Server:
    *   ejabberd
    *   Openfire
    *   Tigase
    *   Prosody
*   Was für Clients gibt es? Beispiele:
    *   Psi
    *   [http://www.pidgin.im/](http://www.pidgin.im/)
    *   Adium, iChat
    *   Miranda
    *   Gajim
    *   Empathy
    *   bald: Swift (swift.im)
    *   --> [http://xmpp.org/software/clients.shtml](http://xmpp.org/software/clients.shtml)
*   Sehr stark und einfach erweiterbar (z.B. mit Namespaces)
    *   Viele der wichtigen Features sind "Erweiterungen"
    *   Community-getriebener Prozess der Standardisierung
    *   XSF (XMPP Standards Foundation) leitet die Standardisierung
*   Beispiele für Erweiterungen
    *   Multi-User Chat (MUC)
    *   PubSub
    *   PEP (Personal Eventing Protocol)
    *   Jingle (Voice-Chat)
    *   Service Discovery
    *   BOSH: XMPP über HTTP
        *   ermöglicht Web-Clients, die ausschließlich in JavaScript geschrieben sind
    *   Location-Infos
    *   --> [http://xmpp.org/extensions/](http://xmpp.org/extensions/)
*   Client-Bibliotheken für sehr viele Sprachen verfügbar, Beispiele:
    *   JavaScript: Strophe.js
    *   PHP: xmpphp
    *   C: libstrophe
    *   Java: Smack
    *   Python: SleekXMPP; Twisted
    *   Ruby: XMPP4R
    *   --> [http://xmpp.org/software/libraries.shtml](http://xmpp.org/software/libraries.shtml)

### Diverses

*   OAuth über XMPP [http://notizblog.org/2008/07/24/oauth-ueber-xmpp-jabber/](http://notizblog.org/2008/07/24/oauth-ueber-xmpp-jabber/)
*   AOL und XMPP [http://notizblog.org/2008/01/18/aol-will-xmppjabber-einsetzen/](http://notizblog.org/2008/01/18/aol-will-xmppjabber-einsetzen/)
*   WordPress und XMPP [http://notizblog.org/2009/09/14/xmpp-pubsub-on-wordpress-com/](http://notizblog.org/2009/09/14/xmpp-pubsub-on-wordpress-com/)
*   XMPP Standards Foundation: [http://xmpp.org/](http://xmpp.org/)
*   Einführung in XMPP: [http://www.slideshare.net/remko.troncon/xmpp-101](http://www.slideshare.net/remko.troncon/xmpp-101) bzw. [http://metajack.im/2010/02/16/xmpp-101-a-video-from-the-xmpp-summit/](http://metajack.im/2010/02/16/xmpp-101-a-video-from-the-xmpp-summit/) (OGV, HTML5/Firefox)

### OneSocialWeb

*   Einführung in OneSocialWeb (deutsch): [http://notizblog.org/2010/02/11/onesocialweb/](http://notizblog.org/2010/02/11/onesocialweb/)
*   OneSocialWeb: [http://onesocialweb.org](http://onesocialweb.org/)[/](http://onesocialweb.org/)
*   Das Draft-Protokoll: [http://onesocialweb.org/doc](http://onesocialweb.org/docs-protocol.htm)[s](http://onesocialweb.org/docs-protocol.htm)[-protocol.htm](http://onesocialweb.org/docs-protocol.htm)

## Und dann noch...

*   Twitter Konferenz: [http://chirp.twitter.com/](http://chirp.twitter.com/)
*   IdentityCamp Mannheim: [http://www.identitycamp.de/](http://www.identitycamp.de/)

Viel Spaß beim anschaun: <object width="480" height="295"><param name="movie" value="http://www.youtube.com/v/o7Pt0PXC_Bs&amp;hl=de_DE&amp;fs=1&amp;"><param name="allowFullScreen" value="true"><param name="allowscriptaccess" value="always"><embed src="http://www.youtube.com/v/o7Pt0PXC_Bs&amp;hl=de_DE&amp;fs=1&amp;" type="application/x-shockwave-flash" allowscriptaccess="always" allowfullscreen="true" width="480" height="295"></object> <object width="480" height="295"><param name="movie" value="http://www.youtube.com/v/dApxhDbqG_k&amp;hl=de_DE&amp;fs=1&amp;"><param name="allowFullScreen" value="true"><param name="allowscriptaccess" value="always"><embed src="http://www.youtube.com/v/dApxhDbqG_k&amp;hl=de_DE&amp;fs=1&amp;" type="application/x-shockwave-flash" allowscriptaccess="always" allowfullscreen="true" width="480" height="295"></object>
