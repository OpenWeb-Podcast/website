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
<img src="http://blog.openwebpodcast.de/wp-content/uploads/2010/03/xmpp.png" alt="xmpp" title="xmpp" width="74" height="76" class="alignright size-full wp-image-321" />Vor ein paar Wochen wurde auf der <a href="http://fosdem.org/2010/">FOSDEM</a> erstmals das Projekt <em><a href="http://onesocialweb.org/">OneSocialWeb</a></em> vorgestellt: ein <em>free, open, and decentralized social</em> Network basierend auf XMPP. <a href="http://mrtopf.de">Christian</a> und ich (<a href="http://notizblog.org/">Matthias</a>) haben uns für dieses Thema mal wieder tatkräftige Unterstützung geholt: <a href="http://identi.ca/rkallensee">Raphael Kallensee</a> arbeite als Web-Entwickler in Mannheimer und bloggt unter <a href="http://raphael.kallensee.name/">raphael.kallensee.name</a>.

Viel Spaß beim hören:

<audio controls>
  <source src="http://openwebpodcast.de/mp3/openweb26.mp3" type="audio/mpeg">
  Ihr Browser unterstützt diesen Audio-Player nicht.
</audio>
<small>Länge: 0:57h (49.8 MB), <a href="http://openwebpodcast.de/mp3/openweb26.mp3">Download MP3</a></small>

(weiter unten gibt es auch noch zwei Videos)

<h3>News</h3>
<ul>
	<li>CCC und Innenminister fordern  Datenbrief: <a href="http://www.ccc.de/datenbrief">http://www.ccc.de/datenbrief</a></li>
	<li><a href="http://openidentityexchange.org/">http://openidentityexchange.org/</a> (Drummond Reed darüber: <a href="http://datawithoutborders.net/dwb12/%29">http://datawithoutborders.net/dwb12/)</a></li>
	<li><a href="http://www.tagesschau.de/inland/bundesverfassungsgericht144.html">Karlsruhe kippt Vorratsdatenspeicherung</a></li>
	<li>Action Streams:
<ul>
	<li><a href="http://www.gravity7.com/blog/media/2010/02/action-streams-blue-sky-proposal.html">http://www.readwriteweb.com/archives/action_streams_a_new_idea_for_social_networks.php</a></li>
	<li><a href="http://www.gravity7.com/blog/media/2010/02/action-streams-blue-sky-proposal.html">http://www.gravity7.com/blog/media/2010/02/action-streams-blue-sky-proposal.html</a></li>
	<li><a href="http://wiki.activitystrea.ms/Actions">http://wiki.activitystrea.ms/Actions</a></li>
</ul>
</li>
	<li>Facebook-Chat  via XMPP: <a href="http://blog.facebook.com/blog.php?post=297991732130">http://blog.facebook.com/blog.php?post=297991732130</a></li>
</ul>
<h2>Thema: XMPP</h2>
<blockquote>"XMPP is to Jabber as HTTP  is to the Web." - Peter Saint-André</blockquote>
<ul>
	<li>langlebige  TCP-Verbindung</li>
	<li>2 XML-Streams: Client-Server und  Server-Client</li>
	<li>Die einzelnen XML-Snippets nennen sich Stanzas</li>
	<li>Verschiedene Typen: message, presence, iq</li>
	<li>XMPP ist dezentral</li>
	<li>Client/Server-Architektur, aber auch  federated</li>
	<li>ähnlich  IRC bzw. E-Mail von der Dezentralität her</li>
	<li>user@server.tld sind bare JIDs</li>
	<li>user@server.tld/&lt;resource&gt; sind  full JIDs</li>
	<li>Dadurch  kann man mehrfach eingeloggt sein</li>
	<li>Da gibt es auch noch eine Priorität,  denn Kontakte schreiben zuerst  normalerweise an die  Bare JID.</li>
	<li>Man  kann auch direkt an die full JIDs schicken (passiert nach Gesprächsbeginn  normalerweise dann automatisch durch den Client)</li>
	<li>"Transports" können als eine Art  Gateway zu proprietären IM-Netzwerken verwendet werden</li>
	<li>Installationen:
<ul>
	<li>Ursprungsserver: Jabber.org</li>
	<li>Google Talk
<ul>
	<li>Jede E-Mail-Adresse ist ein  XMPP-Account</li>
</ul>
</li>
	<li>LiveJournal</li>
	<li>GMX/Web.de/1&amp;1
<ul>
	<li>Jede E-Mail-Adresse ist ein  XMPP-Account</li>
</ul>
</li>
	<li>talkr.im</li>
</ul>
</li>
	<li>Server:
<ul>
	<li>ejabberd</li>
	<li>Openfire</li>
	<li>Tigase</li>
	<li>Prosody</li>
</ul>
</li>
	<li>Was für Clients gibt es? Beispiele:
<ul>
	<li>Psi</li>
	<li><a href="http://www.pidgin.im/">http://www.pidgin.im/</a></li>
	<li>Adium, iChat</li>
	<li>Miranda</li>
	<li>Gajim</li>
	<li>Empathy</li>
	<li>bald: Swift (swift.im)</li>
	<li>--&gt; <a href="http://xmpp.org/software/clients.shtml">http://xmpp.org/software/clients.shtml</a></li>
</ul>
</li>
	<li>Sehr stark und einfach erweiterbar (z.B. mit Namespaces)
<ul>
	<li>Viele der wichtigen Features sind "Erweiterungen"</li>
	<li>Community-getriebener Prozess der  Standardisierung</li>
	<li>XSF  (XMPP Standards Foundation) leitet die Standardisierung</li>
</ul>
</li>
	<li>Beispiele für Erweiterungen
<ul>
	<li>Multi-User Chat (MUC)</li>
	<li>PubSub</li>
	<li>PEP (Personal Eventing Protocol)</li>
	<li>Jingle (Voice-Chat)</li>
	<li>Service Discovery</li>
	<li>BOSH: XMPP über HTTP
<ul>
	<li>ermöglicht Web-Clients, die  ausschließlich in JavaScript geschrieben sind</li>
</ul>
</li>
	<li>Location-Infos</li>
	<li>--&gt; <a href="http://xmpp.org/extensions/">http://xmpp.org/extensions/</a></li>
</ul>
</li>
	<li>Client-Bibliotheken für sehr viele  Sprachen verfügbar, Beispiele:
<ul>
	<li>JavaScript: Strophe.js</li>
	<li>PHP: xmpphp</li>
	<li>C: libstrophe</li>
	<li>Java: Smack</li>
	<li>Python: SleekXMPP; Twisted</li>
	<li>Ruby: XMPP4R</li>
	<li>--&gt; <a href="http://xmpp.org/software/libraries.shtml">http://xmpp.org/software/libraries.shtml</a></li>
</ul>
</li>
</ul>
<h3>Diverses</h3>
<ul>
	<li>OAuth über XMPP <a href="http://notizblog.org/2008/07/24/oauth-ueber-xmpp-jabber/">http://notizblog.org/2008/07/24/oauth-ueber-xmpp-jabber/</a></li>
	<li> AOL  und XMPP <a href="http://notizblog.org/2008/01/18/aol-will-xmppjabber-einsetzen/">http://notizblog.org/2008/01/18/aol-will-xmppjabber-einsetzen/</a></li>
	<li> WordPress  und XMPP <a href="http://notizblog.org/2009/09/14/xmpp-pubsub-on-wordpress-com/">http://notizblog.org/2009/09/14/xmpp-pubsub-on-wordpress-com/</a></li>
	<li> XMPP  Standards Foundation: <a href="http://xmpp.org/">http://xmpp.org/</a></li>
	<li>Einführung  in XMPP: <a href="http://www.slideshare.net/remko.troncon/xmpp-101">http://www.slideshare.net/remko.troncon/xmpp-101</a> bzw. <a href="http://metajack.im/2010/02/16/xmpp-101-a-video-from-the-xmpp-summit/">http://metajack.im/2010/02/16/xmpp-101-a-video-from-the-xmpp-summit/</a> (OGV, HTML5/Firefox)</li>
</ul>
<h3>OneSocialWeb</h3>
<ul>
	<li>Einführung  in OneSocialWeb (deutsch): <a href="http://notizblog.org/2010/02/11/onesocialweb/">http://notizblog.org/2010/02/11/onesocialweb/</a></li>
	<li>OneSocialWeb:  <a href="http://onesocialweb.org/">http://onesocialweb.org</a><a href="http://onesocialweb.org/">/</a></li>
	<li>Das  Draft-Protokoll: <a href="http://onesocialweb.org/docs-protocol.htm">http://onesocialweb.org/doc</a><a href="http://onesocialweb.org/docs-protocol.htm">s</a><a href="http://onesocialweb.org/docs-protocol.htm">-protocol.htm</a></li>
</ul>
<h2>Und dann noch...</h2>
<ul>
	<li>Twitter Konferenz: <a href="http://chirp.twitter.com/">http://chirp.twitter.com/</a></li>
	<li>IdentityCamp Mannheim: <a href="http://www.identitycamp.de/">http://www.identitycamp.de/</a></li>
</ul>

<!--more-->Viel Spaß beim anschaun:

<object width="480" height="295"><param name="movie" value="http://www.youtube.com/v/o7Pt0PXC_Bs&hl=de_DE&fs=1&"></param><param name="allowFullScreen" value="true"></param><param name="allowscriptaccess" value="always"></param><embed src="http://www.youtube.com/v/o7Pt0PXC_Bs&hl=de_DE&fs=1&" type="application/x-shockwave-flash" allowscriptaccess="always" allowfullscreen="true" width="480" height="295"></embed></object>

<object width="480" height="295"><param name="movie" value="http://www.youtube.com/v/dApxhDbqG_k&hl=de_DE&fs=1&"></param><param name="allowFullScreen" value="true"></param><param name="allowscriptaccess" value="always"></param><embed src="http://www.youtube.com/v/dApxhDbqG_k&hl=de_DE&fs=1&" type="application/x-shockwave-flash" allowscriptaccess="always" allowfullscreen="true" width="480" height="295"></embed></object>
