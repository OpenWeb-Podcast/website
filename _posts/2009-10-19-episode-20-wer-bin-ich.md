---
ID: 205
post_title: 'Episode 20 - Wer bin ich?'
author: Christian Scholz
post_date: 2009-10-19 13:10:14
post_excerpt: ""
layout: post
permalink: /205/episode-20-wer-bin-ich/
published: true
enclosure:
  - |
    https://openwebpodcast.de/mp3/openweb20.mp3
    67948672
    audio/mpeg
---

Nachdem der [letzte Podcast](http://blog.openwebpodcast.de/187/owp19/) von Sebastian als technisch bezeichnet wurde, kommt nun einer, der auch wirklich technisch ist. Es geht um allerlei, was ich "**Benutzerbezeichner**" genannt habe, also die Frage, wie man sich als User im globalen Netzwerk mit einem globalen Identifier anmelden kann und warum das eigentlich sinnvoll ist.

Wir gehen dann noch im Detail auf die entsprechenden Standards ein, die eine Rolle spielen.

<audio controls>
  <source src="https://openwebpodcast.de/mp3/openweb20.mp3" type="audio/mpeg">
  Ihr Browser unterstützt diesen Audio-Player nicht.
</audio>
<small>Länge: 1:13h (64,8 MB), <a href="https://openwebpodcast.de/mp3/openweb20.mp3">Download MP3</a></small>
### News

*   Google Wave Hackathon, 18.10.2009, St.Oberholz, Berlin (somit vorbei)
*   Veröffentlichung [pydataportability.discover](http://mrtopf.de/blog/en/introducing-webfinger-and-a-python-client/)

### User-Identifier

*   Wofür braucht man User-Identifier? Was ist das Problem?
*   Welche Arten von User-Identifiers gibt es?
    *   URLs (OpenID)
    *   E-Mail
    *   Cardspace
*   2 Themenbereiche: Identifikation, Service Discovery

### Die unterschiedlichen Systeme

*   [Webfinger](http://code.google.com/p/webfinger/), [EAUT](http://www.eaut.org)
*   [SGN](http://code.google.com/p/google-sgnodemapper/)
*   [XRI](http://www.inames.net/)
*   [XRD](http://www.oasis-open.org/committees/download.php/34724/xrd-1.0-wd09.html) (Draft 9)
*   [XRDS](http://de.wikipedia.org/wiki/XRDS)
*   [XRDS-Simple](http://xrds-simple.net)
*   [LRDD und Discovery](http://hueniverse.com/discovery/)

### Webfinger Beispiele

*   Host Meta:
    *   Yahoo: [http://yahoo.com/.well-known/host-meta](http://yahoo.com/.well-known/host-meta)
    *   Google: [http://gmail.com/.well-known/host-meta](http://gmail.com/.well-known/host-meta)
    *   YIID: [http://yiid.com/.well-known/host-meta](http://yiid.com/.well-known/host-meta)
*   Beispielprofil:
    *   Google: [http://www.google.com/s2/webfinger/?q=bradfitz@gmail.com](http://www.google.com/s2/webfinger/?q=bradfitz@gmail.com)

Um sein Google Profil für Webfinger zu aktivieren, muss man im [Google Profil zu seinen Interessen “webfingeralpha” hinzufügen](http://groups.google.com/group/webfinger/browse_thread/thread/46fe84c1e38ab715). (via [Peter](http://blog.openwebpodcast.de/205/episode-20-wer-bin-ich/comment-page-1/#comment-154))

Webfinger über YQL: [http://developer.yahoo.com/yql/console/?q=select%20*%20from%20webfinger%20where%20account%3D%27beestage%40yahoo.com%27&env=http%3A%2F%2Fdatatables.org%2Falltables.env](http://developer.yahoo.com/yql/console/?q=select%20*%20from%20webfinger%20where%20account%3D%27beestage%40yahoo.com%27&env=http%3A%2F%2Fdatatables.org%2Falltables.env)
