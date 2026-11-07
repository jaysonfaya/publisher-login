# publisher-login

Login-Weiterleitung für **THE PUBLISHER** (MPC-Plugin von JJ DA PLUG).

YouTube, Instagram, SoundCloud und TikTok verlangen eine https-Adresse als Ziel nach dem Login. Diese Seite nimmt den
Login-Code entgegen und leitet ihn sofort an die Handy-Seite deiner MPC im eigenen WLAN weiter (die Adresse der MPC steckt
im `state`). Es wird nichts gespeichert und nichts an andere Server geschickt. Weitergeleitet wird nur an private
Adressen (192.168.x.x, 10.x.x.x, 172.16–31.x.x).

Adresse für die Redirect-URI bei allen Plattformen: `https://jaysonfaya.github.io/publisher-login/`
