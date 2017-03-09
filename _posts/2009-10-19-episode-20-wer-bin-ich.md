---
ID: 205
post_title: 'Episode 20 &#8211; Wer bin ich?'
author: Christian Scholz
post_date: 2009-10-19 13:10:14
post_excerpt: ""
layout: post
permalink: /205/episode-20-wer-bin-ich/
published: true
enclosure:
  - |
    http://openwebpodcast.de/mp3/openweb20.mp3
    67948672
    audio/mpeg

---
Nachdem der <a href="http://blog.openwebpodcast.de/187/owp19/">letzte Podcast</a> von Sebastian als technisch bezeichnet wurde, kommt nun einer, der auch wirklich technisch ist. Es geht um allerlei, was ich "<strong>Benutzerbezeichner</strong>" genannt habe, also die Frage, wie man sich als User im globalen Netzwerk mit einem globalen Identifier anmelden kann und warum das eigentlich sinnvoll ist.

Wir gehen dann noch im Detail auf die entsprechenden Standards ein, die eine Rolle spielen.

<audio controls>
  <source src="http://openwebpodcast.de/mp3/openweb20.mp3" type="audio/mpeg">
  Ihr Browser unterstützt diesen Audio-Player nicht.
</audio>
<small>Länge: 1:13h (64,8 MB), <a href="http://openwebpodcast.de/mp3/openweb20.mp3">Download MP3</a></small>
<h3>News</h3>
<ul>
	<li>Google Wave Hackathon, 18.10.2009, St.Oberholz, Berlin (somit vorbei)</li>
	<li>Veröffentlichung <a href="http://mrtopf.de/blog/en/introducing-webfinger-and-a-python-client/">pydataportability.discover</a></li>
</ul>
<h3>User-Identifier</h3>
<ul>
	<li>Wofür braucht man User-Identifier? Was ist das Problem?</li>
	<li>Welche Arten von User-Identifiers gibt es?
<ul>
	<li>URLs (OpenID)</li>
	<li>E-Mail</li>
	<li>Cardspace</li>
</ul>
</li>
	<li>2 Themenbereiche: Identifikation, Service Discovery</li>
</ul>
<h3>Die unterschiedlichen Systeme</h3>
<ul>
	<li><a href="http://code.google.com/p/webfinger/">Webfinger</a>, <a href="http://www.eaut.org">EAUT</a></li>
	<li><a href="http://code.google.com/p/google-sgnodemapper/">SGN</a></li>
	<li><a href="http://www.inames.net/">XRI</a></li>
	<li><a href="http://www.oasis-open.org/committees/download.php/34724/xrd-1.0-wd09.html">XRD</a> (Draft 9)</li>
	<li><a href="http://de.wikipedia.org/wiki/XRDS">XRDS</a></li>
	<li><a href="http://xrds-simple.net">XRDS-Simple</a></li>
	<li><a href="http://hueniverse.com/discovery/">LRDD und Discovery</a></li>
</ul>

<h3>Webfinger Beispiele</h3>

<ul><li>Host Meta:<ul>
<li>Yahoo: <a href="http://yahoo.com/.well-known/host-meta">http://yahoo.com/.well-known/host-meta</a></li>
<li>Google: <a href="http://gmail.com/.well-known/host-meta">http://gmail.com/.well-known/host-meta</a></li>
<li>YIID: <a href="http://yiid.com/.well-known/host-meta">http://yiid.com/.well-known/host-meta</a></li></ul></li>
<li>Beispielprofil:<ul>
<li>Google: <a href="http://www.google.com/s2/webfinger/?q=bradfitz@gmail.com">http://www.google.com/s2/webfinger/?q=bradfitz@gmail.com</a></li></ul>
</li></ul>

Um sein Google Profil für Webfinger zu aktivieren, muss man im <a href="http://groups.google.com/group/webfinger/browse_thread/thread/46fe84c1e38ab715">Google Profil zu seinen Interessen “webfingeralpha” hinzufügen</a>. (via <a href="http://blog.openwebpodcast.de/205/episode-20-wer-bin-ich/comment-page-1/#comment-154">Peter</a>)

Webfinger über YQL: <a href="http://developer.yahoo.com/yql/console/?q=select%20*%20from%20webfinger%20where%20account%3D%27beestage%40yahoo.com%27&env=http%3A%2F%2Fdatatables.org%2Falltables.env">http://developer.yahoo.com/yql/console/?q=select%20*%20from%20webfinger%20where%20account%3D%27beestage%40yahoo.com%27&env=http%3A%2F%2Fdatatables.org%2Falltables.env</a>
